### SLAM 3D-Map visualization
### in browser

 ny nnn112358

---

First, this URL Click.

---

This Page made by follow tools

・rtabmap_ros
・potree
・gitpage

---

Materials to prepare

・Kinect V1(or other RGB-D Camera)
・node-PC
・ROS

---

First, 

 kinetic:
 sudo apt-get install ros-kinetic-freenect-launch
 sudo apt-get install ros-kinetic-rtabmap-ros

----

Operation check of Kinect V1

 roslaunch freenect_launch freenect.launch
 rosrun image_view image_view image:=/camera/rgb/image_color
 rosrun image_view image_view image:=/camera/depth/image_raw
 
---

$ rtabmap



---



