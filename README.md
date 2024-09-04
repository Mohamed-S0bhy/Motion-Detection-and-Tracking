# Motion Tracking System Using OpenCV
### Project Overview
This project implements a motion tracking system using Python and OpenCV. The system processes video streams in real-time, detects motion by comparing frames, and highlights movement with bounding boxes. The output is saved as a video file.

### Features
Real-time motion detection
Bounding boxes to highlight detected movement
Video output with marked motion

### Requirements
Python 3.x
OpenCV 4.x or higher

### How It Works
Frame Differencing: The program reads consecutive frames from the video, computes the difference between them, and identifies regions with significant changes.
Bounding Boxes: Contours are drawn around detected motion to highlight areas of activity.
Output: A video file is generated with marked motion areas.
