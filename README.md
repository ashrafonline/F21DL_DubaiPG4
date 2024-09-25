# F21DL_DubaiPG4 Project - Heriot Watt University - Dubai 2024-2025

## Project Overview

Project Description Goes Here

## Repository Structure

- **data/**:
  - `raw/`: Contains unprocessed datasets. Data in this folder should remain untouched.
  - `processed/`: Cleaned and processed data that is ready for modeling.

- **notebooks/**:
  - Jupyter notebooks for exploratory data analysis, model development, and results demonstration.
  - `model_development.ipynb`: Experiments with different models and hyperparameter tuning.
  - `results.ipynb`: Final presentation of results and conclusions.

- **src/**:
  - Core source code for the project, organized into subdirectories:
    - `data/`: Scripts to clean and preprocess datasets.
    - `features/`: Scripts for feature extraction and transformation.
    - `models/`: Scripts to train, predict, and evaluate machine learning models.
    - `visualization/`: Scripts to generate charts, plots, and visual representations of the data and model results.

- **models/**:
  - Pre-trained or serialized models, such as `.pkl` or `.h5` files.

- **reports/**:
  - Any generated reports, analysis, and figures. This folder contains deliverables like presentations, PDFs, or images of results.

### Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ashrafonline/F21DL_DubaiPG4.git
   cd F21DL_DubaiPG4
2. **Push changes**
   ```bash
   git add .
   git commit -m "Describe the push you made"
   git push origin main