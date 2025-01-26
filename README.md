# color-face-object-identifier
This is my fourth personal project. I made a color, face, and object detection system using Python and OpenCV.
It uses your camera for real-time color detection
It also uses your camera and a face recognition model to detect faces.
This can be used for color-blind people and can help them identify colors.

**Features**
* Gets video frames from your camera
* Converts the frames into an HSV
* Shows the predefined colors (blue, green, and red) with boxes around the color
* Uses the haar cascade to detect faces

**Libraries / Models**
* Opencv for camera use and color detection
* Numpy for color ranges
* Haar Cascade Classifier for face detection
* MobileNet-SDD model for object detection

**Currently Working On**
* Improving the color detection system by separating the boxes if they are not touching/overlapping
* Making the object detection system

**Future Plans**
* I plan on making this into an object classifier gradually with OpenCV's library
* I plan on using AI to automatically detect what object it is and say what color and object it is
* When the color is detected, I want to add a feature where it displays the name of the color and says it with text-to-speech
* I plan on adding a feature that uses face detection by detecting emotions based on facial expressions
* I plan on adding a feature to toggle between everything so you could only see the face detection or the color detectin by itself if the user wants to
