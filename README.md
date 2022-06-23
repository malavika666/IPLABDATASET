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
<br>
*************************************************************************************************************************
8.Program
import cv2<br>
#read the image file<br>
img=cv2.imread('plant1.jpg')<br>
cv2.imshow("RGB",img)<br>
cv2.waitKey(0)<br>
#Gray scale<br>
img=cv2.imread('plant1.jpg',0)<br>
cv2.imshow("Gray",img)<br>
cv2.waitKey()<br>
#Binary image<br>
ret,bw_img=cv2.threshold(img,127,255,cv2.THRESH_BINARY)<br>
cv2.imshow("Binary",bw_img)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
<br>
![image](https://user-images.githubusercontent.com/97940144/174046292-80860a0d-b139-406f-9cd0-2566df35eb19.png)<br>
![image](https://user-images.githubusercontent.com/97940144/174046522-df55cdf1-06bd-43a2-9e82-82928198648d.png)<br>
![image](https://user-images.githubusercontent.com/97940144/174046710-e9080fa2-6d89-4bee-ac82-3d1b805c9957.png)<br>
<br>
**************************************************************************************************************************
9.Program<br>
import cv2<br>
img=cv2.imread('butterfly1.jpg')<br>
print('original image length width',img.shape)<br>
cv2.imshow('original image',img)<br>
cv2.waitKey(0)<br>
#to show the resized image<br>
imgresize=cv2.resize(img,(160,170))<br>
cv2.imshow('Resized image',imgresize)<br>
print('Resized image length width',imgresize.shape)<br>
cv2.waitKey()<br>
![image](https://user-images.githubusercontent.com/97940144/174047072-ab06cc37-4656-4e2a-8689-3eef0af3d04c.png)<br>
![image](https://user-images.githubusercontent.com/97940144/174047191-69fe5670-62ab-493a-916e-811a1170d4dd.png)
***************************************************************************************************************************
#Program
import cv2<br>
img=cv2.imread("D:\\flower1.jpg")<br><br>
gray=cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)<br>
hsv=cv2.cvtColor(img,cv2.COLOR_BGR2HSV)<br>
lab=cv2.cvtColor(img,cv2.COLOR_BGR2LAB)<br>
hls=cv2.cvtColor(img,cv2.COLOR_BGR2HLS)<br>
yuv=cv2.cvtColor(img,cv2.COLOR_BGR2YUV)<br>
cv2.imshow("GRAY IMAGE",gray)<br>
cv2.imshow("HSV IMAGE",hsv)<br>
cv2.imshow("LAB IMAGE",lab)<br>
cv2.imshow("HLS IMAGE",hls)<br>
cv2.imshow("YUV IMAGE",yuv)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>

![image](https://user-images.githubusercontent.com/97940144/175269476-d560cedd-8ed2-406f-943f-d52fc0a357c6.png)



