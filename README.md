# color-face-object-identifier
This is my fourth personal project. It's a color, face and object detection system that I made using Python and OpenCV.
It uses your camera for real-time color detection
It also uses your camera and a face recognition model to detect faces.
This can be used for color blind people and can help them identify colors.

**Features**
* Gets video frames from your camera
* Converts the frames into an HSV
* Shows the predefined colors (blue, green, and red) using a mask 
* Uses the haar cascade to detect faces

**Libraries / Models**
* Opencv for camera use and color detection
* Numpy for color ranges
* Haar Cascade Classifier for face detection

**Currently Working On**
* Finding an object classifier model
* Improving the color detection system by putting boxes around the detected colors the same way the box is around the face when detected
* Adding a way to close the color masks windows if the user just wants to see the face detection

**Future Plans**
* I plan on making this into an object classifier gradually with OpenCV's library
* I plan on using AI to automatically detect what object it is and say what color and object it is
* When the color is detected I want to add a feature where it displays the name of the color and says it with text to speech
* I plan on adding a feature that use face detection by detecting emotions based on facial expressions
