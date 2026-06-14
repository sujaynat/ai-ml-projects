# AI/ML Projects

This repository contains a curated collection of AI, machine learning, deep learning, computer vision, and generative AI projects. Each project folder includes a clean Jupyter notebook converted from the original HTML export, along with the input files required to understand or rerun the work.

## Repository Structure

| Project | Area | Notebook | Input Files |
| --- | --- | --- | --- |
| [ML](./ML/) | Banking / marketing analytics | [`personal-loan-prediction.ipynb`](./ML/personal-loan-prediction.ipynb) | `Loan_Modelling.csv` |
| [advanced-ML](./advanced-ML/) | Immigration / workforce analytics | [`easyvisa-approval-prediction.ipynb`](./advanced-ML/easyvisa-approval-prediction.ipynb) | `EasyVisa.csv` |
| [NeuralNetwork](./NeuralNetwork/) | Renewable energy / predictive maintenance | [`renewind-failure-prediction.ipynb`](./NeuralNetwork/renewind-failure-prediction.ipynb) | `Train.csv`<br>`Test.csv` |
| [Computer-Vision](./Computer-Vision/) | Computer vision / workplace safety | [`helmet-detection.ipynb`](./Computer-Vision/helmet-detection.ipynb) | `Labels_proj.csv`<br>`images_proj.npy` |
| [NLP-GenAI](./NLP-GenAI/) | Generative AI / healthcare NLP | [`medical-rag-question-answering.ipynb`](./NLP-GenAI/medical-rag-question-answering.ipynb) | `medical_diagnosis_manual.pdf` |
| [ModelDeployment](./ModelDeployment/) | Retail analytics / model deployment | [`superkart-sales-forecasting.ipynb`](./ModelDeployment/superkart-sales-forecasting.ipynb) | `SuperKart.csv` |

## Projects Overview

### Personal Loan Campaign Prediction

Builds a supervised machine learning model for AllLife Bank to predict which liability customers are likely to purchase a personal loan.

- Folder: [`ML`](./ML/)
- Domain: Banking / marketing analytics
- Main notebook: [`personal-loan-prediction.ipynb`](./ML/personal-loan-prediction.ipynb)

### EasyVisa Approval Prediction

Uses ensemble learning and model tuning to predict visa application outcomes from employer and applicant case data.

- Folder: [`advanced-ML`](./advanced-ML/)
- Domain: Immigration / workforce analytics
- Main notebook: [`easyvisa-approval-prediction.ipynb`](./advanced-ML/easyvisa-approval-prediction.ipynb)

### ReneWind Generator Failure Prediction

Develops neural network based models to predict wind turbine generator failures using transformed sensor data.

- Folder: [`NeuralNetwork`](./NeuralNetwork/)
- Domain: Renewable energy / predictive maintenance
- Main notebook: [`renewind-failure-prediction.ipynb`](./NeuralNetwork/renewind-failure-prediction.ipynb)

### Helmet Detection Computer Vision Model

Builds an image classification model to identify whether workers are wearing safety helmets in workplace images.

- Folder: [`Computer-Vision`](./Computer-Vision/)
- Domain: Computer vision / workplace safety
- Main notebook: [`helmet-detection.ipynb`](./Computer-Vision/helmet-detection.ipynb)

### Medical RAG Question Answering

Creates a retrieval augmented generation workflow over a medical manual to answer healthcare-related questions.

- Folder: [`NLP-GenAI`](./NLP-GenAI/)
- Domain: Generative AI / healthcare NLP
- Main notebook: [`medical-rag-question-answering.ipynb`](./NLP-GenAI/medical-rag-question-answering.ipynb)

### SuperKart Sales Forecasting and Deployment

Builds a sales prediction model for SuperKart using product and store attributes, with model deployment-oriented workflow steps.

- Folder: [`ModelDeployment`](./ModelDeployment/)
- Domain: Retail analytics / model deployment
- Main notebook: [`superkart-sales-forecasting.ipynb`](./ModelDeployment/superkart-sales-forecasting.ipynb)

## How to Use

1. Open any project folder.
2. Review the project-specific `README.md`.
3. Open the notebook in Jupyter Notebook, JupyterLab, Google Colab, or GitHub's notebook viewer.
4. Keep the input files in the same folder as the notebook unless the notebook path is updated.

## Notes

- The notebooks were converted from HTML exports into clean `.ipynb` files.
- Notebook outputs were removed during conversion to keep the files easier to render and upload to GitHub.
- No notebook includes the `metadata.widgets` block that previously caused GitHub rendering errors.
- Some notebooks install specific package versions in the first code cells. If running locally, use a virtual environment to avoid dependency conflicts.
