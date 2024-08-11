# README: Road Defect Dataset
This is a road defect dataset, including **2517** images and txt labels, divided into **4** classes: ['Longitudinal Crack', 'Pothole', 'Transver Crack', 'Alligator Crack' ]

Road defect dataset covered multiple provinces across China, including Hebei Province, Jilin Province, Henan Province and Shandong Province. The dataset contains six scenarios shown as Figure 1: 1) country roads; 2) campus roads; 3) urban feeder roads; 4) urban arterial roads; 5) sub-urban roads; and 6) urban expressways. Images were captured at different moments throughout the day to emulate a diverse range of lighting conditions. 

Road Defect Dataset is uploaded on the BaiduNetDisk: 

> URL: https://pan.baidu.com/s/18T_GxCvvHNFkPQOumGAzXw?pwd=sncx
> 
> CODE: sncx 

**Folder Directory**
```
├─images
│  ├─train
│  └─val
└─labels
    ├─train
    └─val
```
YOLOv5 training data configuration: .yaml
```
train: ../mycoco/images/train/
val: ../mycoco/images/val/

# number of classes
nc: 4

# class names
names: ['Longitudinal Crack', 'Pothole', 'Transver Crack', 'Alligator Crack' ]
```

Our Augmentation Dataset can be downloaded from BaiduNetDisk:
> URL: https://pan.baidu.com/s/1yPCWxpRDAsr_nWy6P268FA?pwd=8qnq

> CODE: 8qnq
