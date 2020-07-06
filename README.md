# G1N_Project_DLSpring2020
This repository contains code and results for Course Project by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This project is only for learning purposes and is not intended to be used for clinical purposes.

## Note
This project uses MonoDepth as a base project. For original code and paper, please refer to original github website "https://github.com/mrharicot/monodepth#models".

## monodepth

### Abstract
The arrival of autonomous robots and self-driving cars have sprawled computer vision demanding novel and more rigid work in this field. Depth Estimation is one such application whereby we estimate the distance between various objects in an image or a video frame. Hence, we extract out spatial information. We can mine out this information by algorithms and related techniques but, we propose a deep network that solves the same problem. We pose the problem as an image reconstruction by taking left and right images from a calibrated binocular camera.The network works by taking both images and returning four more images all of varying scales, along with losses, called per pixel scene depth. The network then selects the finest scale and uses it to output a depth map at the original image’s resolution. During training, we take both left and right images however, only a single image is required at testing time. Hence, the network can be deployed on images taken by ordinary cameras. KITTI and Cityscapes datasets were used on this network.

## Dataset
This model requires rectified stereo pairs for training.
There are two main datasets available:
#### KITTI
#### Cityscapes

## System Diagram / Pipeline
![pipeline](/readme_images/pipeline.png)

## Results
           Pre-Trained Model             Our Model
![bresults](/readme_images/bresults.jpeg)

