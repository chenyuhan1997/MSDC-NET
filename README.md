<p align="center">
   <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=MSDC NET&center=true&size=27" />
  <img src="https://github.com/chenyuhan1997/PED/blob/main/assets/1.png" alt="my" width="1000" style="display: block; margin: 0 auto;"/>
   <a href="https://github.com/chenyuhan1997/PED/"><img src="https://img.shields.io/badge/Project-PED-black" /></a>&emsp;
</p>

# :fire::fire::fire: Multi-scale Shifted Dilated Convolutional Neural Network for Low-light Image Enhancement

- :star: - **Arxiv** (Coming Soon)
- :star: - **DATESET:**[LOL](https://daooshee.github.io/BMVC2018website/) [FIVEK](https://data.csail.mit.edu/graphics/fivek/) [LSRW](https://github.com/JianghaiSCU/R2RNet) 
- :star: - **Pretrained Models:** `Mini_weight.pkl` `Max_weight.pkl`

<img width="200%" src="https://github.com/chenyuhan1997/chenyuhan1997/blob/main/assets/hr.gif" />

## Introduction
<img src="https://github.com/chenyuhan1997/MSDC-NET/blob/main/assets/1.png" alt="my" width="1000" style="display: block; margin: 0 auto;"/>

MSDC-NET aims to become the deep learning model for low-light image enhancement with the smallest number of parameters and minimal floating-point operations in recent years. Both the model and its variants have parameter counts of ≤ **240 bytes**. Experimental validation demonstrates that MSDC-NET achieves state-of-the-art performance compared to existing algorithms across multiple metrics, including SSIM, PSNR, parameters, and FLOPs

<img width="200%" src="https://github.com/chenyuhan1997/chenyuhan1997/blob/main/assets/hr.gif" />

## :running: TODO
- [x] Release project page
- [ ] Release max / min model weights on **Github**
- [ ] Release paper
- [ ] Release inference code
- [ ] Release training code
- [ ] Release evaluation code

## :arrow_forward: Getting Started

### Installation

1. Clone MSDC-NET.
```bash
git clone --recursive https://github.com/chenyuhan1997/MSDC-NET
cd MSDC-NET
# git submodule update --init --recursive
```
2. Create the environment, here we show an example using conda.
```bash
conda create -n MSDC-NET python=3.11
conda activate MSDC-NET
conda install pytorch torchvision pytorch-cuda=12.1 -c pytorch -c nvidia  # use the correct version of cuda for your system
pip install opencv, kornia, pytorch_msssim, matplotlib, PIL, scikit-image, scipy, einops, math, typing
```

### Train & Test
1. Train
```bash
python train.py
```
2. Test
```bash
python test.py
```
<img width="200%" src="https://github.com/chenyuhan1997/chenyuhan1997/blob/main/assets/hr.gif" />

## :city_sunset: Results on Low-light Image Enhancement

<img src="https://github.com/chenyuhan1997/MSDC-NET/blob/main/assets/2.png" alt="my" width="1000" style="display: block; margin: 0 auto;"/>


:warning: **The current image is for demonstration purposes only and is not the final product.**





