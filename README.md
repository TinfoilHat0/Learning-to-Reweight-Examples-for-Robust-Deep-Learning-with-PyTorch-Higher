# Learning-to-Reweight-Examples-for-Robust-Deep-Learning-with-PyTorch-Higher
An implementation of the paper [Learning to Reweight Examples for Robust Deep Learning](https://arxiv.org/abs/1803.09050) from ICML 2018 with PyTorch and [Higher](https://github.com/facebookresearch/higher).
Core of the paper is the following algorithm.

<img src="reweight_alg.png" width="400" />

Simply see the notebook for my implementation.

I was able to replicate the imbalanced MNIST experiment from the paper.Orange is baseline, blue is the method from paper.

<img src="results.png" width="600" />



## Citation
```bibtex
@inproceedings{ren2018learning,
  title={Learning to reweight examples for robust deep learning},
  author={Ren, Mengye and Zeng, Wenyuan and Yang, Bin and Urtasun, Raquel},
  booktitle={International conference on machine learning},
  pages={4334--4343},
  year={2018},
  organization={PMLR}
}
```
