# Multivariate Gait Data 

## Overview  
This project uses machine learning models to predict whether a subject is wearing a brace based on gait cycle data. The project includes data preprocessing, model training, evaluation, and feature importance analysis.

## Python and Package Versions  
To ensure reproducibility, the project uses:  
- **Python Version**: 3.12.5  
- **Package Versions**: Refer to `data1030.yaml` for the full list of dependencies.

### Key Libraries:  
- pandas == 1.3.3  
- numpy == 1.21.2  
- scikit-learn == 1.0  
- matplotlib == 3.4.3  
- shap == 0.41.0  
- xgboost == 1.4.2  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/cccccccccc02/Data1030_Project.git  
   cd Data1030_Project
2. Create and activate the environment using data1030.yaml file:
   ```bash
   conda env create -f environment.yaml  
   conda activate brace-detection

## Directory Structure
├── data/            # Raw and preprocessed data  
├── figures/         # Generated figures  
├── results/         # Predictions, saved models, evaluation metrics  
├── report/          # Final report (PDF)  
├── src/             # Source code (Python scripts and notebooks)  
├── data1030.yaml    # Conda environment file  
├── LICENSE          # Project license  
└── README.md        # Project overview  

## Contact
Author: Chuyi Hu
GitHub: YourUsername