# Energy Consumption Prediction

This project involves analyzing a given dataset to predict energy consumption using machine learning techniques. Two models have been implemented—**Linear Regression** and **Random Forest Regression**—to evaluate and compare their performance.

## Project Structure

```
├── datasets/
│   ├── train_energy_data.csv
│   ├── test_energy_data.csv
├── notebook/
│   ├── analysis.ipynb
│   ├── analysis_random_forest.ipynb
├── requirements.txt
```

* `datasets/` contains the training and testing data used for model building and evaluation.
* `notebook/` holds two Jupyter notebooks:

  * `analysis.ipynb`: Contains the implementation using Linear Regression.
  * `analysis_random_forest.ipynb`: Contains the implementation using Random Forest Regression.
* `requirements.txt` lists all Python dependencies required to run the notebooks.

## Objective

The primary objective is to predict energy consumption values based on various features provided in the dataset. By training and comparing different regression models, we aim to understand which model performs better for this dataset and why.

## Algorithms Implemented

### 1. Linear Regression

* File: `analysis.ipynb`
* Achieved accuracy: 98.58%

### 2. Random Forest Regressor

* File: `analysis_random_forest.ipynb`
* Achieved accuracy: 94.32%

## Getting Started

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run the Notebooks

1. Open `analysis.ipynb` to explore Linear Regression results.
2. Open `analysis_random_forest.ipynb` to explore Random Forest results.

Each notebook walks through data loading, preprocessing, model training, evaluation, and result visualization.

## Note

The original dataset ZIP file is excluded from the repository to maintain a cleaner structure. Place extracted dataset files in the `datasets/` directory for the notebooks to function properly.

## License

This project is intended for academic and learning purposes.

