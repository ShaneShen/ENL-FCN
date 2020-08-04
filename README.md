# Efficient Deep Learning of Non-local Features for Hyperspectral Image Classification [[arXiv]](https://arxiv.org/pdf/2008.00542.pdf)
## Introduction
This work focuses on integrating long-range contextual information for HSI classification. Concretely, the efficient non-local module is embedded in the FCN  as a learning unit to capture the long-range contextual information with computation efficiency.

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
