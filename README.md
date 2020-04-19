## Cooperative Spectral-Spatial Attention Dense Network for Hyperspectral Image Classification

Keras implementation of our method for hyperspectral image classification. The given codes are written on the University of Pavia data set and the unbiased University of Pavia data set. When you want to try another hyperspectral imagery (HSI) datasets, you just need to replace the [data set](### Hyperspectral datasets) and update the corresponding training parameters. Please refer to [Usage](### Usage) for specific usage.This repository will also update in the feature for research exchange. test

### Paper

Please cite our papers if you find it useful for your research.

Here are the bibliography info:

```

We will update it after the paper is published！

```

Paper links:



### Requirements

- This tool is compatible with Python 2.7 and Python 3.5+；
- Tensorflow 1.12.0 ;
- Keras 2.2

### The network structure

We will update it after the paper is published.

### Hyperspectral datasets

 We have used Indian Pines (IP), University of Pavia (UP), Salinas (SL) as our evaluation data sets. To demonstrate that our proposed method is effective on unbiased HSI data, we tested networks on the UP and SL. We achieved the unbiased images of HSI by a method described in [1]. Experimental results on the biased and unbiased HSI data show that our method outperforms several state-of-the-art methods in HSIC with small training samples. You can download other HSI datasets from <http://dase.grss-ieee.org/>.

[1] Liu X, Wang R, Cai Z, et al. Deep Multigrained Cascade Forest for Hyperspectral Image Classification[J]. IEEE Transactions on Geoscience and Remote Sensing, 2019, 57(10): 8169-8183.

### Usage

- Replace the file path for the hyperspectral data in code with yours.
- Change the hyper-parameter in codes to switch from different datasets.
- Train models with the University of Pavia data set: `CSSADN_UP_biased.py`.
- Train models with the unbiased University of Pavia data set: `CSSADN_UP_unbiased.py`.
- Evaluate models: Run `Load_model_*****.py`.
- Calculate the trainable number of parameters: `.\net\CSSADN_UP_NET.py`

### Acknowledgement

Part of codes come from the outstanding repositories as follows:

<https://github.com/shamangary/Keras-MNIST-center-loss-with-visualization>

<https://github.com/zilongzhong/SSRN>
