# YOLOv8-and-DeepSORT-with-TensorRT-
## This project uses YOLOv8 under AGPL 3.0 License (for open source and academic projects) ##

### Project Overview ###
This project integrates object detection (YOLOv8) and object tracking (DeepSORT) with TensorRT and deploys converted models into NVIDIA Jetson Orin Nano. 

### Prerequisite ###

#### Platform ####
1. Device: NVIDIA Jetson Orin Nano Development Kit (8GB) <br />
(https://developer.nvidia.com/embedded/learn/get-started-jetson-orin-nano-devkit)
2. Machine: aarch64  <br />
3. System: Linux  <br />
4. Distribution: Ubuntu 20.04 focal  <br />
5. Release: 5.10.104-tegra  <br />
6. Python: 3.8.10  <br />

#### Libraries ####
1. Jetpack: 5.1.1  <br />
2. CUDA: 11.4.315 (pre-installed by Jetpack) <br />
3. cuDNN: 8.6.0.166 (pre-installed by Jetpack)  <br />
4. TensorRT: 8.5.2.2 (pre-installed by Jetpack) <br />
5. Torch: torch-2.0.0+nv23.05-cp38-cp38-linux_aarch64  <br />
6. Torchvision: 0.15.2 <br />


### Convert YOLOv8 from Pytorch model to TensorRT model ###

### Convert DeepSORT's ReID from Pytorch model to TensorRT model ###
