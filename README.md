# Random Epipolar Constraint Loss Functions for Supervised Optical Flow Estimation

This repository contains the source code for the following paper.  
Zhengyuan Fan, Zemin Cai, "Random Epipolar Constraint Loss Functions for Supervised Optical Flow Estimation," Pattern Recognition, 148:110141, 2024.  
https://doi.org/10.1016/j.patcog.2023.110141

## Requirements
The code has been tested on PyTorch 1.11.0 and Cuda 10.2.  


## Training
After you have the 'train.py' code for the project, run the file for training. However, before doing that, make sure that the training dataset is prepared.  
Click to enter RECLoss-GMA and run <br>  
./train.sh

## Evaluation
You can use the 'evalu.py' code in the project to evaluate a pre-trained model. The pre-trained weights can be found in the 'models' folder.

## Acknowledgements
Thanks to [RAFT](https://github.com/princeton-vl/RAFT/tree/master), [GMA](https://github.com/zacjiang/GMA), [GMFlow](https://github.com/haofeixu/gmflow) for providing awesome repos! These have been very helpful for our project.  
If you use this project, please cite the following paper. Also, feel free to provide feedback on our work.  

@article{FAN_RECLoss,  
title = {Random epipolar constraint loss functions for supervised optical flow estimation},  
journal = {Pattern Recognition},  
volume = {148},  
pages = {110141},  
year = {2024},   
doi = {https://doi.org/10.1016/j.patcog.2023.110141},  
}
