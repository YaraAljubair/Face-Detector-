# Face-Detector-
In this project I used python programming language and one of its packages opencv<ul>
<li> I had to install the opencv package first on Windows and import it in pycharm then I tested the camera and at first two windows opened one with normal colors the other was more gray</li>
<li>I continued my coding but when I typed  
$cv2.CasacadeClassifier(‘Cascade/haarcascade_frontalface_default.xml’) 
It led to an error </li>
    <li>  after some research I decided to change the code to
$ cv2.CasacadeClassifier(cv2.data.haarcascades+‘haarcascade_frontalface_default.xm’)
and it worked out great </li> 
</ul>   I attached a Video with the result 
