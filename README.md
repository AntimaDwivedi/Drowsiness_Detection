# Drowsiness Detection Algorithm

### Methodology of the model  ###

<b>•</b> For the drowsiness detection of vehicle drivers, the algorithm fixes facial landmarks on the detected face and subsequently calculates the proportions of the eye as you can see in this image.<br> <br>
<b>•</b> It calculates the **Euclidean distance** between different coordinates of eyes and we have noted down the normal **Eye Aspect ratio**.<br><br>
<b>•</b> Depending on calculated values, the system detects a state based on selected adaptive threshold values.<br><br>

![Screenshot 2024-03-27 152928](https://github.com/AntimaDwivedi/Drowsiness_Detection/assets/56269029/55780842-af4a-4571-a52d-a374a984ac53) &nbsp;
<br>

<b>•</b> Whenever the eyes are closed it will show the warning message and whenever eyes aspect ratio consecutive frames will cross the threshold a warning sound will be played.<br> <br>


### Requirements ###    
<b>•</b> Opencv and face_recognition</br>

### Quick Start ### 
<b>•</b> Download the zip file and execute drowsiness.py in the Python interpreter.
