# RAGNet
- The implementation of "Two-Stage Single Image Reflection Removal with Reflection-Aware Guidance".

# Prerequisites  
- python=3.7.5, pytorch=0.1.2  
- Ubuntu 18.04, cuda-10.0

# Test datasets
- [Real20](https://github.com/ceciliavision/perceptual-reflection-removal) and [Real45](https://github.com/fqnchina/CEILNet) datasets are provided in ./testsets folder.  
- The SIR dataset is not provided due to their policy, [download](https://sir2data.github.io/) here and put it under ./testsets folder. Please organize the SIR dataset according to our code implementation.
  
# Test
- Clone the repository and download the **pretrain.pth** in ./checkpoint folder, then put **pretrain.pth** under ./checkpoint folder.
- Run  
  `$ python test.py`
