# Kernel Spike

## Introduction

This project is for exploring using the kernel function as a alternative for exponantial function in computing the spike convolution, which is used to approximate the spike outputs.
The algorithm is implemented in [Pytorch](https://pytorch.org/) and the configuration is in [YAML](https://yaml.org/), managed by [Hydra](https://hydra.cc/).

## TODO

- [ ] Implement the kernel-weight metho
- [ ] Implement the kernel-attention method
- [ ] Implement the ... undergoing method 

## Usage
To run the code, you need to install the dependencies first:
```bash
pip install -r requirements.txt
```
Then, you can run the code with the following command for training the model:
```bash
python train.py
```
To test the model, you can run the following command:
```bash
python test.py
```

The configuration is in `config` folder, you can change the configuration by modifying the file or using command line arguments. For example, to change the learning rate, you can run the following command:
```bash
python train.py trainer.lr=0.01
```
or directly change the `lr` in `config/trainer.yaml` file.
For more information about the configuration, please refer to the [Hydra documentation](https://hydra.cc/docs/intro).
