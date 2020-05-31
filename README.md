# vision_based_grasp_robot
This a vision based robot application project for grasp, push, bin-picking and any other applications needed.

Firstly, we use a robot of UR5e for robot application development with a realsence camera D415.
Next time, we will adjust application for a dual arm robot and more camera.

Now system has 3 parts: 2D object detection & segmatation, grasp pose estimator based point cloud, robot move application.

1. 2D object detection & segmatation 

This part is based on Mask-RCNN 

cuda 9.0
tensorflow==1.8

2. grasp pose estimator based point cloud

There will support multiple grasp algorithms.

3. robot application(a simulation in vrep also will be here)

main.py 


To do list:
