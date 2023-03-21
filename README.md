# PM-HGNN

Implementation of the PM-HGNN with Pytorch, another implementation with Tensorflow incoming.

### Required packages
The code has been tested running under Python 3.8.1. with the following packages installed (along with their dependencies):

- numpy == 1.18.2
- pandas == 1.0.4
- scikit-learn == 0.23.1
- networkx == 2.5
- pytorch == 1.6.0
- torch_geometric == 1.5.1

### Data requirement
All datasets we used in the paper are all public datasets which can be downloaded from the internet (https://github.com/cynricfu/MAGNN/tree/master/data/raw).

### Code execution
Two ipynb files present the example experiments of PM-HGNN and PM-HGNN++ models on IMDb dataset.

## Cite

Please cite our paper if it is helpful in your own work:

```bibtex
@article{ZLP22,
author = {Zhiqiang Zhong and Cheng{-}Te Li and Jun Pang},
title = {Personalised Meta-path Generation for Heterogeneous Graph Neural Networks},
journal = {Data Mining and Knowledge Discovery (DMKD)},
volume = {36},
number = {6},
pages = {2299--2333},
publisher = {Springer},
year = {2022},
}
```
