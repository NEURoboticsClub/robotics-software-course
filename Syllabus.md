# NURobotics Robotics Software Course - Fall 2026

The NURobotics Robotics Software course is designed to prepare you to work on software for NURobotics competitive teams. This program offers practical experience writing code using C++ and ROS. It also covers some of the fundamental concepts of robotics.


## Instructors

- Casey Goyette


## Meeting Schedules

### General Software Training Meetings
Thursdays 6:00pm - 8:00pm
- 10/1 - Richards 236
- 10/8 - Richards 236
- 10/15 - Richards 236
- 10/22 - Dodge 050
- 10/29 - Richards 253
- 11/5 - Richards 254
- 11/12 - Richards 236
- 11/19 - Shillman 135
- 12/3 - Richards 254


## Resources

- [RoboJackets Training YouTube Channel](https://www.youtube.com/channel/UCh3TLV-vQzzcWGQ4u2jsMOw)

  Supplemental training videos to review anything we go over in class.

- [Software Training Repository](https://github.com/NEURoboticsClub/robotics-software-course)

  The GitHub repository that hosts most of the resources for the software training program, including project instructions and starter code.

- [STSL Repository](https://github.com/RoboJackets/stsl)

  The Software Training Support Library repository. This holds support code for the training projects.

## Prerequisites

We will assume that students are familiar with the concepts covered in [AP Computer Science A](https://apstudents.collegeboard.org/courses/ap-computer-science-a). Topics we assume knowledge of will be briefly covered in Week 0 content. Topics covered in AP Computer Science A that have special syntax, properties, or behavior in C++ will be covered in the main course content.

Students should also be comfortable with math at the level of [AP Calculus AB](https://apstudents.collegeboard.org/courses/ap-calculus-ab). Derivatives and integrals will show up throughout the course.

## Topic Schedule

The content of this course is divided into three tracks: Robotics Theory, ROS, and C++. The Robotics Theory track will survey the concepts and math that make intelligent mobile robots work. The ROS track will cover how to use the Robot Operating System to program robots. The C++ track will introduce the C++ programming language, popular in robotics applications.

Week | Robotics Theory | ROS | C++ | Projects
--- | --- | --- | --- | --- |
0 | | | [AP CS Review](https://youtube.com/playlist?list=PL1R5gSylLha2AOCmSaLdDlBMug5XFNfwv)
1 | [Linear Algebra, Sensors, Coordinate Frames](https://youtube.com/playlist?list=PL1R5gSylLha2RjafLHG9lqNqZ2rzH_hdQ) | [Introduction to ROS and useful tools](https://youtube.com/playlist?list=PL1R5gSylLha0y1U3yHAkCYJXXL-GiJDwF) | [Introduction to C++](https://youtube.com/playlist?list=PL1R5gSylLha1TChL2Lkm6PQQnOPRSIpDK) | [Coordinate Frame Transforms](projects/week_1/Instructions.md)
2 | [Computer Vision](https://youtube.com/playlist?list=PL1R5gSylLha0cFU3nGomLr8cIUaKun6bl) | [rclcpp Basics, Timers, Topics](https://youtube.com/playlist?list=PL1R5gSylLha0wxbvXIiNeEr12aoO_VX_8) | [Classes, Inheritance, std::bind](https://youtube.com/playlist?list=PL1R5gSylLha3KemZ2wqInhNm-db8kR88r) | [Color-based Obstacle Detection](projects/week_2/Instructions.md)
3 | [Probability, Particle Filters](https://youtube.com/playlist?list=PL1R5gSylLha2ylxbALvguW15qf-mHjsGm)  | [Launch, Parameters](https://youtube.com/playlist?list=PL1R5gSylLha3YMGovXmHZGn9wVrAChkxk) | [Lifetime, References, Pointers](https://youtube.com/playlist?list=PL1R5gSylLha2BEzoEGSt-EAmx4HbvQ7RZ) | [Particle Filter Localization](projects/week_3/Instructions.md)
4 | [Optimization](https://youtube.com/playlist?list=PL1R5gSylLha0975HYnqN-Jq4Jx0r7LiTu) | [Services](https://youtube.com/playlist?list=PL1R5gSylLha3QucE7Smr0-YvnV70fZkoq) | [Concurrency Basics](https://youtube.com/playlist?list=PL1R5gSylLha1B3HQldnfhFu4_rVZnW55q) | [Gradient Descent Optimization](projects/week_4/Instructions.md)
5 | [SLAM, Mapping](https://www.youtube.com/watch?v=CgiVz-KMBH0&list=PL1R5gSylLha1cX02r8hiMA85vPmfSYHP_) | [TF, Custom Interfaces](https://youtube.com/playlist?list=PL1R5gSylLha2od_7P9YuSSLsKCd3vtCY7) | [Lambdas](https://youtube.com/playlist?list=PL1R5gSylLha1huMeonsTMxqU8DE7m_zWh) | [Mapping](projects/week_5/Instructions.md)
6 | [Kalman Filters](https://youtube.com/playlist?list=PL1R5gSylLha0j_tmn3YhTTs90-pUFuZH9) | [Quality of Service](https://youtube.com/playlist?list=PL1R5gSylLha0IvTKCOckpL5QvVB4Hn-97) | [Templates](https://youtube.com/playlist?list=PL1R5gSylLha3kQMd1tIxDywbOWNNYaiJM) | [Kalman Filter Tracking](projects/week_6/Instructions.md)
7 | [Control](https://youtube.com/playlist?list=PL1R5gSylLha3nYaE3PTmJIon7GgIxzr_M) | [Actions](https://youtube.com/playlist?list=PL1R5gSylLha1qUf5ngWco_EnNfYsTzAUc) | [LQR Controller](projects/week_7/Instructions.md)
8 | [Path Planning](https://youtube.com/playlist?list=PL1R5gSylLha1epFZYz_z2BKO0sSXNPcjM) | [Bags](https://youtube.com/playlist?list=PL1R5gSylLha2i-XmvxwzfPgBKSJ6EKcF4) | [Iterators, Algorithms](https://youtube.com/playlist?list=PL1R5gSylLha1l1f8OcxXCVtnh6XmPzFzU) | [A-Star Path Planning](projects/week_8/Instructions.md)


<!-- Coming Soon: 
- C++ practice 
  - indexing, sorting, mattrix operations -->


## Additional Resources
Check out [Learning Resources](./learning_resources.md) for resources to get a better understanding of the topics we're covering!


## Project Schedule

Each week will culminate in a programming project that uses the tools and techniques covered. The projects build on each other to produce the complete software stack needed to get a custom robot to execute a challenge game.

Week | Title |  | Description
--- | --- | --- | ---
1 | Coordinate Frame Transforms | [Instructions](projects/week_1/Instructions.md) | Transform fiducial detections from the camera's frame to the robot's body frame.
2 | Color-based Obstacle Detection | [Instructions](projects/week_2/Instructions.md) | Use HSV color detection and a projective homography to find obstacles near the robot.
3 | Particle Filter Localization | [Instructions](projects/week_3/Instructions.md) | Use a particle filter to localize the robot based on fiducial detections.
4 | Gradient Descent Optimization | [Instructions](projects/week_4/Instructions.md) | Use gradient ascent to guide the robot to the highest simulated elevation on the map.
5 | Mapping | [Instructions](projects/week_5/Instructions.md) | Build a map of the environment with a probablistic occupancy grid.
6 | Kalman Filter Tracking | [Instructions](projects/week_6/Instructions.md) | Track mineral deposits with a kalman filter.
7 | LQR Controller | [Instructions](projects/week_7/Instructions.md) | Control the robot's motion with an LQR controller.
8 | A-Star Path Planning | [Instructions](projects/week_8/Instructions.md) | Teach the robot how to avoid obstacles with the A-Star path planning algorithm.
