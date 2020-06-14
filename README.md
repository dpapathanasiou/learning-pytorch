# About

Before I can dive deeply into more [ambitious projects](https://github.com/dpapathanasiou/export-import), I need a more basic understanding of how [PyTorch](https://pytorch.org/) works, so this repo captures notebooks and experiments based on the [PyTorch tutorials](https://pytorch.org/tutorials/index.html), and [Ian Pointer](https://github.com/falloutdurham)'s book [Programming PyTorch for Deep Learning](https://www.oreilly.com/library/view/programming-pytorch-for/9781492045342/), using [jupyter notebooks](https://jupyter.org/).

## Setup

Using [Anaconda](https://www.anaconda.com) makes things easy: use the `Python 3.x` [command line installer](https://www.anaconda.com/products/individual).

After downloading and [installing](https://docs.anaconda.com/anaconda/install/), execute these commands inside the `(base)` environment (the last one is optional, but useful if using [AWS](https://aws.amazon.com/)):

```sh
conda upgrade conda
conda update --all
conda install pytorch torchvision torchtext torchaudio -c pytorch
conda install -c conda-forge awscli 
```
