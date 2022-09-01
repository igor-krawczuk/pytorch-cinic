A simple package packaging a pytorch dataloader for [the CINIC10 dataset](https://datashare.ed.ac.uk/handle/10283/3192 ).

If you use it cite the original authors

```
@misc{https://doi.org/10.48550/arxiv.1810.03505,
  doi = {10.48550/ARXIV.1810.03505},
  url = {https://arxiv.org/abs/1810.03505},
  author = {Darlow, Luke N. and Crowley, Elliot J. and Antoniou, Antreas and Storkey, Amos J.},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), Machine Learning (cs.LG), Machine Learning (stat.ML), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {CINIC-10 is not ImageNet or CIFAR-10},
  publisher = {arXiv},
  year = {2018},
  copyright = {Creative Commons Attribution Share Alike 4.0 International}
}
```

and if you want to be nice, also [this repo](https://github.com/igor-krawczuk/pytorch-cinic) (although the code is borderline trivial so no hard feelings if not).

To use simply import 

`from pytorch_cinic.dataset import CINIC10`

and then use like CIFAR10 (except that we use `partition=train/valid/test` instead of `train=True/False`)
