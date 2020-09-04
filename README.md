uvbot
===
uvbot is a ROS wrapper of the aimijia uvbot robot. For details and instructions, please see the official website, www.aimiplus.com
<br>
Install
---
Officially only linux operating systems with ROS kinetic are supported. 
<br>
# Dependencies
AprilRobotics/apriltag, the installation steps can be referred to, https://github.com/AprilRobotics/apriltag
<br>
# Install
'''
mkdir -p ~/catkin_ws/src                # Make a new workspace 
cd ~/catkin_ws/src                      # Navigate to the source space
git clone https://github.com/zhonghang1187151422/uvbot.git      # Clone uvbot library
cd ~/catkin_ws                          # Navigate to the workspace
rosdep install --from-paths src --ignore-src -r -y  # Install any missing packages
catkin_make                             # Build all packages

'''
