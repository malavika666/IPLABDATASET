# IPLABDATASET
import cv2<br>
img=cv2.imread('leaf1.jpg',0)<br>
cv2.imshow('image',img)<br>
cv2.waitKey(0)<br>
cv2.destroyAllWindows()<br>
![image](https://user-images.githubusercontent.com/97940144/173802513-b7e6b142-6d25-43d2-9823-15c4bdca95a9.png)



from PIL import Image
img=Image.open('plant1.jpg')
img=img.rotate(180)
img.show()
cv2.waitKey(0)
cv2.destroyAllWindows()
![image](https://user-images.githubusercontent.com/97940144/173803822-ef786ccc-38b4-4acb-9ba8-0ae3dd29cc49.png)
