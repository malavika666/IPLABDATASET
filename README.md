# IPLABDATASET
1.program<br>
import cv2<br>
img=cv2.imread('leaf1.jpg',0)<br>
cv2.imshow('image',img)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
![image](https://user-images.githubusercontent.com/97940144/173802513-b7e6b142-6d25-43d2-9823-15c4bdca95a9.png)<br>
<br>
*********************************************************************************************************************

3.Program<br>
from PIL import Image<br>
img=Image.open('plant1.jpg')<br>
img=img.rotate(180)<br>
img.show()<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
![image](https://user-images.githubusercontent.com/97940144/173803822-ef786ccc-38b4-4acb-9ba8-0ae3dd29cc49.png)<br>
<br>
***********************************************************************************************************************
5.Program<br>
from PIL import Image<br>
img=Image.new("RGB",(300,400),(0,255,0))<br>
img.show()<br>
![image](https://user-images.githubusercontent.com/97940144/173804674-18ebd303-7da7-40c2-9c58-83e01b8d4601.png)

