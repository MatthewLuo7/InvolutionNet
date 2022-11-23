# InvolutionNet

## Introduction

This repository is our 3rd place work in [the 59th IEEE/ACM Design Automation Conference System Design Contest](https://byuccl.github.io/dac_sdc_2022/results/). A fully-pipelined FPGA accelerator for object detection CNN is designed in Vivado High-Level Synthesis. The design is deployed on an embedded FPGA, Ultra96-V2, and is evaluated according to its inference speed, energy consumption and prediction accuracy. In July 2022, the final result of the contest was announced at the 59th IEEE/ACM Design Automation Conference, San Francisco, USA.

## Team Members

- Haitong Huang, State Key Lab of Processors, Institute of Computing Technology, Chinese Academy of Sciences
- Erjing Luo, School of Information and Electronics, Beijing Institute of Technology
- Cangyuan Li, Center for Intelligent Computing Systems, Institute of Computing Technology, Chinese Academy of Sciences

## Repository Organization
- deploy: the deployment files on Ultra96-V2
- scripts: the scripts for generating HLS and Vivado project
- src: the accelerator design
