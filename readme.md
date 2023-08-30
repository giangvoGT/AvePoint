# README

This project is a text classification task on the Reuters-21578 dataset. The goal of the project is to predict the topic of a document based on its content.

The main steps in the project are:

1. Data Loading and Preprocessing: The Reuters-21578 dataset is loaded and parsed.

1. Feature Extraction: Each document is transformed into an embedding vector using OpenAI's ada-002 model.

1. Model Training: An XGBoost model is trained on the extracted features to predict the topic of a document.

1. Model Evaluation: The trained model's performance is evaluated using several metrics, including accuracy, precision, recall, F1-score, and ROC-AUC.

1. Visualization: Several visualizations are created to provide insights into the data and the model's performance.

## Environment Setup

This project requires Python and several Python packages. A `requirements.txt` file is provided to install the necessary packages using pip:

```
pip install -r requirements.txt
```

## Data

The dataset used in this project is the Reuters-21578 dataset, which is a collection of documents that were assembled and indexed by Reuters in 1987 for research purposes. The dataset can be found in the `data` directory.

## Scripts

The main script in this project is `main.ipynb`, which carries out the data loading, preprocessing, feature extraction, model training, and evaluation.

## Model

The trained XGBoost model is saved in the `model` directory.

## How to Run

Once the environment is set up and the data is in place, you can run the `main.ipynb` script using Jupyter notebook:

```
jupyter notebook main.ipynb
```

## Results

The results of the model training and evaluation are saved in the `report.pdf` file.

______________________________________________________________________

`requirements.txt`

```
numpy
pandas
beautifulsoup4
tqdm
openai
chromadb
langchain
scikit-learn
xgboost
plotly
jupyter
```
