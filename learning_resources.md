# Learning Resources
Take a look through these resources to get a better understanding of the topics we're covering!

Check the topics in the [syllabus](./Syllabus.md#topic-schedule) to find links to playlists that cover exactly the same content we went over in class.

Presentations for each week can be found in the [presentations](./presentations/) folder


## General Resources
### Text
1. [Learn Git](https://learngitbranching.js.org/?locale=en_US)
1. [The Linux command line](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview)
1. [Robotics and Perception Textbook](https://www.roboticsbook.org/intro.html)
### Videos
1. [Broader view on Controls Matlab videos ](https://www.mathworks.com/videos/tech-talks.html)
1. [Linear algebra review (Gilbert Strang - MIT)](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8)


## Week 1 Resources
### Text
1. [Explanation of Individual 2D Transformation Matrices and Homogeneous Coordinates](https://graphicmaths.com/pure/matrices/matrix-2d-transformations/)
1. [Explanation of Combining Individual 2D Transformation Matrices](https://graphicmaths.com/pure/matrices/combining-transformations/)
### Videos
1. [Quaternions](https://www.youtube.com/watch?v=d4EgbgTm0Bg)
1. [Quaternion Interactive Tool](https://www.youtube.com/watch?v=zjMuIxRvygQ)
1. [Where Rotation Matrices Come From](https://www.youtube.com/watch?v=BKsZrkI6sro)

## Week 2 Resources
### Text
1. [Multiple View Geometry in Computer Vision](https://github.com/DeepRobot2020/books/blob/master/Multiple%20View%20Geometry%20in%20Computer%20Vision%20(Second%20Edition).pdf)
    - Great resource for computer vision
    - Check out Chapter 2 for projective geometry and transformations in 2D (homographies) and check out Chapter 4.1 for the Direct Linear Transform (the mathematical method used for computing homographies)
### Videos
1. [Discrete Convolutions (Most relevant to the filtering we convered)](https://www.youtube.com/watch?v=KuXjwB4LzSA)
1. [Continuous Convolutions](https://www.youtube.com/watch?v=IaSGqQa5O-M)
1. [Homogenous Coordinates](https://www.youtube.com/watch?v=MQdm0Z_gNcw)
    - Also includes explanations of the pinhole camera model and transformation matrices
    - Would recommend other explanations on this channel - he does a great job of breaking things down
1. [What Homographies Are](https://www.youtube.com/watch?v=B8kMB6Hv2eI)
1. [How to Compute Homographies](https://www.youtube.com/watch?v=l_qjO4cM74o)

## Week 3 Resources
### Text
1. [Discrete Bayes Filter Python Notebook Explanation](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python/blob/master/02-Discrete-Bayes.ipynb)
1. [Gaussians and Bayes' Theorem Python Notebook Explanation](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python/blob/master/03-Gaussians.ipynb)
1. [Particle Filter Python Notebook Explanation](https://github.com/rlabbe/Kalman-and-Bayesian-Filters-in-Python/blob/master/12-Particle-Filters.ipynb)
### Videos
1. [Bayes Filter Explanation](https://www.youtube.com/watch?v=0lKHFJpaZvE)
1. [Particle Filter 5 Minute Overview](https://www.youtube.com/watch?v=YBeVDxTHiYM)
1. [Particle Filter Explanation](https://www.youtube.com/watch?v=MsYlueVDLI0)

## Week 4 Resources
### Text
1. [Occupancy Grid Mapping Explanation](https://www.cs.cmu.edu/~16831-f14/notes/F14/16831_lecture06_agiri_dmcconac_kumarsha_nbhakta.pdf)
#### Some Current SLAM Solutions (There are a lot more than this!!!)
Most popular SLAM solutions are open source, and can be found on GitHub. Linked below are some current popular SLAM solutions. If you're interested in learning how they work under the hood, all of the repos have the paper introducing and explaining the SLAM solution in their README.
- [ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3)
    - Real-time SLAM library able to perform Visual, Visual-Inertial and Multi-Map SLAM with monocular, stereo and RGB-D cameras, using pin-hole and fisheye lens models (_description from ORB-SLAM3 README_)
- [VINS-Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion)
    - Optimization-based multi-sensor state estimator, which achieves accurate self-localization for autonomous applications (drones, cars, and AR/VR). VINS-Fusion is an extension of [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono), which supports multiple visual-inertial sensor types (mono camera + IMU, stereo cameras + IMU, even stereo cameras only) (_description from VINS-Fusion README_)
- [LIO-SAM](https://github.com/TixiaoShan/LIO-SAM)
    - Real-time lidar-inertial odometry package (_description from LIO-SAM README_)
- [DROID-SLAM](https://github.com/princeton-vl/DROID-SLAM)
    - Deep learning-based visual SLAM system that performs real-time camera pose estimation and dense 3D scene reconstruction using monocular, stereo, or RGB-D cameras
- [MultiCam SLAM](https://github.com/neufieldrobotics/MultiCamSLAM)
    - Generic visual SLAM framework for multi camera systems (_description from MultiCam SLAM README_)
    - Developed by the Institute for Experiential Robotics right here at Northeastern!

### Videos
1. [SLAM 5 Minute Overview](https://www.youtube.com/watch?v=BuRCJ2fegcc)
1. [SLAM 30 Minute Overview](https://www.youtube.com/watch?v=0I30M6yTklo)
1. [Introduction to Robot Mapping](https://www.youtube.com/watch?v=wVsfCnyt5jA)
1. [Occupancy Grid 5 Minute Overview](https://www.youtube.com/watch?v=8ckhPViqneg)
1. [Occupancy Grid Maps](https://www.youtube.com/watch?v=v-Rm9TUG9LA)