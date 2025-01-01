# Conditional Self-Supervised Learning for Few-Shot Classification

本项目为南京大学22级智科数学建模大作业对于论文Conditional Self-Supervised Learning for Few-Shot Classification的代码复现，论文的github仓库地址为https://github.com/anyuexuan/CSS ,对代码作了略微修改以在自己的环境配置下能够运行。

## Enviroment

Python3,12

torch:2.5.1+cu121

Driver Version: 535.104.05   CUDA Version: 12.2

实验在两张NVIDIA RTX 6000 Ada Generation上运行

## Getting started

### CIFAR-FS

- Change directory to `./filelists/cifar`
- Download [CIFAR-FS](https://drive.google.com/file/d/1i4atwczSI9NormW5SynaHa1iVN1IaOcs/view)
- run `bash ./cifar.sh`

### CUB

- Change directory to `./filelists/CUB`
- Download [CUB-200-2011](https://data.caltech.edu/records/65de6-vp158)
- run `bash ./CUB.sh`

### mini-ImageNet

- Change directory to `./filelists/miniImagenet`
- Download [mini-ImageNet](https://drive.google.com/file/d/1hQqDL16HTWv9Jz15SwYh3qq1E4F72UDC/view)
- run `bash ./miniImagenet.sh`

## Running

```
python run_css.py
```



