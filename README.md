# Efficient Deep Learning of Non-local Features for Hyperspectral Image Classification [[arXiv]](https://arxiv.org/pdf/2008.00542.pdf)
## Introduction
For each pixel in an HSI, it is not only related to its nearby pixels but also has connections to pixels far away from itself. Therefore, to incorporate the long-range contextual information, a deep fully convolutional network (FCN) with an efficient non-local module, named ENL-FCN, is proposed for HSI classification. In the proposed framework, a deep FCN considers an entire HSI as input and extracts spectral-spatial information in a local receptive field. The efficient non-local module is embedded in the network as a learning unit to capture the long-range contextual information. Different from the traditional non-local neural networks, the long-range contextual information is extracted in a specially designed criss-cross path for computation efficiency.

## Requirements
* Ununtu 18.0 
* python 3.7 
* Pytorch 1.4 

## Training and Testing
put HSI dataset in ```Datasets``` folder <br>
run the ```Demo_IP.py``` for Indian Pines dataset training and testing<br> 

## Citation
```
@article{shen2020,
  title={Efficient Deep Learning of Non-local Features for Hyperspectral Image Classification},
  author={Shen, Yu and Zhu, Sijie and Chen, Chen and Xiao, Liang and Du, Qian and Chen, Jianyu and Pan, Delu},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2020}
}
```

## Implementation
This work is implemented based on [CCNet](https://github.com/speedinghzl/CCNet/tree/pytorch-1.1).
