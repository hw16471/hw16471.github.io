---
title: Computer Graphics Raytracer 
github: https://github.com/ainsleyrutterford/UOB_Raytracer
media: <div style="width:100%;height:0px;position:relative;padding-bottom:58.044%;">  <iframe src="https://streamable.com/s/rn875/wxuqhg" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;;border-radius:15px"> </iframe> </div> <br>
---
## [Parallel Optimisations of a Lattice Boltzmann Code (Using the BlueCrystal Supercomputer)](https://github.com/hw16471/UOB_OpenCL_LBM)
<img src="assets/img/final_state.png" width="450">
### Overview
This project was all about learning how to exploit different hardware to improve the runtime of a Lattice Boltzmann code, which is widely used for simulating fluid dynamics. Popular programming platforms like MPI, OpenMP and OpenCL were each implemented and tested in various different combinations. The most efficient of these was OpenCL or MPI+OpenCL, which utilized one or more GPUs. If you want know more about this, please read the [article](https://github.com/hw16471/UOB_OpenCL_LBM/blob/master/submission/report.pdf) I wrote. 

### Technologies 
* C
* OpenCL
* MPI
* OpenMP

### Compile and Run
```bash
git clone git@github.com:hw16471/UOB_OpenCL_LBM
cd UOB_OpenCL_LBM/submission
make
./d2q9-bgk ../input_128x128.params ../obstacles_128x128.dat
```
Requirements: A GPU, OpenCL
