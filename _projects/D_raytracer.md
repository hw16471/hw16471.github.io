---
title: Computer Graphics Raytracer 
github: https://github.com/hw16471/UOB_Raytracer
media: <div style="width:100%;height:0px;position:relative;padding-bottom:58.044%;"><iframe src="https://player.vimeo.com/video/347279698" width="640" height="480" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe></div><br>
---
### Overview
This project involved building a Real-Time Raytracer from scratch using OpenCL, GLM and SDL. As can be seen above, this raytracer was used to render the [Cornell Box](https://en.wikipedia.org/wiki/Cornell_box) where phenomena such as reflection and refraction have been showcased. The realism of the rendered image was improved further using anti-aliasing and soft shadows. Other Cornell Box scenes are shown in the images below:
* [scene1](assets/img/showcase1.png)
* [scene2](assets/img/showcase2.png)
* [scene3](assets/img/showcase3.png)

### Technologies 
* C++
* OpenCL
* OpenGL Mathematics (GLM)
* Simple DirectMedia Layer (SDL2)


### Compile and Run
```bash
git clone git@github.com:hw16471/UOB_Raytracer
cd UOB_Raytracer
source clean_build.sh
```
Requirements: A GPU, OpenCL, GLM, and SDL2
