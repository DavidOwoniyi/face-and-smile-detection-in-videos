This is a simple program that detects faces and smiles in videos.

It uses Python and OpenCV. 
OpenCV is a library that contains pretrained models that can be used for face and smile detection.

The models used here are called: Haar cascade classifiers for face and smile detection.

The first step is to import the OpenCV library and load the face and smile detection models.
We then gain access to our camera in which we'd be using for video capturing.
We then use the models to detect faces and smiles in the video capture and then
draw rectangles on the faces and smiles in real time.

The video is worked on frame by frame, so this is how face detection and smile detection is possible.
