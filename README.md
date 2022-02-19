Face and Eye Detection using OpenCV, python and the Haarcascade Classifier through the device webcam.
Detects the face and the eyes and makes a box around them to locate and show the same.

The yellow box detecting the face and the blue detetcting eyes.

Requirements:
python: 3.x, openCV

we find the faces in the image with detectMultiScale. If faces are found, this function returns the positions of detected faces as Rect(x,y,w,h).

Press 'q' key to close the window displaying the video that is captured, showing the detected eyes and face.
