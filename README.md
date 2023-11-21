## Traffic Sign Detection
### Overview

In this project, I built Traffic Sign Detection program using Support Vector Machine (SVM). Input and output as below:

- Input: a picture in which there are traffic signs
- Output: coordinates and class of traffic signs in the input picture
  
The project includes 2 main module which are: 

1. Traffic sign classifier using SVM 
2. Object detection model using Sliding Window technique

Other techniques were also utilized are (i) Histogram of oriented gradients (HOG) to represent better feature for images, (ii) Pyramid image technique to make objects with smaller/bigger size fit the window size and (iii) Non-Maximum Suppression technique to keep the bounding box with the highest confidence score while eliminating overlapping bounding boxes.

![image](https://github.com/huongnd12/traffic-sign-detection/assets/57044034/0f81dbdd-903d-4859-9923-b0582d4abb84)

Dataset contains 877 images with 4 classes (trafficlight, stop, speedlimit, crosswalk)

![image](https://github.com/huongnd12/traffic-sign-detection/assets/57044034/b1090107-cfe6-4670-a89b-85948a447bf1)

### Output
Evaluation with accuracy score:
- On training set: 0.9986684420772304
- On validation set: 0.9659442724458205

Output image with traffic sign detection:

![image](https://github.com/huongnd12/traffic-sign-detection/assets/57044034/5265df8a-1eb8-4ce8-a8aa-994a3b5462d9)

### Further work
One of problems of this program is the real-time issue.
