# Kernel Spike
## Introduction
This project is for exploring using the kernel function as a alternative for exponantial function in computing the spike convolution, which is used to approximate the spike outputs.
The algorithm is implemented in [Pytorch](https://pytorch.org/) and the configuration is in [YAML](https://yaml.org/), managed by [Hydra](https://hydra.cc/).

## TODO
- [ ] Implement the kernel function
- [ ] Implement the spike convolution layer with kernel function
- [ ] Implement the auto diff w.r.t. the kernel function
- [ ] Test, and make sure the algorithm can converge