---
title:
draft: false
tags:
  - example-tag
aliases:
description: asdf
date: 2025-10-01
---
### Overview
This project was based on the paper [Towards Understanding Asynchronous Advantage Actor-Critic: Convergence and Linear Speedup](Towards_Understanding_Asynchronous_Advantage_Actor-Critic.pdf).

The study covered both the theoretical convergence analysis of Asynchronous Advantage Actor-Critic (A3C) and its multiprocessing implementation for distributed reinforcement learning, including the role of CPU cores, threads, and process management. 
Through this work, I developed a broader interest in distributed computation, which led me to further study **MPI-based parallel computing and scientific computing** during the [15th KIAS CAC Summer School on Artificial Intelligence & Parallel Computing](https://cac.kias.re.kr/2024/)

### Contributions
- Reviewed and summarized the convergence analysis of A3C from the reference paper  
- Analyzed the multiprocessing-based implementation of A3C, including shared memory, shared optimizer, and synchronization mechanisms  
- Explained system-level concepts such as CPU cores, threads, and process scheduling in the context of distributed reinforcement learning  

### Slides
- [A3C](A3C.pdf)
- [A3C Multiprocessing Code](A3C_Multiprocessing_Code.pdf)
- [Multiprocessing A3C](Multiprocessing_A3C.pdf)
- [CPU Core & Thread A3C](CPU_Core_Thread_A3C.pdf)