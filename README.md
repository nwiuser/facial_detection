**Image and Video Detection using Python**

*Introduction*

This project demonstrates how to perform object detection on both images and videos using Python. Object detection is a computer vision technique that allows us to identify and locate objects within an image or video. This README will guide you through setting up the project and running the detection code.

*Prerequisites*

Make sure you have the following installed:

Python 3.x
OpenCV (cv2) library
Numpy library

The repository contains 2 models of facial detection:
`facial_img.py` : After the importing, teh script loads the pre-trained cascade classifier and the image. It detect the face in the grayscale image, and then it draws rectangles around the faces and eyes and then displays the resulting image.
`facial_video.py` : After importing the libraries, it initialized for face detection using the pre-trained XML file 'haarcascade_frontalface_default.xml'.The script initializes a video capture object (camera) to read frames from the specified video file. In the loop, it converts each frame to greyscale to detect faces. It draws rectangles around detected faces, displays teh resulting video, you exit with "q" key.

