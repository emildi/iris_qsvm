# Quantum Machine Learning Classification using Quantum Support Vector Machines

## Introduction

This is a demo on how to use Quantum Support Vector Machines, as implemanted by Qiskit, to perform classification on the Iris dataset

## Software Environment

### Prerequisites

The software development and experiments were done on a Linux x86-64 workstation with Ubuntu 20.04. The same software stack should work macOS or Windows, but this was not explicitly tested.

Instructions on how to recreate the conda environment are in the following section (this assumes conda is already installed and configured).

### Build a replica conda environment

To build an exact replica of the conda software environment run the following command, which would create a new conda environment called `qsi` (the name could be changed as desired) with the required packages:

```bash
conda create --name qsi --file spec-file.txt
```

Activate the conda environment, once it's installed, start a Jupyter notebook or Jupyter Lab instance and access the notebook from it.

```bash
conda activate qsi
```
