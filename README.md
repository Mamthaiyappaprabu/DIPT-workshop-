# DIPT-workshop-1:
## WORKING ON IMAGES :
#### NAME : MAMTHA I
#### REG NO : 212222230076
## INSTRUCTION  :
***1. The image should be a plant, Tree, flower or building.***

***2. The filename should be username.jpg.***

***3.The image should be Converted to gray scale and HSV***

***4. Display the H, S and V planes***
## PROGRAM :

```
import cv2
image=cv2.imread('flower.jpg',1)
image=cv2.resize(image,(400,250))
cv2.imshow('pic',image)
cv2.waitKey(0)

```
***The image should be Converted to gray scale :***
```
import cv2
image = cv2.imread('flower.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2GRAY)
cv2. imshow('gray_scale', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
```
***The image should be Converted to HSV :***
```
import cv2
image = cv2.imread('flower.jpg')
gray = cv2. cvtColor(image, cv2.COLOR_BGR2HSV)
cv2. imshow('my_img', gray)
cv2. waitKey(0)
cv2. destroyAllWindows()
```
***Display the H, S and V planes :***
```
import cv2
image=cv2.imread("flower.jpg",1)
image= cv2.resize(image,(400,250))
image=cv2.cvtColor(image,cv2.COLOR_RGB2HSV)
H,S,V=cv2.split(image)
cv2.imshow('Hue',H)
cv2.imshow('Saturation',S)
cv2.imshow('Value',V)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
## OUTPUT :
#### IMAGE :

![Screenshot 2024-02-27 082716](https://github.com/Mamthaiyappaprabu/DIPT-workshop-/assets/119393563/5c97d7c8-52e4-4b56-8170-563767f5f4db)

#### GRAY SCALE :
![Screenshot 2024-02-27 082825](https://github.com/Mamthaiyappaprabu/DIPT-workshop-/assets/119393563/f3794c8e-9c8c-4335-a5f3-bbba57413080)

#### HSV :

![Screenshot 2024-02-27 082905](https://github.com/Mamthaiyappaprabu/DIPT-workshop-/assets/119393563/49c112ac-3f78-43fa-aed5-b21fefa2383b)


#### HUE :
![Screenshot 2024-02-27 083341](https://github.com/Mamthaiyappaprabu/DIPT-workshop-/assets/119393563/897b4e72-57a9-4b5d-a620-45241dae9454)

#### VALUE :
![Screenshot 2024-02-27 083349](https://github.com/Mamthaiyappaprabu/DIPT-workshop-/assets/119393563/d079c45d-dc62-4882-80b6-5a7b5cfa9dc2)

#### SATURATION :
![Screenshot 2024-02-27 083432](https://github.com/Mamthaiyappaprabu/DIPT-workshop-/assets/119393563/8fada161-a296-4c4c-926b-caacc898dced)

## RESULT :
Therefore working on images has been successfully implemented.







