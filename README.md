# Drowsiness_Detection

### Working ###

For the drowsiness detection of vehicle drivers, the algorithm fixes facial landmarks on the detected face and subsequently calculates the proportions of the eye as you can see in this image. It calculates the Euclidean distance between different co-ordinates of eyes and we have noted down the normal **Eye Aspect ratio**. Depending on calculated values, the system detects a state based on selected adaptive threshold values.<br>
whenever eyes are closed it will show the warning message and whenever eyes aspect ratio consecutive frames will cross the threshold a warning sound will be played.<br> <br>

![Alt text](https://www.mdpi.com/jimaging/jimaging-04-00120/article_deploy/html/images/jimaging-04-00120-g002.png?raw=true "Title")
### Requirements ###    
Opencv and face_recognition</br>

### Quick Start ### 
Download the zip file and execute drowsiness.py in the Python interpreter.
