# Relativistic GAN using PyTorch

ℹ️ Simple Jupyter notebook that I used for my project. It is based on the work of [eriklindernoren](https://github.com/eriklindernoren/PyTorch-GAN/blob/master/implementations/relativistic_gan/relativistic_gan.py) with some enhancements for processing parameters and CUDA.

## Usage

* create a folder where your dataset will be, for instance `./dataset/dog_pictures/`
* create a conda environment `conda create --name <env> --file requirements.txt` with Python 3.7 (did not tested on > 3.7).
* open a notebook and adjust the settings on the second cell.
* run all the cells.

2 more folders will be created automatically:

* `models` to save intermediate models states
* `images` to save intermediate results

## Licence

Read it [here](LICENCE).
