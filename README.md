<p align="center">
  <a href="https://github.com/sxzgroup/qc_lecture">
    <img width=60% src="static/logo.png">
  </a>
</p>

# Quantum Computing Basics with TensorCircuit-NG

_Materials for [1st ML&QC Winter School](https://indico.ihep.ac.cn/event/24170/) at Nankai University_

## Contents

- `resources`: slides for QC introduction and lecture notes for QC by others.

- `lectures`: jupyter notebooks on QC with code demos using TC-NG

## TensorCircuit-NG

[TensorCircuit-NG](https://github.com/tensorcircuit/tensorcircuit-ng) is an open-source high-performance quantum software framework, supporting for automatic differentiation, just-in-time compiling, hardware acceleration, and vectorized parallelism, providing unified infrastructures and interfaces for quantum programming. It can compose quantum circuits, neural networks and tensor networks seamlessly with high simulation efficiency and flexibility.

Welcome to star and contribute to the project!

## Setup

To run the jupyter notebooks in `lectures`, please first `pip install -r requirements.txt`. We suggest using anaconda to manage python environment, i.e.

```bash
git clone https://github.com/sxzgroup/qc_lecture.git
cd qc_lecture

conda create -n tc python=3.10 pip
conda activate tc
pip install -r requirements.txt
jupyter notebook
```

To make a pull request, please first ensure formatting the notebooks locally by running `black .`
