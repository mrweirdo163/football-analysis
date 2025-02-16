# football-analysis

![image](https://github.com/user-attachments/assets/44969a0d-dd96-4a14-8f1f-5e4d6c97283e)
## Introduction

The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, one of the best AI object detection models available. We will also train the model to improve its performance. Additionally, we will assign players to teams based on the colors of their t-shirts using Kmeans for pixel segmentation and clustering. With this information, we can measure a team's ball acquisition percentage in a match. We will also use optical flow to measure camera movement between frames, enabling us to accurately measure a player's movement. Furthermore, we will implement perspective transformation to represent the scene's depth and perspective, allowing us to measure a player's movement in meters rather than pixels. Finally, we will calculate a player's speed and the distance covered. This project covers various concepts and addresses real-world problems, making it suitable for both beginners and experienced machine learning engineers.

![image](https://github.com/user-attachments/assets/53a9488b-5563-4752-b48f-536ee4b41966)

## Modules Used

> **YOLO**: AI Object Detection
> **K-means**: Pixel segmentation and clustering to detect t-shirt color
> **Optical Flow**: Measure camera movement
> **Speed and Distance Calculation**

## Trained Model and Data
> YOLO v5
> We use this [dataset](https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc/dataset/1) on Roboflow to Fine-tuning YOLO model.
