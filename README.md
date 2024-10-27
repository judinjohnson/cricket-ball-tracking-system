Cricket Ball Tracking System 🎯

# Basic Details
Team Name: Flywheel

# Team Members
- **Team Lead**: Naveen Wilson - Jyothi Engineering College, Thrissur
- **Member 2**: Judin Johnson - Jyothi Engineering College, Thrissur
- **Member 3**: Hameem Abdul Nassir - Jyothi Engineering College, Thrissur

# Project Description
Our project tracks the trajectory of a cricket ball using computer vision and deep learning techniques. The system can predict the ball’s path by analyzing video frames and providing real-time feedback to improve cricket officiating and player performance.

# The Problem
Tracking the ball in cricket manually is too slow and prone to human error. In international matches, we have a DRS system. But we miss those technologies in local matches due to a lack of budget. So the players and umpires miss key details during high-speed deliveries.

# The Solution
A deep learning-powered system that tracks the ball’s movement with unparalleled precision, providing data no one ever thought they needed. Even a mobile phone can be used for tracking purpose, so it can be implemented for local matches and also for training purpose.

# Technical Details
**Technologies/Components Used**
**For Software:**
- **Languages Used**: Python, HTML, JavaScript, CSS
- **Frameworks Used**: TensorFlow, PyTorch
- **Libraries Used**: OpenCV, YOLOv8, Scikit-learn
- **Tools Used**: Roboflow for dataset preparation, Jupyter Notebooks for model training

**For Hardware:** N/A (This is a software-based project)

# Implementation
**For Software:**
**Installation**
- pip install -r requirements.txt

**Run**
- python train.py --data data.yaml --epochs 100
- python detect.py --source cricket_video.mp4

## Project Documentation
### For Software:**

### Screenshots

#### Model Training
<img src="https://github.com/user-attachments/assets/a045b9c0-327a-4fb4-9bf8-f717a5de7bc7" alt="Model Training" width="500"/>

This screenshot shows the training process of the YOLOv8 model.

#### Ball Detection
<img src="https://github.com/user-attachments/assets/e0ac0a7b-2aea-4afd-b684-b1550d7c05e8" alt="Ball Detection" width="500"/>

This image shows the YOLOv8 model detecting the cricket ball from a test video.

#### Performance Measures
- ##### Class Loss
<img src="https://github.com/user-attachments/assets/45322e8f-6e03-4b00-8dbe-97e8e0cf6ad5" alt="Class Loss" width="400"/>

- ##### Confusion Matrix
<img src="https://github.com/user-attachments/assets/f02a614c-5ec2-4721-91e4-d751f6b66bc3" alt="Confusion Matrix" width="400"/>

Shows the performance measures of the model which we have built.

### Diagrams

#### Workflow
<img src="https://github.com/user-attachments/assets/1ac6ed5a-bcff-4ee4-bed6-e477c2d83e7d" alt="Workflow" width="500"/>)

This diagram explains the complete workflow, from video input to ball detection and trajectory prediction.

**Team Contributions**
- Naveen Wilson: Led the project, handled dataset preparation, model training, and deployment
- Judin Johnson: Contributed to video preprocessing and implementation of the detection pipeline
- Hameem Abdul Nassir: Assisted in evaluation, testing, and preparing results for the IEEE paper
