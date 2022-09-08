# Real Time Object Detection and Counting

This is a real-time object detecting and counting application which was developed as a University project. This model has the ability to detect and get the count of each object detected in realtime and as I utilize the COCO dataset and COCO.weights it can only detect the classes that are defined in the COCO names.

Reference - https://github.com/pjreddie/darknet/blob/master/data/coco.names

First I developed the application to detect the objects on a provided image and later I extended it to get the real-time reading from the Webcam. But as I use the CPU rendering it has low frame rate therefore it's not that accurate.



**Here's a video of me testing the application**

https://drive.google.com/file/d/1CEYGGP7TCyjIzqryQZzR1m10krCDra3-/view?usp=sharing

## Tech

Python, OpenCV and numpy
