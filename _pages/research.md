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

Defense: 10/23/2024

This survey explores the development of domain-specific architectures for reinforcement learning (RL), highlighting advancements and challenges in implementing RL on specialized hardware. As RL algorithms grow more complex and computationally intensive, custom hardware solutions offer promising pathways to enhance performance, energy efficiency, and scalability. We review different architectures designed to accelerate RL algorithms as well as key contributions for various fields such as IoT applications, hardware prefetching and processors. Previous work primarily focused on either FPGA or GPU implementations, lacking extensive performance comparisons across various RL algorithms and configurations especially the modern ones. They also lack detailed discussions on integrating advanced neural network layers like CNNs and RNNs in FPGA designs. Our survey addresses these gaps by providing a comprehensive comparison of FPGA and GPU implementations, emphasizing fine-grained parallelism, on-chip memory usage, and integration with software-based environments. Furthermore, we explore near-memory computing and state-of-the-art DRL algorithms on custom hardware. We conclude with future research directions, including integrating advanced neural network layers in FPGA designs and exploring near-memory computing to further enhance
RL capabilities on custom hardware.

Defense PPT (in Chinese) preview: [here](../files/undergraduate-research-program/Custom Hardware for Deep Reinforcement Learning.pptx){:target="_blank"}. 

## 3. Robogame 

*A Robot Competition at USTC* 

Supervisor: [Prof. Huichun Ye](https://pmpi.ustc.edu.cn/2020/0425/c19781a419361/ "Prof. Huichun Ye's homepage"){:target="_blank"} 

05/2023 ~ 10/2023, USTC 

Final: 10/22/2023 

I built a robot with my teammates in USTC’s 2023 Robogame. I was responsible for the operation and maintenance of the core power supply module and the air pump system, as well as assisting with parameter tuning. Our Robot can independently identify, grab ores of different colors and transport them to the designated area in time.
We won the 2nd prize among 39 teams. (Project code: [here](https://gitee.com/langlang02/miner-craft-robogame2023 "gitee link"){:target="_blank"} ) 

<div style="display: flex; justify-content: center; gap: 1em;">
    <iframe src="https://drive.google.com/file/d/1X6Bf7go0nT6MjuTKoUvBnHb5hPmhsGH7/preview" 
            width="640" height="480" allow="autoplay; fullscreen" allowfullscreen>
    </iframe>
    
    <iframe src="https://drive.google.com/file/d/1F79y73cuPLEYJn3AgSGt17I_9ofuiMYJ/preview" 
            width="640" height="480" allow="autoplay; fullscreen" allowfullscreen>
    </iframe>
</div>

<figure>
    <img src="../files/picture/2023.10.10. Innovative Center(Zhenglang Weng, Jiazhuo Liu, Yaoliang Bian, Taowei Liu, Yaxin Gong with our robot).jpg" 
         alt="My great teammates and me(from left to right: Zhenglang Weng, Jiazhuo Liu, Yaoliang Bian, Taowei Liu, Yaxin Gong with our robot)">
    <figcaption>
        Miner Craft Team: my great teammates and me (from left to right: Zhenglang Weng, Jiazhuo Liu, Yaoliang Bian, Taowei Liu, Yaxin Gong with our robot) <br /> 2023.10.10 @ Innovative Center
    </figcaption>
</figure>

## 4. 18th National College Students' Smart Car Competition 

Supervisor: [Prof. Huichun Ye](https://pmpi.ustc.edu.cn/2020/0425/c19781a419361/ "Prof. Huichun Ye's homepage"){:target="_blank"} 

11/2022 ~ 07/2023, USTC 

Final: 07/21/2023 

I participated in the power relay group of Anhui division with my passionate teammates, Weixing Chen, Xinyuan Zhang, Boxuan Niu. I was responsible for the PCB design of the core boards for the rescue vehicle and the rescued vehicle of the electrical energy relay team. Weixing Chen and I also provided help to the Duck Yummy team of Shanghai Jiao Tong University in the intelligent vision group of East China Division.

<center> 
    <img style="
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12), 0 2px 10px 0 rgba(34,36,38,.08); 
        height: 300px; 
        object-fit: cover;" 
        src="../files/picture/Xia_Tou_Ke_Nan_Team's_introduction_&_car.jpg" 
        width="46.5%">
    
    <img style="
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12), 0 2px 10px 0 rgba(34,36,38,.08); 
        height: 300px; 
        object-fit: cover;" 
        src="../files/picture/Xia_Tou_Ke_Nan_Team's_car.jpg" 
        width="50%">
    
    <br />
    <div style="
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        Xia Tou Ke Nan Team's introduction & car
    </div>
    <p> </p>
</center>

<center> 
    <img style="
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12), 0 2px 10px 0 rgba(34,36,38,.08); 
        height: 300px; 
        object-fit: cover;" 
        src="../files/picture/Duck_Yummy_Team's_car.jpg" 
        width="46.5%">
    
    <img style="
        border-radius: 0.3125em;
        box-shadow: 0 2px 4px 0 rgba(34,36,38,.12), 0 2px 10px 0 rgba(34,36,38,.08); 
        height: 300px; 
        object-fit: cover;" 
        src="../files/picture/East Region Intelligent Vision Group Competition Site at Nanjing University of Information Science & Technology.jpg" 
        width="50%">
    
    <br />
    <div style="
        color: orange;
        border-bottom: 1px solid #d9d9d9;
        display: inline-block;
        color: #999;
        padding: 2px;">
        left: Duck Yummy Team's car; right: East Region Intelligent Vision Group Competition Site at Nanjing University of Information Science & Technology
    </div>
    <p> </p>
</center>

## 5. Examining the Influences of Skyrmion Movement 

Supervisor: [Prof. Peng Li](https://faculty.ustc.edu.cn/lipeng18/en "Prof. Peng Li's homepage"){:target="_blank"} 

09/2022 ~ 06/2023, USTC 

Defense: 06/08/2023

This experiment aims to understand the physical properties and structural characteristics of Skyrmion through learning, and to study the influence of different magnetocrystalline anisotropy constants (PMA) on the magnitude of Skyrmion generated by current, as well as the influence of two-dimensional PMA gradient fields on the driving effect of Skyrmion, using an object-oriented micromagnetic simulation framework software. Finally, the conclusions of the integration leakage ignition model were obtained through program simulation, image analysis, and other methods. At the same time, the simulation process was summarized, reflected on, and improved.

Summary essay preview: [here](https://drive.google.com/file/d/1mF824PXULRFDKP2KEecxfiXSzwnpKZhE/preview){:target="_blank"}. 
Demo preview: [here](https://drive.google.com/file/d/1bc4_YoC5T39uSQ55-v7Do-wv4eca3_2H/preview){:target="_blank"}.
<div style="display: flex; justify-content: center; gap: 1em;">
    <iframe src="https://drive.google.com/file/d/1bc4_YoC5T39uSQ55-v7Do-wv4eca3_2H/preview" 
            width="640" height="480" allow="autoplay; fullscreen" allowfullscreen>
    </iframe>
   
</div>

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
