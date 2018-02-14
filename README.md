[![logo](https://github.com/ctuning/ck-guide-images/blob/master/logo-powered-by-ck.png)](https://github.com/ctuning/ck)
[![logo](https://github.com/ctuning/ck-guide-images/blob/master/logo-validated-by-the-community-simple.png)](http://cTuning.org)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

<!-------------------------------------------------------------------------------------->
# Introduction

This repository contains validated results in [the CK format](https://github.com/ctuning/ck)
from the [1st ACM ReQuEST tournament](http://cknowledge.org/request-cfp-asplos2018.html) 
on algorithm/software/hardware co-design of Pareto-efficient 
image classification at ASPLOS'18.

See [ReQuEST website](http://cKnowledge.org/request) 
and [arXiv report](https://arxiv.org/pdf/1801.06378.pdf) 
for more details about our open and reproducible tournaments
on Pareto-efficient co-design of the whole software and hardware
stack for AI, deep learning and other emerging workloads.

<!-------------------------------------------------------------------------------------->
# Validated submissions


<!-------------------------------------------------------------------------------------->
# Ongoing evaluation for image classification

1. [Image classification using Caffe on Intel-based servers (AWS)](https://github.com/ctuning/ck-request-asplos18-caffe-intel)
2. [Image classification using farm of RPi and TX2](https://github.com/ctuning/ck-request-asplos18-iot-farm)
3. [Image classification using ArmCL with OpenCL on HiKey 960](https://github.com/dividiti/ck-request-asplos18-mobilenets-armcl-opencl)
4. [Image classification using TVM/NNVM on ARM GPU](https://github.com/ctuning/ck-request-asplos18-mobilenets-tvm-arm)
5. [TBA](TBA)

<!-------------------------------------------------------------------------------------->
# Reproducing and validating results

<!-------------------------------------------------------------------------------------->
## Prerequisites

* Collective Knowledge Framework: see [minimal installation guidelines](https://github.com/ctuning/ck#minimal-installation)

<!-------------------------------------------------------------------------------------->
## Installation

Note that *#* means *sudo* on Linux and can be skipped on Windows.


```
# pip install ck
$ ck pull repo:ck-request-asplos18-results
```
