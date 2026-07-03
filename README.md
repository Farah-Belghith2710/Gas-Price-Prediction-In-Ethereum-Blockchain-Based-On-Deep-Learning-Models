# Ethereum Gas Price Prediction using Hybrid Deep Learning Models

An advanced time-series and deep learning framework designed to forecast Ethereum blockchain transaction fees. This repository leverages a hybrid modeling architecture to optimize predictive performance by combining classical statistical forecasting with neural networks.

---

## Key Features
* **Hybrid Architecture**: Combines an Autoregressive Integrated Moving Average (ARIMA) model with a Multi-Layer Perceptron (MLP) network to capture both linear and non-linear patterns in transaction fees.
* **Optimized Pipeline**: Completely cleaned and structured data pipeline tracking transaction history variations.
* **Production Ready**: Avoids heavy raw data version control issues by utilizing preprocessed data streams optimized for quick loading and efficient training.

---

## Project Structure
* `final code mlp+arima, fee price prediction.ipynb`: Core Jupyter notebook containing data preprocessing, exploratory data analysis, model training, evaluation metrics, and visualizations.
* `dataset_done_chunk1_57H_cleaned_preprocessed.csv`: Cleaned, lightweight, preprocessed time-series dataset engineered for model evaluation.
* `.gitignore`: Built-in safety filters to exclude heavy raw data files from repository memory.

---

## Tech Stack
* **Language**: Python
* **Libraries**: PyTorch/TensorFlow, Scikit-Learn, Pandas, NumPy, Statsmodels
