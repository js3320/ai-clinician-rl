# AI Clinician - Reinforcement Learning for Sepsis Treatment

This repository contains the code for reinforcement learning-based clinical decision support for sepsis treatment using the MIMIC-III database.

## Overview

This project implements an AI clinician using reinforcement learning to optimize treatment strategies for sepsis patients. The model learns optimal policies for fluid administration and vasopressor therapy based on patient state.

## Files

### Main Analysis Files
- `preprocessing_and_RL_modelling.ipynb` - Main notebook containing data preprocessing and RL model training
- `preprocessing_and_RL_modelling-Copy[1-3].ipynb` - Alternative versions/experiments
- `preprocessing_and_RL_modelling_best.ipynb` - Best performing model variant

### MATLAB Core Files
- `AIClinician_core_160219.m` - Core AI Clinician implementation (Feb 2019 version)
- `AIClinician_core_181118.m` - Core AI Clinician implementation (Nov 2018 version)
- `AIClinician_mimic3_dataset_160219.m` - MIMIC-III dataset processing
- `AIClinician_sepsis3_def_160219.m` - Sepsis-3 definition implementation

### Data Extraction
- `AIClinician_Data_extract_MIMIC3_140219.ipynb` - Data extraction from MIMIC-III database

## Requirements

### Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

### MATLAB
- MATLAB R2018b or later
- Statistics and Machine Learning Toolbox

## Data

**Note**: This repository does NOT include any patient data for privacy and data protection reasons. 

To use this code, you will need to:
1. Obtain access to the MIMIC-III database from PhysioNet (https://mimic.physionet.org/)
2. Complete required training and sign data use agreements
3. Extract the required data using the provided extraction scripts
4. Place the extracted data in a `data_extraction/` folder

The following data files are expected (but not included):
- Demographics, labs, medications, fluids, vitals, etc. (see extraction notebook)

## Usage

1. **Data Extraction**: Use `AIClinician_Data_extract_MIMIC3_140219.ipynb` to extract required data from MIMIC-III
2. **Preprocessing & Training**: Run `preprocessing_and_RL_modelling.ipynb` to preprocess data and train the RL model
3. **Analysis**: Use the MATLAB scripts for additional analysis and evaluation

## Citation

If you use this code, please cite the original AI Clinician paper:

[Add appropriate citation here]

## License

[Add your chosen license here]

## Contact

[Add your contact information]

## Disclaimer

This code is for research purposes only and should not be used for clinical decision-making without proper validation and regulatory approval.
