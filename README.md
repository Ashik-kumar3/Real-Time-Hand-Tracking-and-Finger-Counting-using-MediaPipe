# Finger Counting using MediaPipe and Computer Vision

## Overview

This project implements a real-time Finger Counting System using MediaPipe and OpenCV.

The system detects a user's hand through a webcam, identifies hand landmarks, and counts the number of fingers that are raised. The count is displayed live on the video stream.

This project demonstrates the application of Computer Vision, Hand Tracking, and Human-Computer Interaction using MediaPipe's hand landmark detection framework.

---

## Problem Statement

Traditional methods of gesture recognition often require specialized hardware or sensors. With advancements in computer vision, hand gestures can now be recognized using a standard webcam.

The objective of this project is to develop a real-time finger counting system capable of accurately detecting and counting raised fingers from live video input.

---

## Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy

---

## Project Workflow

1. Capture Webcam Video
2. Detect Hand using MediaPipe
3. Extract Hand Landmarks
4. Identify Finger Positions
5. Determine Raised Fingers
6. Count Total Fingers
7. Display Finger Count

---

## System Architecture

```text
Webcam Input
      ↓
Hand Detection
      ↓
Hand Landmark Extraction
      ↓
Finger State Analysis
      ↓
Finger Counting
      ↓
Live Display Output
```

---

## MediaPipe Hand Landmarks

The system uses MediaPipe Hands to detect:

* 21 Hand Landmarks
* Finger Tips
* Finger Joints
* Palm Coordinates

Detected Fingers:

* Thumb
* Index Finger
* Middle Finger
* Ring Finger
* Little Finger

---

## Features

* Real-Time Finger Counting
* Hand Tracking
* Landmark Detection
* Live Webcam Processing
* Fast and Lightweight System
* Multiple Finger Recognition
* Gesture-Based Interaction

---

## Finger Counting Logic

The system determines whether a finger is raised by comparing the coordinates of finger tips with lower finger joints.

### Example

| Raised Fingers | Output |
| -------------- | ------ |
| Thumb          | 1      |
| Thumb + Index  | 2      |
| Three Fingers  | 3      |
| Four Fingers   | 4      |
| Open Palm      | 5      |

---

## Applications

* Gesture-Controlled Systems
* Touchless User Interfaces
* Smart Classrooms
* Interactive Games
* Human-Computer Interaction
* Sign Language Preprocessing
* Virtual Presentation Controls

---

## Results

The system successfully detects hand landmarks and accurately counts the number of raised fingers in real time.

MediaPipe enables robust hand tracking even under moderate lighting and movement conditions, making the solution suitable for real-world gesture-based applications.

---

## Future Improvements

* Hand Gesture Recognition
* Virtual Mouse Control
* Volume Control using Hand Gestures
* Sign Language Recognition
* AI-Based Gesture Classification
* Multi-Hand Tracking
* Smart Home Control System

---

## Learning Outcomes

This project demonstrates:

* Computer Vision Fundamentals
* MediaPipe Hand Tracking
* Landmark Detection
* Real-Time Video Processing
* Gesture Recognition
* Human-Computer Interaction

---

