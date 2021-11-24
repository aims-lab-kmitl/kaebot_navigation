# SLAM and Navigation Package for KaeBOT


# Instruction for SLAM
1. Prepare your environment
      1. Understanding, your robot will be the master and you will remote from your labtop.
      2. Modify .bashrc for both robot and labtop
      3. [On robot] Prepare the `ROS_MASTER_URI=http://<ROBOT IP ADDRESS>:11311` and `ROS_HOSTNAME=<ROBOT IP ADDRESS>`
      4. [On labtop] Prepare the `ROS_MASTER_URI=http://<ROBOT IP ADDRESS>:11311` and `ROS_HOSTNAME=<LABTOP IP ADDRESS>`
3. [On robot] Go to `~/catkin_ws/src`
4. [On robot] git clone https://github.com/aims-lab-kmitl/kbot_navigation
5. [On robot] Go to `~/catkin_ws` Then build using `catkin_make`
6. [On robot] Run SLAM using `roslaunch kbot_navigation slam.launch`

### Debug step
1. [On labtop] Go to `~/catkin_ws/src`
2. [On labtop] git clone https://github.com/aims-lab-kmitl/kbot_rviz_display
3. [On labtop] Go to `~/catkin_ws` Then build using `catkin_make`
4. [On labtop] `roslaunch kbot_slam kbot_slam.launch`


## Author
AIMS Research and Development Team
