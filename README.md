# Object-trajectory-tracking-OpenCV

This app tracks the trajectory of an object(A blue object as of now) in the frame. 

Input can be given in the form of a video file or directly through the attached webcam.

````
python object_trajectory_tracking.py --video <video-file-name> --buffer <value>
````

Example:

````
python object_trajectory_tracking.py --video videofile.mp4 --buffer 30
````

Attributes:

--video(optional): The input video file. If not given, then webcam will be used.

--buffer(optional): The maximum size of the deque (which maintains the length of the trajectory of the object we are tracking)
