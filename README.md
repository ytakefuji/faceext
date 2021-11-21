# faceext
This is under review.

This is a faceext Python software for hiding all of your clothes and 
background except your face.
faceext.py is based on two state-of-the-art libraries including 
mediapipe library for segmenting a face from the original image and 
opencv library for superimposing faces and monotonous backgrounds 
(black, white, or gray). 

faceext has been downloaded by 1998 users worldwide.

OBS studio can play a virtual camera so that the crafted image of extracted face
with superimposed monotonous background can be fed to remote meeting applications.
Remote meeting applicaions including Zoom, WebEx, and Google meet
were successfully tested.

Python3.7 or Python3.8 is recommended.

# How to install faceext

You need to install OBS studio: 
https://obsproject.com/download

You also need to install mediapipe and opencv:

$ pip install mediapipe

$ pip install opencv-python

Finally install faceext

$ pip install faceext

# How to run faceext
Run faceext.

$ faceext

Your face with gray color background will be popped on the screen.

There are three background colors: black "-B", gray "-G", and white color "-W".
The default background color is gray.

$ faceext -G

You can add a message or name on the crafted image.

$ faceext -B yoshi

or

$ faceext -W yoshiyasu takefuji

Run OBS studio and select the popped image as source.

Then press the "start virtual camera" button in OBS studio.

Run any remote meeting application and select OBS virtual camera in video source selection.

That is all.



