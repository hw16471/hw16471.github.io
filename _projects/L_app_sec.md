---
title: applied_security 
---

## [Applied Security - DPA Attacks](https://github.com/hw16471/AppliedSecurity)
<img src="assets/img/labelled_trace.png" width="450">
### Overview
This project developed my understanding of how AES encryption works and the different 'trade offs' between speed, memory usage and ultimately, security. An AES implementation was first developed to run a scale-board from the University of Bristol, this device has severe hardware limitations and thus any implementation must be efficient. One of the ways this was done was to pre-compute the sbox function. A Differential Power Attack (DPA) was then created in python to interact with the board in order to gather power traces. These recorded traces could then be compared to hypothetical power consumption values for a chosen message in order to recover the key, using approximately 125 traces. A counter-measure for this style of attack was implemented called masking, this carefully used 6 masks throughout the encryption process to prevent information leaking from the CPU. This prevented key recovery for 'first order' DPA style attacks. 

### Technologies 
* C
* Python
* Multiprocessing and NumPy packages

### Compile and Run
Attacks require a scale-board, or dat file containing it's traces. If this can be obtained, 
attacks can be run with:
```bash
git clone git@github.com:hw16471/AppliedSecurity
cd AppliedSecurity/39824/scope
make parallel_attack.py
```
Requirements: A scale-board.

