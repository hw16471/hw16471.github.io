---
title: Computer Graphics Raytracer 
github: https://github.com/ainsleyrutterford/UOB_Raytracer
media: >
<div style="width:100%;height:0px;position:relative;padding-bottom:58.044%;">
  <iframe src="https://streamable.com/s/rn875/wxuqhg" frameborder="0" width="100%" height="100%" allowfullscreen style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;;border-radius:15px">
  </iframe>
</div>
<br>
---


### Overview
This project involved building a Real-Time Raytracer from scratch using OpenCL, GLM and SDL. As can be seen above, this raytracer was used to render the [Cornell Box](https://en.wikipedia.org/wiki/Cornell_box) where phenomena such as reflection and refraction have been showcased. The realism of the rendered image was improved further using anti-aliasing and soft shadows. Other Cornell Box scenes are shown in the images below:
* [scene1](https://streamable.com/1mugn)
* [scene2](https://streamable.com/kwoa2)
* [scene3](https://streamable.com/phfs2)

### Technologies 
* C
* OpenCL
* OpenGL Mathematics (GLM)
* Simple DirectMedia Layer (SDL2)


### Compile and Run
```bash
git clone git@github.com:ainsleyrutterford/UOB_Raytracer
cd UOB_Raytracer
source clean_build.sh
```
Requirements: A GPU, OpenCL, GLM, and SDL2
