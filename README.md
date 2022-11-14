# IntelligentRobotics2223
This package contains the launch file to do the exercise 4 with AprilTag library.

## Installation Guide
### Install AprilTag library
Clone the following repositories in your workspace (src folder):
- Apriltag: https://github.com/AprilRobotics/apriltag.git
- Apriltag_ros: https://github.com/AprilRobotics/apriltag_ros.git

### Download the BAG
Download the BAGs from the following link: https://drive.google.com/drive/folders/1gJWo28Gj0dLpFLCWEjEVjI-vEPymD7mp?usp=sharing


## Run the exercise
### Exercise 4.1 Part A
- Run the bag_ex_41
- Launch the apriltag node: roslaunch exercise_4_1 iaslab_apriltag.launch

### Exercise 4.1 Part B
- Launch the static transform: roslaunch exercise_4_1 static_robot_tf.launch
- Run the bag_ex_41
- Launch the apriltag node: roslaunch exercise_4_1 iaslab_apriltag.launch