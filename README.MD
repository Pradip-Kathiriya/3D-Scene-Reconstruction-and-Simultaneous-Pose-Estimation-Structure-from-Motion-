## Project Description

The purpose of this project is to reconstruct 3D scene and simultaneously obtain the camera poses of a monocular camera. This is also known as Structure from Motion(SfM) 

The following are the steps involved in the SfM:
- Feature Matching and Outlier rejection using RANSAC
- Estimating Fundamental Matrix
- Estimating Essential Matric from Fundamental Matrix and Intrinsic Camera Matrix
- Estimating Camera Pose from decomposition of Essential Matrix
- Check for Cheirality Condition using Trinagulation
- Perspective-n-Point
- Bundle adjustment

## Pseudo code

![summary](https://user-images.githubusercontent.com/90370308/221982778-86f56fcd-731e-4b9e-86e5-146214f86f5b.png)

## Results

### Feature Matching using SIFT and RANSAC

![feature matching](https://user-images.githubusercontent.com/90370308/222005261-3c35443a-a23e-4ad1-9f88-b6f92a126ba5.png)

### Triangulation check for Cheirality Condition

![all_poses](https://user-images.githubusercontent.com/90370308/222008248-e8bec6d5-b87c-45df-89b6-08b1d9ce333b.png)

### Non-Linear Triangulation

![linear_nonlinear](https://user-images.githubusercontent.com/90370308/222008621-e1d88b49-75f6-461e-a8af-4798b1cd9ce9.png)

### Linear Camera Pose Estimation

![PnP56](https://user-images.githubusercontent.com/90370308/222008862-53869898-0084-4b9d-b764-46be92277d4e.png)

### Bundle Adjustment and Sparse Scene Reconstruction

![BundleAdjustment56](https://user-images.githubusercontent.com/90370308/222008894-d65dfeae-db6d-40e4-a173-2f51f451417c.png)

## Requirement
Python 2.0 or above

## License

 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) Feb 2023 Pradip Kathiriya
