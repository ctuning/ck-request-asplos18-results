[![logo](https://github.com/ctuning/ck-guide-images/blob/master/logo-powered-by-ck.png)](https://github.com/ctuning/ck)

This repository contains validated workflows and results in the [open CK format](https://github.com/ctuning/ck)
from the reproducible [ReQuEST@ASPLOS'18 tournament](http://cknowledge.org/request-cfp-asplos2018.html) 
on optimization and co-design of Pareto-efficient SW/HW stack for deep learning based inference (image classification).
You can browse these results in the [live ReQuEST scoreboard](http://cKnowledge.org/request-results):

1. [Image classification using Intel Caffe on Intel-based servers (AWS)](https://github.com/ctuning/ck-request-asplos18-caffe-intel)
2. [Image classification using MXNet/TVM/NNVM on ARM GPU](https://github.com/ctuning/ck-request-asplos18-mobilenets-tvm-arm)
3. [Image classification using TensorFlow and Apache Avro on IoT farms (5..11 Raspberry Pi 3 devices) vs NVIDIA Jetson TX2](https://github.com/ctuning/ck-request-asplos18-iot-farm)
4. [Image classification using TVM on FPGA](https://github.com/ctuning/ck-request-asplos18-resnet-tvm-fpga)
5. [Image classification using ArmCL and TensorFlow with OpenCL on HiKey 960](https://github.com/dividiti/ck-request-asplos18-mobilenets-armcl-opencl)

All above workflows implement image classification across a very diverse model/software/hardware stack:

* **Models:** MobileNets, ResNet-18, ResNet-50, Inception-v3, VGG16, SSD and AlexNet.
* **Data types:** 8-bit integer, 16-bit floating-point (half), 32-bit floating-point (float).
* **AI frameworks and libraries:** MXNet, TensorFlow, Caffe, Keras, Arm Compute Library, cuDNN, TVM and NNVM.
* **Platforms:** Xilinx Pynq-Z1 FPGA, Arm Cortex CPUs and Arm Mali GPGPUs (Linaro HiKey960 and T-Firefly RK3399), a farm of Raspberry Pi devices, NVIDIA Jetson TX2, and Intel Xeon servers in Amazon Web Services, Google Cloud and Microsoft Azure.

The reproduced results, available on the [ReQuEST scoreboard](http://cKnowledge.org/request-results), also exhibit amazing diversity:
* **Latency:** 4 .. 500 ms
* **Throughput:** 2 .. 465 images/sec
* **Top 1 accuracy:** 41 .. 75 %
* **Top 5 accuracy:** 65 .. 93 %
* **Platform cost:** 40 .. 1200 $
* **Device frequency:** 100 .. 2600 MHz
* **Peak power consumption:** 2.5 .. 180 Watts
* **Trained model size (weights):** 2 .. 130 MB
* **Cloud usage cost per inference:** 2.6E-6 .. 9.5E-6 $

# Further discussions

* [Collective Knowledge mailing list](http://groups.google.com/group/collective-knowledge)
* [Collective Knowledge slack](https://collective-knowledge.slack.com)
* [Artifact evaluation mailing list](http://groups.google.com/group/artifact-evaluation)
