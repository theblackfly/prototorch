# ProtoTorch

ProtoTorch is a PyTorch-based Python toolbox for bleeding-edge research in
prototype-based machine learning algorithms.

![Tests](https://github.com/si-cim/prototorch/workflows/Tests/badge.svg?branch=master)

## Description

This is a Python toolbox brewed at the Mittweida University of Applied Sciences
in Germany for bleeding-edge research in Learning Vector Quantization (LVQ)
methods. Although, there are other (perhaps more extensive) LVQ toolboxes
available out there, the focus of ProtoPy is ease-of-use, extensibility and
speed.

Many popular prototype-based Machine Learning (ML) algorithms like K-Nearest
Neighbors (KNN), Generalized Learning Vector Quantization (GLVQ) and Generalized
Matrix Learning Vector Quantization (GMLVQ) including the recent Learning Vector
Quantization Multi-Layer Network (LVQMLN) are implemented using the "nn" API
provided by PyTorch.

## Installation

ProtoTorch can be installed using `pip`.
```
pip install prototorch
```

## Usage

ProtoTorch is modular. It is very easy to use the modular pieces provided by
ProtoTorch, like the layers, losses, callbacks and metrics to build your own
prototype-based(instance-based) models. These pieces blend-in seamlessly with
numpy and PyTorch to allow you mix and match the modules from ProtoTorch with
other PyTorch modules.

ProtoTorch comes prepackaged with many popular LVQ algorithms in a convenient
API, with more algorithms and techniques coming soon. If you would simply like
to be able to use those algorithms to train large ML models on a GPU, ProtoTorch
lets you do this without requiring a black-belt in high-performance Tensor
computation.
