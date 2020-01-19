

<p class="message">
Hello! This is a repository of the study "neural network acceleration". 
The goal of this study is to understand the implmentation of nerual networks on various acceleration.
</p>

### Research Area
Machine learning acceleration using `CPU`,`GPU`, and `FPGA`, `ASIC`.

#### Parallel Programming (CPU, GPU, FPGA)
- Including AVX/NEON, OpenMP/MKL/BLAS, and OpenCL/CUDA
- DNN acceleartion API (cuDNN, cuBLAS, TensorCore)
- Xilinx's SDSoC/SDAccel 

#### Logic Design
- Frontend Design (Design Compuiler, PrimeTime, VSC, NC-Verilong)
- RTL Language (Verilog, System Verilog, Chisel)

#### DNN Acceletion HW/SW Design
- DNN Primitive Design running on CPU/GPU/NPU
- PCIe based LVCSR Acceleration HW/SW Design
- `Heterogenous accleration` with NPU and GPU
- `Edge and Server based neural processing unit (NPU)` design 

### Paper
1. DANNA: Dataflow-Aware Neural Network Accelerator 
- RL based MCU with reconfigurable systolic array
- Writing the manuscript for DAC, 2020

2. SANNA: Sparse-Aware Neural Network Accelerator 
- Fine-grain sparse matrix accelerator   
- RISC-V Co-processr implementation (65nm tech), Writing the manuscript for IEEE VLSI System, 2020

3. SENNA: Semi-reconfigurable and efficient Neural Network Accelerator 
- Semi-reconfigurable accelerator for various dimensions and shape matrix multiplication  
- NPU Archiecture running on RISC-V, Under Elsevier Integration review, 2020

4. CENNA: Cost Effective Neural Network Accelerator
- Reducing the hardware cost using proposed cost-centric method
- Sansung 65nm tech implementation, MDPI electronics, 2020

5. Implementation of a CNN accelerator on an Embedded SoC Platform using SDSoC
- Ruducing read after write (RAW) dependencies in HLS
- ACM ICDSP (Tokyo), 2018

6. Modified Convolution Neural Network for Highly Effective Parallel Processing
- Reducing the divergence branch problem in LeNet-5
- IEEE IRI Conference (San Diago), 2017

7. Prediction unit pruning algorithm for inter-prediction in high-efficiency video coding
- IET Electronics Letter, 2015

### Project
#### 1. Reinforcement learning (RL) framework running on edge-device 
<p class="message">
   Reinforcement learning (RL) is running on home appliances (Edge-device). As you know, edge-device is desinged for low-power and  computing-power. The goal of this project is designing a lightweight RL framework (On-device RL). Funded by LG electronics (2019.12 ~ 2020.11).
</p>

#### 2. DIMM based big data acceleration system design 
<p class="message">
   Research the acceleration method of NN that can be implemented at the DIMM level. 
  NN acceleartion in close to memory is efficient for both throughput and power consumption.
  This project aims to implement a recommendation system. Funded by Samsung electronics (2019.07 ~ 2020.06)
</p>

#### 3. Deep neural netowrk framework for edge-device
<p class="message">
   Research the BLAS engine for inference of NN on edge-device. 
  Also, using transfer learning, home applicance can adopt to different operating environments.
  Funded by LG electronics (2018.07 ~ 2019.06)
</p>

#### 4. LVCSR based AI speaker system HW/SW implementation
<p class="message">
   Explore the hw/sw design space of LVCSR based ASR acceleration.
  The goal of this project is designing CUDA based ASR Engien and PCIe based Acceleration System.
  In this project, Jetson Tx2 based AI speaker and Kintex-7 based PCIe accelerator are designed.
  Funded by MOTIE, Korea (2017.01 ~ 2020.12)
</p>


### Teaching
#### 1. Parallel computing overview for GIS startup company 
<p class="message">
   Lecture parallel computing (OpenMP, CUDA, cuBLAS/cuDNN for GIS enginners. Funded by InnoPAM (2020.01 ~ 2020.01).
</p>

#### 2. Development program for big data engineer
<p class="message">
   Lecture big data and recommendation system for private banker. Funded by Mirase Asset Life Insurance (2019.11 ~ 2019.12).
</p>

#### 3. Competency Development Program for AI and Big data engineer
<p class="message">
   Lecture big data and AI for undergraduate students and person preparing employement.
  Funded by Seoul city and KAIST (2019.07 ~ 2019.08)
</p>

### Presentation
1. How to accelerate nerual network with Tensor core in MODUCON19 (모두콘 19)
- 2019.19, Presentation at Global education ceter for enginners in Seoul national university (SNU)
- https://github.com/ConstantPark/EDU-Neural_Accleration_Lab/tree/master/MODUCON19


### Comminutiy
1. Teacher of CUDA beginner Course (풀잎스쿨) and Leader of Neural acceleartion lab in Modulabs (모두의 연구소)  
- 2019.07 ~ Present
- https://github.com/ConstantPark/cuDNN-with-LeNet and https://github.com/ConstantPark/Tensor_Core

2. TF korea shinchon community
- 2017.09 ~ Present
- https://www.facebook.com/groups/SCDeepLearning/

3. Parallel development community (PDC) community
- 2017.12 ~ Present
- https://cafe.naver.com/speedbetter

### Patent
1. Neural network acceleration method and neural network accelerator structure capable of dynamically adapting to matrix size
- 10-2019-0092932, Funded by MOTIE, Korea 

2. Quantization and acceleration on deep learning using dynamic precision number representation and operator structure
- 10-2019-0086281 , Funded by MOTIE, Korea 

3. An Efficient SIMD Implementation Technique for Accelerating Convolution Neural Networks
- 10-2018-0124166, Funded by MOTIE, Korea 

4. Highly Effective Work-group Scheduling Techniques for Convolution Neural Network using OpenCL
- 10-2018-0076692, Funded by MOTIE, Korea 

5. Deep neural network accelerator using Strassen's algorithm based multiplication method
- 10-2018-0076691, Funded by MOTIE, Korea 
