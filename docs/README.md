# QLSC612 Practical Assignment 

A jupyter notebook that simulates the process of p-hacking using brain size data 

## Prerequisites 

To get started, run `pip3 install --upgrade pip` to ensure that you have the latest pip. Then, use `pip3 install SomePackage==1.0.4` to install the required packages:

```
pandas==1.0.3
numpy==1.18.1
matplotlib==3.1.3
seaborn==0.10.1
scikit-learn==0.22.1
statsmodels==0.11.1
jupyter-client==6.1.3
```

Alternatively, run `pip3 install -r docs/requirements.txt` to install all dependencies in the testing environment. 

## Usage

To run the analysis, open `scripts/myanalysis.ipynb` in jupyter notebook and follow the instructions in each cell. 

A successful analysis reads `data/brainsize.csv`, and fits Ordinary Least Squares (OLS) and Generalized Linear Model (GLM) regression models on partY / partY2 (two random variables) and PIQ. A series of distribution plots and regression plots (under `scripts`) are generated to aid the analysis. 

## Built with 

Python 3.7.6

## Author 

Hongyu Zhang 
