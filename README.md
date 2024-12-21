# PPE Safety Kit Object Detection using YOLO


## Overview
This project focuses on detecting Personal Protective Equipment (PPE) using the powerful YOLO (You Only Look Once) object detection algorithm. The model is capable of identifying various safety-related equipment and situations, including:
Hardhat
Mask
NO-Hardhat
NO-Mask
NO-Safety Vest
Person
Safety Cone
Safety Vest
Machinery
Vehicle
The primary goal of this project is to enhance workplace safety by ensuring that individuals adhere to safety protocols in hazardous environments. This tool is ideal for organizations and individuals looking to monitor and enforce safety standards for employees, contractors, or visitors in industrial, construction, or other high-risk areas. By leveraging cutting-edge object detection techniques, this project empowers users to maintain a safer working environment efficiently and effectively.


## Dataset
We used the PPE detection dataset available on Roboflow for training our model. The dataset contains images of people wearing PPE equipment in different environments.Dataset is annotated and have classes = `['Hardhat', 'Mask', 'NO-Hardhat', 'NO-Mask', 'NO-Safety Vest', 'Person', 'Safety Cone','Safety Vest', 'machinery','vehicle']` . Training set contains 2.6k images , validation set contains 114 images and Testing set contains 82 images. Input dimensions of single image is 640x640. 

## Tech-Stack  : 

- OpenCV 
- Ultralytics 
- torch 
- tochvision 
- Python 3.10
- flask


## Installation : 

- clone the repository : `$ git clone https://github.com/Vinayakmane47/PPE_detection_YOLO.git`
- create a conda environment : `$ conda create -n myyolo python=3.10 -y`
- Intall requirements : `$ pip install -r requirements.txt`
- Run main.py : `python app.py`
- Upload Image/Video to detect object or Start Live videocam 


## Results : 

![1](https://user-images.githubusercontent.com/103372852/233774695-ad3b800b-5d8e-4583-a395-e70ac86f2dda.PNG)

![3](https://user-images.githubusercontent.com/103372852/233774758-180186a2-8267-495b-8c04-0d43778299d2.PNG)




