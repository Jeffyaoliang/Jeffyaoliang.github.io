---
# layout: archive # too wide
title: "Yaoliang Bian's Research Page"
permalink: /research/
author_profile: true
---

<!-- 放关于研究的详细内容 -->
<!--{% include toc %} -->
---

# Research Interests 

1. Wireless Communication & Mobile Computing: 
   - Bluetooth Backscatter
   - On-device AI
  
2. Digital Circuit Design: 
   - AI accelerator 

3. Embodied Intelligence:
   - 3D scene understanding
   - Robotics Simulation

---


# Research & Project Experience

## 1. Harnessing Multi-Frequency Carriers for Commodity Bluetooth Backscatter 

*Undergraduate Research Program at USTC* 

Supervisor: [Prof. Wei Gong](https://ubiot.ustc.edu.cn/weigong "Prof. Mengping ZHANG's homepage"){:target="_blank"} 

09/2024 ~ Present, USTC  

Existing backscatter technologies have limited compatibility with commercial wireless systems (such as WiFi and Bluetooth), particularly when dealing with multi-frequency carriers, where issues such as low utilization, uncertain latency, and connectivity limitations arise. DanBlue addressed these issues by introducing edge agents and a broadband channel hopping mechanism.

However, currently, DanBlue only supports a single carrier source. We are trying to explore how to multiplex multiple carrier sources, especially when these carriers have different hopping sequences. Moreover, the distance from the carrier to the tag is related to the tag's sensitivity. We would like to increase the downlink distance by improving the tag's sensitivity or using low-noise amplifiers. To enable the tag to utilize ambient BLE signals, DanBlue introduces additional edge devices and a wide clock, which increases costs. We are working on reducing it by integrating it into existing devices. Last but not least, the current system design is primarily intended for backscatter beacons. In the future, application protocols based on wide data channels, such as BLE pairing, need to be developed to further enhance the system's functionality and security.

## 2. A Survey on Custom Hardware for Deep Reinforcement Learning 

Supervisor: [Prof. Ameer Abdelhadi](https://www.ece.mcmaster.ca/~ameer/ "Prof. Ameer Abdelhadi's homepage"){:target="_blank"} 

07/2024 ~ 09/2024, McMaster University (onsite) 

This survey explores the development of domain-specific architectures for reinforcement learning (RL), highlighting advancements and challenges in implementing RL on specialized hardware. As RL algorithms grow more complex and computationally intensive, custom hardware solutions offer promising pathways to enhance performance, energy efficiency, and scalability. We review different architectures designed to accelerate RL algorithms as well as key contributions for various fields such as IoT applications, hardware prefetching and processors. Previous work primarily focused on either FPGA or GPU implementations, lacking extensive performance comparisons across various RL algorithms and configurations especially the modern ones. They also lack detailed discussions on integrating advanced neural network layers like CNNs and RNNs in FPGA designs. Our survey addresses these gaps by providing a comprehensive comparison of FPGA
and GPU implementations, emphasizing fine-grained parallelism, on-chip memory usage, and integration with software-based environments. Furthermore, we explore near-memory computing and state-of-the-art DRL algorithms on custom hardware. We conclude with future research directions, including integrating advanced neural network layers in FPGA designs and exploring near-

Defense PPT (in Chinese) preview: [here](../files/undergraduate-research-program/Custom Hardware for Deep Reinforcement Learning.pptx){:target="_blank"}. 

## 3. Robogame 

*A Robot Competition at USTC* 

Supervisor: [Prof. Huichun Ye](https://pmpi.ustc.edu.cn/2020/0425/c19781a419361/ "Prof. Huichun Ye's homepage"){:target="_blank"} 

05/2023 ~ 10/2023, USTC 

Defense: 06/07/2023 

I built a robot with my teammates in USTC’s 2023 Robogame. I was responsible for the electrical wiring of the robot chassis and the coding of motion control. Our Robot can independently identify, grab ores of different colors and transport them to the designated area in time.
We won the 2nd prize among 39 teams. (Project code) 

<iframe src="https://drive.google.com/file/d/1X6Bf7go0nT6MjuTKoUvBnHb5hPmhsGH7/preview" 
        width="640" height="480" allow="autoplay; fullscreen" allowfullscreen>
</iframe>

<iframe src="https://drive.google.com/file/d/1F79y73cuPLEYJn3AgSGt17I_9ofuiMYJ/preview" 
        width="640" height="480" allow="autoplay; fullscreen" allowfullscreen">
</iframe>

arXiv preprint (submitted): [here](https://arxiv.org/abs/2311.09119 "arXiv link"){:target="_blank"} 


---


# Numerical PDE Programming (choronological order) 

| PDE | method | domain | mesh | language |
| --- | --- | --- | --- | --- |
| Poisson (Dirichlet) | 2-order FD | 2D rectangle | uniform Cartesian | Matlab |
| compressible Euler | 5-order FD-WENO | 1D interval | uniform Cartesian | Fortran |
| compressible Navier--Stokes | 5-order FD-WENO | 2D rectangle | uniform Cartesian | Fortran + OpenMP |
| Hamilton-Jacobi | 5-order FD-WENO | 2D rectangle | uniform Cartesian | Fortran + OpenMP |
| compressible RMHD | 5-order FD-HJ | 2D rectangle | uniform Cartesian | Fortran + OpenMP |
| compressible RMHD | 4-order FD-HJ + Fourier | 3D toroidal with rectangular section | uniform Cylindrical | Fortran + OpenMP |
| compressible RMHD | 3-order FD-HJ + Fourier | 3D toroidal with circular section | uniform Cartesian (embedded) | Fortran + OpenMP + MPI |
| compressible MHD | arbitrary-degree DG (locally div-free) | 2D rectangle | arbitrary Cartesian | Fortran + OpenMP + MPI |
| Poisson | arbitrary-degree FEM | 1D interval | arbitrary Cartesian | Matlab |
| Poisson | quadratic FEM | 2D polygon | triangular | Matlab |
| Poisson | LDG | 1D interval | arbitrary Cartesian | Matlab |
| Poisson | HDG | 1D interval | arbitrary Cartesian | Matlab |
| Poisson | arbitrary-degree MD-LDG (good results up to k=9) | 2D polygon | triangular | Matlab |
| p-Laplace | arbitrary-degree LDG | 1D interval | arbitrary Cartesian | Matlab |
| p-Laplace | arbitrary-degree LDG | 2D polygon | triangular | Matlab |
| mixed FEM | arbitrary-degree FEM | 2D polygon | triangular | MFEM |
