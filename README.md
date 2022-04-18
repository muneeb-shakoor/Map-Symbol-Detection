# Map-Symbol-Detection
Detecting land symbols from landscape plains to automate the lengthy manual detection process. For this object detection problem yolo model had already played remarkable role in different areas. I used pre-trained weights of yolov5 on my custom dataset.

## Dataset 
No public dataset is availble so I used real world images. Manual labelling is done on each image using LabelImg Tool. [download](https://tzutalin.github.io/labelImg/)
with Yolo txt labels 

## Pre-processing Dataset
Whole dataset is resize into 1280x1280 and split into training and validation in 80:20 ratio.

## original Image
![image](original_test.png)

## Results 
![image](results.jpg)


