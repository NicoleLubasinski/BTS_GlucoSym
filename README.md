# BTS_GlucoSym

## Overview
GlucoSym_BTS is a Python-based tool for processing glucose time-series data to isolate the postprandial glucose response (PPGR). It integrates signal processing, ODE-based physiological modeling, optimization, using coefficient of Variation clustering to study blood glucose dynamics. 

The script is implemented as a Jupyter notebook and is designed using data from the following Zenodo repository: at https://doi.org/10.5281/zenodo.15196914 (https://doi.org/10.5281/zenodo.15196914).

## Features
- PPGR isolation from raw glucose signals
- ODE-based simulation of glucose-insulin dynamics
- Statistical analysis 
- Coefficient of Variation based PPGR clustering
- Multiprocessing for large dataset handling

## Installation
```bash
pip install -r requirements.txt
