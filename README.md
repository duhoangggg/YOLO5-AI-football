# AI Football Insight

## Introduction
The goal of this project is to:

Detect and track players, referees, and the football using YOLO

Group players into teams based on shirt color using KMeans

Calculate ball possession for each team

Measure player movement and camera motion using optical flow

Apply perspective transformation to estimate distance in meters

Compute each player’s speed and distance covered

This project uses techniques from Computer Vision and Machine Learning, and helps practice real-world AI skills

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Datasets: 
- [Kaggel Dataset] :(https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data?select=clips)

- [Robowflow Football Dataset (used YOLO5)] :(https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc/dataset/1)