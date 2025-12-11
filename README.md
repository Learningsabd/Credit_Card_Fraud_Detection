# Credit Card Fraud Detection 

This project implemetnts Machine Learning techniques to detect fraudulent credit card transactions. Fraud detection is a highly imbalanced classification problem, where fraudulent cases are rare compared to legitimate ones. The goal is to build a reproducible workflow that chieves high precision and recall while minimizing false positives. It is built using Python and popular ML libraries, and aims to demonstrate how data preprocessing, model training, and evaluation can be applied to real-world financial datasets.

##  Project Structure

- `data/` – Contains the dataset (e.g., `creditcard.csv`)
- `notebooks/` – Google Colaboratory notebooks for exploration and modeling
- `models/` – Saved models and evaluation metrics
- `README.md` – Project overview and instructions

##  Key Highlights
- Tackled **imbalanced data** using SMOTE and class weights.  
- Compared **Logistic Regression** and **Random Forest** models.  
- Achieved **ROC‑AUC of 92.45%** with balanced precision and recall (~91%).  
- Created **visualizations** (Confusion Matrix, ROC, PR curves) for easy interpretation.  

##  Tech Stack
- Python (Colab/Jupyter)  
- Pandas, NumPy, Scikit‑learn  
- Matplotlib, Seaborn  

##  Results Snapshot
| Metric      | Best Model |
|-------------|------------|
| Accuracy    | 99.95%     |
| ROC‑AUC     | 92.45%     |
| Precision   | 91%        |
| Recall      | 91%        |

##  Structure
- `data/` – Dataset (e.g., `creditcard.csv`)  
- `notebooks/` – Step‑by‑step ML pipeline  
- `models/` – Saved models and metrics  
- `README.md` – Project overview


##  Future Directions
- Explore **deep learning autoencoders** for anomaly detection.  
- Deploy as a **REST API** for real‑time fraud detection.  
- Benchmark standardized vs non‑standardized pipelines.  
