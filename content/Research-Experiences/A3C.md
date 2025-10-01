---
title: A3C and Distributed RL
draft: false
tags:
  - distributed_RL
  - AI
  - parallel_computing
aliases:
description: Convergence analysis of A3C and its multiprocessing implementation in distributed reinforcement learning; extended interest to MPI-based parallel computing.
date: 2025-10-01
---
**Institution:** Sungkyunkwan University  
**Advisor:** [Prof. Woocheol Choi](https://sites.google.com/site/wchoiam), [Prof. Jeonggyu Huh](https://sites.google.com/view/jeonggyuhuh)  

### Overview
This project was based on the paper [Towards Understanding Asynchronous Advantage Actor-Critic: Convergence and Linear Speedup](https://ieeexplore.ieee.org/document/10124081/).

The study covered both the theoretical convergence analysis of Asynchronous Advantage Actor-Critic (A3C) and its multiprocessing implementation for distributed reinforcement learning, including the role of CPU cores, threads, and process management. 
Through this work, I developed a broader interest in distributed computation, which led me to further study **MPI-based parallel computing and scientific computing** during the [15th KIAS CAC Summer School on Artificial Intelligence & Parallel Computing](https://cac.kias.re.kr/2024/)

### Contributions
- Reviewed and summarized the convergence analysis of A3C from the reference paper  
- Analyzed the multiprocessing-based implementation of A3C, including shared memory, shared optimizer, and synchronization mechanisms  
- Explained system-level concepts such as CPU cores, threads, and process scheduling in the context of distributed reinforcement learning  

### Slides
- [A3C](A3C.pdf) — Overview of Asynchronous Advantage Actor-Critic (A3C) and its convergence analysis  
- [A3C Multiprocessing Code](A3C_Multiprocessing_Code.pdf) — Walkthrough of Python multiprocessing code implementing A3C with shared memory and optimizer  
- [Multiprocessing A3C](Multiprocessing_A3C.pdf) — Explanation of multiprocessing concepts in A3C, including process creation, locks, and shared counters  
- [CPU Core & Thread A3C](CPU_Core_Thread_A3C.pdf) — Background on CPU, cores, threads, and their role in running multiple A3C worker processes
