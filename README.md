<div align="center">

# GOLD-SLAM

**Gaussian-splatting Omnidirectional LiDAR-Depth SLAM**

[![Paper](https://img.shields.io/badge/Paper-B31B1B?style=for-the-badge)](https://arxiv.org/abs/2611.32335)
[![Project Page](https://img.shields.io/badge/Project%20Page-B2582C?style=for-the-badge)](https://insailab.org/GOLD-SLAM/)

</div>

GOLD-SLAM combines LiDAR, IMU, and panoramic images for odometry and 3D Gaussian mapping.
The frontend uses visual constraints in the LiDAR blind zone, and the mapper uses measured LiDAR depth to guide panoramic reconstruction.
Download WHOLE recordings and sensor calibration from [Hugging Face](https://huggingface.co/datasets/InSAI-Lab/WHOLE).

## Video

https://github.com/user-attachments/assets/066ef3c1-db08-4e02-b15a-578a183a9527

## Reconstruction demos

<p align="center"><strong>Oxford Spires · ChristChurch03</strong><br><img src="docs/assets/showcase/christchurch03.webp" width="640" alt="GOLD-SLAM reconstruction of Oxford Spires ChristChurch03"></p>
<p align="center"><strong>WHOLE · night_03</strong><br><img src="docs/assets/showcase/night_03.webp" width="640" alt="GOLD-SLAM reconstruction of WHOLE night_03"></p>
<p align="center"><strong>WHOLE · motion_blur_03</strong><br><img src="docs/assets/showcase/motion_blur_03.webp" width="640" alt="GOLD-SLAM reconstruction of WHOLE motion_blur_03"></p>
<p align="center"><strong>WHOLE · garage_02</strong><br><img src="docs/assets/showcase/garage_02.webp" width="640" alt="GOLD-SLAM reconstruction of WHOLE garage_02"></p>

<details>
<summary><strong>WHOLE · indoor_02</strong></summary>

<p align="center"><img src="docs/assets/showcase/indoor_02.webp" width="640" alt="GOLD-SLAM reconstruction of WHOLE indoor_02"></p>

</details>

<details>
<summary><strong>HILTI-Oxford · Exp21</strong></summary>

<p align="center"><img src="docs/assets/showcase/exp21.webp" width="640" alt="GOLD-SLAM reconstruction of HILTI-Oxford Exp21"></p>

</details>

## System overview

![Panoramic LiDAR–inertial–visual odometry and depth-aware Gaussian mapping](docs/assets/system_overview.png)

## Acknowledgement

We thank the authors and contributors of [FAST-LIVO2](https://github.com/hku-mars/FAST-LIVO2), [Gaussian-LIC2](https://github.com/APRIL-ZJU/Gaussian-LIC), [DAP](https://github.com/Insta360-Research-Team/DAP), and [ODGS-SLAM](https://github.com/odgs-slam/odgs-slam) for sharing their work.

## Citation

```bibtex
@article{zhang2026goldslam,
  title   = {{GOLD-SLAM}: Gaussian-splatting Omnidirectional {LiDAR}-Depth {SLAM}},
  author  = {Weicong Zhang and Yuan Huang and Yu Zheng and Lin Chenxiao and
             Yingying Li and Lilong Fan and Liangdong Zhuang and Yufan Chen and
             Ruiping Liu and Junwei Zheng and Jiaming Zhang},
  journal = {arXiv preprint arXiv:2611.32335},
  year    = {2026},
  doi     = {10.48550/arXiv.2611.32335}
}
```
