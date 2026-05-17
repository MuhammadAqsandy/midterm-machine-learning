# 🖼️ Midterm Machine Learning — Image Classification

> End-to-end Machine Learning pipeline for Image Classification  
> UTS (Midterm) Individual Task — Hands-On End-to-End Models

---

## 📌 Purpose of This Repository

This repository contains the complete implementation of an end-to-end **Machine Learning pipeline** for an **Image Classification** task, submitted as part of the UTS (Midterm) assignment for the **Machine Learning** class.

The project demonstrates practical skills in data preprocessing, feature engineering, model training, hyperparameter tuning, evaluation, and experiment tracking.

---

## 📂 Project Overview

This project builds a comprehensive image classification pipeline using traditional Machine Learning approaches. The workflow covers:

- **Data Preprocessing** — image resizing, normalization, and augmentation
- **Feature Engineering** — feature extraction from images (e.g., HOG, pixel flattening, or CNN-based embeddings)
- **Model Selection** — comparison of multiple ML classifiers (e.g., SVM, Random Forest, KNN, Logistic Regression)
- **Hyperparameter Tuning** — using **Optuna** for automated hyperparameter optimization
- **Evaluation** — using metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
- **Experiment Tracking** — using **MLflow** to track parameters, metrics, and model artifacts

---

## 🧠 Models Used

| Model | Description |
|---|---|
| Support Vector Machine (SVM) | Kernel-based classifier, effective for high-dimensional feature spaces |
| Random Forest | Ensemble of decision trees, robust to overfitting |
| K-Nearest Neighbors (KNN) | Instance-based learning using distance metrics |
| Logistic Regression | Baseline linear classifier for multi-class classification |

### 📊 Evaluation Metrics

| Metric | Description |
|---|---|
| Accuracy | Overall correctness of the model |
| Precision | Ratio of true positives to predicted positives |
| Recall | Ratio of true positives to actual positives |
| F1-Score | Harmonic mean of Precision and Recall |
| Confusion Matrix | Visual breakdown of prediction results per class |

---

## 🗂️ Repository Structure

```
midterm-machine-learning/
│
├── data/
│   ├── raw/                  # Original dataset
│   └── processed/            # Preprocessed images and features
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb     # Data loading, cleaning, and preprocessing
│   ├── 02_feature_engineering.ipynb    # Feature extraction from images
│   ├── 03_model_training.ipynb         # Model training and comparison
│   ├── 04_hyperparameter_tuning.ipynb  # Optuna-based hyperparameter optimization
│   ├── 05_evaluation.ipynb             # Model evaluation and metrics
│   └── 06_mlflow_tracking.ipynb        # Experiment tracking with MLflow
│
├── models/
│   └── best_model.pkl        # Saved best-performing model
│
├── mlruns/                   # MLflow experiment logs
│
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## 🚀 How to Navigate This Repository

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/midterm-machine-learning.git
cd midterm-machine-learning
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebooks in Order
Open Jupyter Notebook and run each notebook sequentially:
```bash
jupyter notebook
```
Start from `01_data_preprocessing.ipynb` and proceed step by step.

### 4. View MLflow Experiments
```bash
mlflow ui
```
Then open your browser at `http://localhost:5000` to explore tracked experiments.

---

## 🔧 Dependencies

Main libraries used in this project:

- `scikit-learn` — ML models and evaluation
- `optuna` — hyperparameter tuning
- `mlflow` — experiment tracking
- `opencv-python` / `Pillow` — image processing
- `numpy`, `pandas` — data manipulation
- `matplotlib`, `seaborn` — visualization
- `scikit-image` — feature extraction (HOG, etc.)

Install all at once:
```bash
pip install -r requirements.txt
```

---

## 👤 Author / Identification

| Field | Info |
|---|---|
| **Name** | Muhammad Aqsandy J Iskandar |
| **Class** | Machine Learning — TK-46-02 |
| **NIM** | 1103220214 |
| **Institution** | Telkom University |

---

## 📝 Notes

- All preprocessing, training, and evaluation steps are documented with comments inside each notebook.
- Hyperparameter tuning was performed using **Optuna** with `n_trials=50` (adjustable).
- All experiment runs including parameters, metrics, and model artifacts are tracked via **MLflow**.

---

*Generated for UTS Midterm — Machine Learning Individual Task*

Class Machine Learning — TK-46-02 
NIM 1103220214 
Institution Telkom University[README.md](https://github.com/user-attachments/files/27891453/README.md)
