# Augmented Statups YOLOv7 Pose-Estimation Tutorial

## 1.	Clone the repo to your working directory using Terminal
``` git clone  https://github.com/augmentedstartups/pose-estimation-yolov7.git ```

Or 

Download YOLOv7 Pose Files from Course 

2.	Create a new Conda Environment

``` conda env create -f environment.yml ```

Activate new Conda Environment  
``` conda activate yolov7pose ```


## 3.	Navigate to the cloned pose-estimation folder 
``` cd pose-estimation ```


## 4. From the Terminal run:

``` python run_pose.py  –-source 0 ```

To run inference on video:

``` python run_pose.py  –-source [path to video]```

To run on GPU:

``` python run_pose.py  –-source 0  –-device 0 ```
