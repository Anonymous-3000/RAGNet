# RAGNet
- The implementation of "Two-Stage Single Image Reflection Removal with Reflection-Aware Guidance".

# Prerequisites  
- The code has been test on a PC with following environment
  - Ubuntu 18.04
  - Python 3.7.5
  - PyTorch 1.2.0
  - cudatoolkit 10.0
  - NVIDIA RTX 2080Ti

# Test datasets
- [Real20](https://github.com/ceciliavision/perceptual-reflection-removal) and [Real45](https://github.com/fqnchina/CEILNet) datasets are provided in `./testsets` folder.  
- The SIR dataset is not provided due to their policy, [download here](https://sir2data.github.io/) and put it under `./testsets` folder. Please organize the SIR dataset according to our code implementation.
  
# Test
### Download the code and pre-trained model

#### Method 1
Clone the repository by
```shell
$ git clone https://github.com/Anonymous-3000/RAGNet
```
and download the `pretrain.pth` into `./checkpoint` folder by clicking the `Download` button in [./checkpoint/pretrain.pth](./checkpoint/pretrain.pth) .
#### Method 2
Install git-lfs (large file support) by
```shell
$ git lfs install --skip-repo
```
and clone this repo by
```shell
$ git lfs clone https://github.com/Anonymous-3000/RAGNet
```

## Test with the pre-trained model  
```shell
$ python test.py
```
