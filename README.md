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
