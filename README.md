sixth-sense-capturing
=====================
Authored by Sagar Patel and Gunjan Gupta.
This is version 1.0.0.

This project aims to design of a fluid interface, which can be realized for interaction between physical world and digital world. Imagine that you are using your hand gesture to capture a movement and the camera kept on your head is capturing the image by recognizing that gesture using image processing. As soon as, it captures the image, it uploades it on Google Drive. And all these things happen on the very small device of just 10" x10", Pandaboard. Pandaboard is used with Ubuntu 12.04 LTS. We have used C++ for algorithm. OpenCV is used to achieve efficient image processing in real time.

Gesture detection can be achieved by color strips. Two different color strips can be used to generate two points in 2D space. A rectangle can be formed using these two points. This rectangle is Region of Interest for cropping the image to get the boundry of desigred image.

As soon as camera captures the image, sound of opening and closing of shutter will be played using MPlayer. As the image is going to be uploaded on google drive, the camera rolling sound will be played. Hence, we can get the idea that whats going on in system and whether the image is captured correctly and uploaded.
