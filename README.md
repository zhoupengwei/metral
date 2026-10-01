[//]: # "SPDX-FileCopyrightText: Copyright (c) 2026 Pengwei Zhou"
[//]: # "SPDX-License-Identifier: GPL-3.0-or-later"
[//]: #
[//]: # "Licensed under the GNU General Public License, Version 3 (the 'License');"
[//]: # "you may not use this file except in compliance with the License."
[//]: # "You may obtain a copy of the License at"
[//]: # "https://www.gnu.org/licenses/gpl-3.0.html"
[//]: #
[//]: # "Unless required by applicable law or agreed to in writing, software"
[//]: # "distributed under the License is distributed on an 'AS IS' BASIS,"
[//]: # "WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied."
[//]: # "See the GNU General Public License for more details."


# METRAL


![Version](https://img.shields.io/badge/Version-v0.1.0-blue)
[![License](https://img.shields.io/badge/License-GPL_3.0-green.svg)](https://www.gnu.org/licenses/gpl-3.0)
![Platform](https://img.shields.io/badge/Platform-linux--64_%7C_win--64_%7C_macos--arm64-gray)
[![CUDA](https://img.shields.io/badge/CUDA-v12.2+_%7c_v13.x-%2376B900?logo=nvidia)](https://developer.nvidia.com/cuda-toolkit-archive)
[![C++](https://img.shields.io/badge/C%2B%2B-C%2B%2B20-orange)](https://isocpp.org/)
[![Python](https://img.shields.io/badge/python-3.8--3.13-blue?logo=python)](https://www.python.org/)
[![CMake](https://img.shields.io/badge/CMake-v3.20%2B-%23008FBA?logo=cmake)](https://cmake.org/)


METRAL (Metric 3D Reconstruction Framework) is an efficient and robust framework for large-scale metric 3D reconstruction. It provides a complete pipeline for image-based reconstruction, integrating Structure-from-Motion (SfM), Multi-View Stereo (MVS), and 3D Gaussian Splatting (3DGS) with scalable geometric optimization and high-performance computing.


METRAL is designed for researchers and developers in computer vision, photogrammetry, remote sensing, and spatial computing, supporting large-scale scene reconstruction across Linux, Windows, and macOS platforms with C++ and Python interfaces.


<img src="docs/images/metral_pipeline.svg" width="700" alt="METRAL Pipeline">


## Features


### Structure-from-Motion (SfM)

- Large-scale image registration
- Robust feature matching and geometric verification
- View graph construction and optimization
- Camera pose estimation
- Multi-view triangulation
- Scalable incremental reconstruction


### Multi-View Stereo (MVS)

- Dense reconstruction from calibrated images
- Depth estimation
- Point cloud generation
- Large-scale scene reconstruction


### 3D Gaussian Splatting (3DGS)

- SfM initialization for Gaussian Splatting
- Accurate camera and structure estimation
- Large-scale scene preparation
- Neural rendering support


### Optimization

- Large-scale Bundle Adjustment
- Sparse nonlinear optimization
- Camera calibration and refinement
- Robust geometric optimization


### GPU Acceleration

- CUDA accelerated reconstruction modules
- Parallel computation pipelines
- Efficient memory management
- Large-scale GPU computation


## Supported Platforms

- Linux
- Windows
- macOS (Apple Silicon / Intel)


## Development Environment

- C++20
- CUDA 12.1 - 12.8
- Python 3.8 - 3.13
- CMake >= 3.20


## Documentation

Documentation is under development.


## Installation


Clone the repository:

```bash
git clone https://github.com/zhoupengwei/metral.git

cd metral
