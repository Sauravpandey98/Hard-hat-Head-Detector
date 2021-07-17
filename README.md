# Hard-hat-Head-Detector
A hardhat and head detector using darknet(Yolo).

# Description
This model can detect hard-hat or head in any environment with a very high FPS rate.This model was implemented with the help of darknet repository of [AlexyAB](https://github.com/AlexeyAB). In spite a basic detection,two extra functionalities is also added to bounding box color.

## Functionality 1
Using this, the color of bounding box can change according to the confidence value.The color of bounding box changes from light to dark as the confidence increases from low to high.

## Functionality 2
Using this,the color of bounding box will change according to color of detected hardhat.It was implemented using image processing and machine learning algorithms.

Implementation of above mentioned functionalities is present in [find_color](https://github.com/Sauravpandey98/Hard-hat-and-Head-Detector/blob/e055bb84205a14c7db4b47192dc50c3221f7416f/darknet/darknet.py#L87) function of darkent,py

# Processed Video with hardhat/head detection

* [**Using 1st Functionality**](https://drive.google.com/file/d/1_YcGGgncHQuYGt_fQBo2yv2BurqJ1s53/view?usp=sharing)
* [**Using 2nd functionality**](https://drive.google.com/file/d/1VEh_onQwGfvAPuIF4yGIrZFrOTQSXz4O/view?usp=sharing)


