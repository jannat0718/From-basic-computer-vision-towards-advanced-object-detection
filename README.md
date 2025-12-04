## 🎬 IPCV Individual Assignment: From Basic Computer Vision to Advanced Object Detection

**Overview**
This repository contains the implementation and final output video for IPCV Assignment 2, which explores a complete computer-vision workflow applied to a 1-minute self-recorded video.
The goal is to demonstrate fundamental image processing, frequency-domain filtering, object detection, and creative computer vision techniques—structured exactly according to the assignment requirements.

**Assignment Structure**
1. Input Video Processing
   - Loaded frames from the input video
   - Resized frames and divided processing into four timed segments
     
2. Part 1 (0–10s): Spatial-Domain Processing
   - Blurring/smoothing using a custom kernel
   - Image sharpening
   - Sobel edge detection
   - Canny edge detection
     
3. Part 2 (10–20s): Frequency-Domain Processing
   - Discrete Fourier Transform of each frame
   - Magnitude spectrum visualization
   - Low-pass filtering
   - High-pass filtering
   - Band-pass filtering
   - Inverse Fourier Transform to reconstruct filtered frames
     
4. Part 3 (20–40s): Object Detection on Student Card
   a. Template-Based Detection: Performed template-based matching to locate each item
     - S-number digits
     - University of Twente logo
     - Student ID photo
  b. Student Card Region Extraction
    - Detected card region using contour-based localization
    - Cropped the card area for improved matching
  c. Optical Flow Tracking
    - Computed motion of feature points between frames
    - Visualized motion using directional arrows
      
5. Part 4 (40–60s): Freestyle Section
   - Combined multiple image processing and tracking methods
   - Added custom visual effects based on motion and object behavior
   - Produced a creative final sequence
     
6. Output Video Generation
   - Combined all processed frames into a single output video
   - Exported the final sequence in MP4 format
     
**Input & Output**
All input videos, output video, and supporting resources are available via Google Drive.
https://drive.google.com/drive/folders/1W3nFJ-uLfL7x2l6_Fg1he5npqMXoYtqg?usp=drive_link
