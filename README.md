# Towards Robust Adversarial Training via Dual-label Geometry Dispersion

## Introduction
This is the implementation of the
paper ["Towards Robust Adversarial Training via Dual-label Geometry Dispersion"]

## Usage
### Installation
The training environment (PyTorch and dependencies) can be installed as follows:
```
cd DGDAT-master
python setup.py install
```

#### Results
| Datasets     | Clear | FGSM   | PGD-100    | Model                                                   |
| ------------ | ------|--------| -------- | ----------------------------------------------------------|
| CIFAR-10     | 90.4% | 77.5%  |  65.6%   | [Modellink](https://drive.google.com)                     |
| CIFAR-100    | 72.3% | 69.3%  |  31.2%   | [Modellink](https://drive.google.com)                     |
| SVHN         | 95.6% | 91.4%  |  75.1%   | [Modellink](https://drive.google.com)                     |
### Train
```
sh ./train.sh
```
### Evaluate
```
sh ./eval.sh
```
