---
title: Parallel Optimizations of a Lattice Boltzmann Code (May 2019)
github: https://github.com/hw16471/UOB_OpenCL_LBM
media: <img src="assets/img/final_state.png" width="300px">
---

### Overview
This project was all about learning how to exploit different hardware to improve the runtime of a Lattice Boltzmann code, which is widely used for simulating fluid dynamics. Popular programming platforms like MPI, OpenMP and OpenCL were each implemented and tested in various different combinations. The most efficient of these was OpenCL or MPI+OpenCL, which utilized one or more GPUs. If you want know more about this, please read the [article](assets/docs/report.pdf) I wrote. 

**Note: This repo is currently private on GitHub as I'm involved in teaching at the University of Bristol. Please email if you would like a copy."

### Technologies 
* C
* OpenCL
* MPI
* OpenMP
* MPI + OpenCL

### Compile and Run
```bash
git clone git@github.com:hw16471/UOB_OpenCL_LBM
cd UOB_OpenCL_LBM/submission
make
./d2q9-bgk ../input_128x128.params ../obstacles_128x128.dat
```
Requirements: A GPU, OpenCL
