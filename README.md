# adip-crowdCount
A crowd counting application based on the CSRNet benchmark

## Datasets
ShanghaiTech Dataset: [Google Drive](https://drive.google.com/open?id=16dhJn7k4FWVwByRsQAEpl9lwjuV03jVI)

## Prerequisites
Recommended environment: Anaconda.

Python: 3.7.2

PyTorch: 1.7.0

CUDA: 10.1

## Ground Truth
Follow the `main.ipynb ` to generate the ground truth. 
Note: you need to generate your own json file

## Training
Run command `python train.py train.json val.json 0 0` to start training process.

## Validation
Follow the `val.ipynb` to try the validation.
