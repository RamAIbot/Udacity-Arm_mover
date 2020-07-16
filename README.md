# Udacity-Arm_mover
Simple Arm_Mover in gazebo

Initially when the robot's joints (2 joints) is in 0,0 radians angle, the camera points to the sky og the environment.
Whenever the camera points to sky (Uniform pixels (gray) in image) and arm is not moving the GoToPosition service is called and the Arm is moved 90 degress or 1.57 radians
in both joints. Now the camera can clearly see the dice infront of the robot.


<p align="center">
<h3> The arm is moved to 90 degress in both the joints.</h3>
  <img src="CaptureRos1.JPG" width="350" title="hover text">
  
  
  <h3> Initial position of arm 0 degress in both the joints.</h3>
  <img src="CaptureRos2.JPG" width="350" alt="accessibility text">
</p>
