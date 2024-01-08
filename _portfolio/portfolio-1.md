---
title: "**Perception Machine Learning Engineer** - DEKA Research and Development Corporation"
excerpt: "Duration: January 2021 - Present"
collection: portfolio
---

## 1. Autonomous Robotics 
### 1.1 Delivery Robot - FedEx ROXO 
### 1.2 Security Robot 

- Initiated role with focus on terrain classification within images to enhance robot navigability.
  
- Trained and optimized a segmentation model for RGB images, overcoming challenges in differentiating crucial elements like curbs, grass types, and surface irregularities, pivotal for robot navigation.
  
- Spearheaded the integration of depth information via stereo cameras to mitigate model limitations and enhance environmental feature recognition for adaptive robot navigation.
  
- Addressed class imbalance issues by implementing the Focal Loss function, significantly enhancing model performance on underrepresented classes.

*Challenges and Innovations:*

- *Evolving Project Challenges:* Adapted to frequent changes in the project's scope and robot configuration, managing data redundancy and perspective variations via ongoing adjustments and data augmentation.

- *Depth-Related Issues:* Worked on refining depth perception algorithms to handle complexities arising from reflections, varying lighting, and challenging environmental conditions.

*Methodologies Implemented:*

- *Deterministic Method:* Leveraged depth data for analysis, applying techniques such as de-projection, noise reduction, voxelization, and edge mapping for systematic environment representation and analysis.

- *Multi-task Model:* Developed models utilizing depth and RGB data for boundary detection, segmentation, and depth hole filling, addressing hardware constraints and lack of ground truth data.

*Notable Achievements:*

- Developed a deep learning sensor fusion model leveraging lidar, radar, mono, and stereo cameras for a comprehensive global occupancy grid, enhancing terrain analysis and drivability assessment.

- Created efficient pipelines for active machine learning, achieving an 84% overall accuracy in semantic segmentation and a 94% accuracy in scene text recognition for number plate identification.

- Formulated algorithms to fill depth holes in stereo camera data, resulting in accurate algorithmic scene segmentation for discerning drivable and non-drivable surfaces.

- Executed ROS and C++ algorithms (RANSAC, PnP, ICP) for automation within the project.

This role has continuously involved navigating evolving project scopes, adapting to technological constraints, and innovating methodologies to advance the field of computer vision and robotics.

## 2. Medical Devices

### 2.1 Infusion Pump 
Delivers medications into a patient's body in a controlled manner.
- Engineered a comprehensive system employing vision detection algorithms, notably Hough transforms, analyzing RGB images captured by the pump's camera. This system accurately tracks drops and streams, precisely calculating the liquid flow rate.
- Implemented a versatile cost function for informed decision-making based on various detection outputs.
- Leveraged dynamic time warping (DTW) and Fourier transforms to synchronize flow estimation outputs with ground truth (scale data) accurately.

### 2.2 Insulin Pump
Provides precise insulin doses to manage blood glucose levels in individuals with diabetes.
- Designed a personalized differential equation model to compute basal and bolus insulin rates using continuous glucose monitor readings. This model considers meal times, types, age, and gender to offer tailored insulin dosage recommendations.
- Currently exploring Reinforcement Learning, Transformer, and GAN techniques on time series data to enhance insulin pump autonomy and reliability. The goal is to optimize insulin delivery without relying on user-input meal information.
- Additionally, developed a computer vision method to identify weld defects during device manufacturing. Employed various texture detection methods and Euclidean distance transform to assess weld thickness and identify defects.

### 2.3 Kidney Transportation Box
Developed a segmentation model to monitor changes in the size and color of kidneys, providing insights into kidney health for both pig and human kidneys. This model offers valuable information for doctors to better understand the kidney's condition.
```

This format organizes the information into separate sections for Autonomous Robotics and Medical Devices, maintaining the structure and content provided. Adjustments can be made as needed based on specific formatting or content requirements.

