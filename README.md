# Drowsiness_Detection
<b>Working:</b>
For the drowsiness detection of vehicle-drivers,algorithm fixes facial landmark on the detected face and subsequently calculates the proportions of eye as you can see on this image. It calculates the euclidean distance between different co-ordinates of eyes and we have noted down the normal <b>Eye Aspect ratio</b>. Depending on calculated values,the system detects a state based on selected adaptive threshold values.<br>
whenever eyes are closed it will show the warnning messase and whenever eyes aspect ratio consecutive frames will cross the threshold a warning sound will be played.<br>
![Alt text](https://www.mdpi.com/jimaging/jimaging-04-00120/article_deploy/html/images/jimaging-04-00120-g002.png?raw=true "Title")
<b>Requirements:</b>    Library such as Opencv and face_recognition</br>
<b>QuickStart: </b>Download the zip file and execute dwowsiness.py in python interpreter.
