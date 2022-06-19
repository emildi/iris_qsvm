# Quantum Machine Learning Classification using Quantum Support Vector Machines

## Introduction

This is a demo on how to use Quantum Support Vector Machines, as implemented by using Qiskit, to perform classification on the Iris dataset. 
<br><br>
Based on ideas from https://github.com/Qiskit/qiskit-machine-learning/blob/main/docs/tutorials/03_quantum_kernel.ipynb.

## Software Environment

### Prerequisites

The software development and experiments were done on a Linux x86-64 workstation with Ubuntu 20.04.

Instructions on how to build a similar conda environment (which should work on number of different platforms, like macOS or Windows) or recreate exact replica on the conda environment (this would only work on Linux x86-64) are in the following sections (this assumes conda and pip are already installed and configured).

## Build a similar conda environment

Run the following command, which would create and activate a new conda environment called `qsvm` (the name could be changed as desired) with the required packages:

```bash
conda create -n qsvm python=3.8 -y
conda activate qsvm
```

Install the required packages:

```bash
pip install qiskit==0.34.2
pip install qiskit-machine-learning==0.3.1

conda install -c conda-forge pandas  -y

conda install jupyter notebook -y
conda install -c conda-forge matplotlib-base -y
```

Start a Jupyter notebook or Jupyter Lab instance and access the notebook from it.

## Build a replica conda environment (Linux x86-64 only)

To build an exact replica of the conda software environment on a Linux x86-64 machine run the following command, which would create a new conda environment called `qsvm` (the name could be changed as desired) with the required packages:

```bash
conda create --name qsvm --file spec-file.txt
```

Activate the conda environment, once it's installed, start a Jupyter notebook or Jupyter Lab instance and access the notebook from it.

```bash
conda activate qsvm
```
