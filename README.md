Real-Time Webcam Facial Feature Detection Project

This project implements real-time face, eye, and mouth detection in a webcam feed using the Viola-Jones object detection algorithm.

The program is written in Python using OpenCV, which is an open source computer vision library.  A different cascade is used for each region of interest:  faces, eyes, and mouths.  The default frontal face cascade, profile face cascade, and the smile cascade (used here with adjusted scale factor and minNeighbors) are all available through OpenCV.

Reference:  P. Viola and M. Jones, “Rapid object detection using a boosted cascade of simple features,” Proceedings of the 2001 IEEE Computer Society Conference on Computer Vision and Pattern Recognition. CVPR 2001, Kauai, HI, USA, 2001, pp. I-I, doi: 10.1109/CVPR.2001.990517. 
