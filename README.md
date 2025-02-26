# Harnessing Machine Learning and Advanced Data Insights for Lithium Recovery from Oil and Gas Brines

Code Repository for the paper "Harnessing Machine Learning and Advanced Data Insights for Lithium Recovery from Oil and Gas Brines"

## Abstract
This study tackles the urgent need for efficient lithium recovery from briny
formation waters associated with oil and gas production. By integrating advanced machine
learning techniques with updated datasets from the USGS National Produced Waters
Geochemical Database (PWGD), the research aims to bridge existing gaps in predictive
modeling. The application of explainable AI methods ensures enhanced transparency and
reliability, enabling better operational decisions. Lightweight machine learning models
designed for EdgeIoT deployment further underscore the scalability and practicality of the
approach. Achieving 97.7% prediction accuracy, this work paves the way for smarter, more
robust lithium recovery systems capable of addressing geological uncertainties and driving
innovation in the field. 

## Tech Stack

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## Run Locally

Clone the project

```bash
  git clone https://github.com/neuralix-ai/HarnessingMachineLearningandAdvancedDataInsightsforLithiumRecoveryfromOilandGasBrines
```
And run `Water-.ipynb `
Python>=3.10


## Project Structure

    .
    ├── LICENSE                 <- Project license file
    ├── README.md               <- Top-level README for developers/researchers using this project
    ├── Water.ipynb             <- the main notebook with all working codes to reproduce results presented in the paper
    ├── cwd                     <- Directory for storing class wise distribution plots
    ├── data.csv                <- CSV cleaned USGS PWGD V3 dataset
    ├── dviz                    <- Directory for storing XAI plots
    ├── metrics                 <- Directory for storing all model metrics
    └── models                  <- Directory for storing all models as pkl files