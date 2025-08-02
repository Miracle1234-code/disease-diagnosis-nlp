
# 🧠 Disease Diagnosis from Symptoms

This project uses NLP and machine learning to predict diseases based on symptoms written in plain text.

## 🔧 Technologies Used
- TF-IDF for text vectorization
- RandomForestClassifier for prediction
- Dataset from HuggingFace (Symptom2Disease)

## 🧪 Example

**Input:**
I have fever and joint pain

**Output:**
dengue

## 🚀 How to Run

Use the following command to install requirements:

    pip install -r requirements.txt

Then run the notebook:

    disease_predictor.ipynb

## 📁 Files
- `train.jsonl` — Dataset
- `disease_predictor.ipynb` — Main notebook
- `model/` — Folder containing saved model files
