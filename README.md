This is a simple program that detects faces in videos.

It uses Python and openCV. 
OpenCV is a library that contains pretrained models that can be used for face detection.

The models used are called: Haar cascade classifiers for face and smile detection.

So, after the OpenCV library has been called and the models have been loaded,
we then gain access to our camera in which we'd be using for video capturing.
We then use the models to detect faces and smiles in the video capture and then
draw rectangles on the face and smiles in real time.

The video is worked on frame by frame, so this is how it is possible.
