# QLSC612 Practical Assignment 

A jupyter notebook that simulates the process of p-hacking using brain size data 

## Getting Started 

The following libraries are required in addition to jupyter notebook. For all dependencies of the testing environment, see `docs/requirements.txt`. 

```
pandas==1.0.3
numpy==1.18.1
matplotlib==3.1.3
seaborn==0.10.1
scikit-learn==0.22.1
statsmodels ==0.11.1
```

## Usage

To run the analysis, open `scripts/myanalysis.ipynb` in jupyter notebook and follow the instructions in each cell. 

A successful analysis reads `brainsize.csv`, and fits Ordinary Least Squares (OLS) and Generalized Linear Model (GLM) regression models on partY / partY2 and PIQ. A series of distribution plots and regression plots are generated to aid the analysis. 

## Author 

Hongyu Zhang 
