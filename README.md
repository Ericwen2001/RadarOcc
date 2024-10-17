<div align="center">   

# [NeruIPS 2024]  RadarOcc: Robust 3D Occupancy Prediction with 4D Imaging Radar 
official implementation of RadarOcc: Robust 3D Occupancy Prediction with 4D Imaging Radar
We will clean our code and provide instructions for code in 4 weeks
</div>

# Abstract 

3D occupancy-based perception pipeline has significantly advanced autonomous driving by capturing detailed scene descriptions and demonstrating strong generalizability across various object categories and shapes. Current methods predominantly rely on LiDAR or camera inputs for 3D occupancy prediction. These methods are susceptible to adverse weather conditions, limiting the all-weather deployment of self-driving cars. To improve perception robustness, we leverage the recent advances in automotive radars and introduce a novel approach that utilizes 4D imaging radar sensors for 3D occupancy prediction. Our method, RadarOcc, circumvents the limitations of sparse radar point clouds by directly processing the 4D radar tensor, thus preserving essential scene details. RadarOcc innovatively addresses the challenges associated with the voluminous and noisy 4D radar data by employing Doppler bins descriptors, sidelobe-aware spatial sparsification, and range-wise self-attention mechanisms. To minimize the interpolation errors associated with direct coordinate transformations, we also devise a spherical-based feature encoding followed by spherical-to-Cartesian feature aggregation. We benchmark various baseline methods based on distinct modalities on the public K-Radar dataset. The results demonstrate RadarOcc's state-of-the-art performance in radar-based 3D occupancy prediction and promising results even when compared with LiDAR- or camera-based methods. Additionally, we present qualitative evidence of the superior performance of 4D radar in adverse weather conditions and explore the impact of key pipeline components through ablation studies.

[arXiv](https://arxiv.org/abs/2405.14014)) 



# News
- **[2024/10/17]** unclean code uploaded



# Getting Started
Please follow installation instruction from OpenOccupancy

- [Installation](docs/install.md) 

- [Prepare Dataset](docs/prepare_data.md)

- [Training, Evaluation, Visualization](docs/trainval.md)


# Acknowledgement

Many thanks to these excellent projects:
- [SurroundOcc](https://github.com/weiyithu/SurroundOcc)
- [OpenOccupancy](https://github.com/JeffWang987/OpenOccupancy)
