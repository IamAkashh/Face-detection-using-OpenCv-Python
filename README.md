OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications..
Face detection using Haar cascades is a machine learning based approach built using OpenCV where a cascade function is trained with a set of input data. OpenCV already contains many pre-defined classifiers for face, eyes, objects etc.. 

1.You need to download the trained classifier XML file (haarcascade_frontalface_default.xml) and export in your project folder.

2.The detection works only on grayscale images or frames. So convert the color image or frame to grayscale.

3.detectMultiScale function is used to detect the faces. It takes 3 arguments — the input image, scaleFactor and minNeighbours.  

4.Videos are made up of frames.So we perform the face detection for each frame in a video...

5.We use cap.read() to read the video and change it to grayscale and the we detect it using detectmultiscale function.
