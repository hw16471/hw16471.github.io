---
title: Dissertation - Using Sensor Fusion and Deep Learning to Improve Activity Tracking
github: https://github.com/hw16471/ActivityTrackingWithSensorFusion
media: <img src="assets/img/rnn-kal-map.png" width="450">
---
### Overview
I wrote my dissertation for my Computer Science degree on whether the accuracy of GPS tracking for sports activities (running, cycling, walking) could be improved using additional sensors found in a smartphone. Initially, I implemented a Kalman Filter to fuse the readings of each sensor, this was written in python and used popular libraries like NumPy. I then researched and taught myself the theory behind Recurrent Neural Networks (RNNs) in order to implement them using tensorflow and keras. This project was supported by the Oracle Innovation Accelerator program, who generously gave me access to a cloud compute instance.

[Link to Dissertation](https://github.com/hw16471/ActivityTrackingWithSensorFusion/blob/last-working/Using_Sensor_Fusion_and_Deep_Learning_to_Improve_Activity_Tracking.pdf)

### Technologies 
* Python
* NumPy, SciPy and Pandas
* Tensorflow
* Keras

### Compile and Run
To train model with test data:
```bash
git clone git@github.com:hw16471/ActivityTrackingWithSensorFusion
cd ActivityTrackingWithSensorFusion
python deep_learning.py
```
Requirements: A GPGPU, Python, Tensorflow_GPU, NumPy, Keras

