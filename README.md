# 🧠 Disease Diagnosis from Symptoms using NLP

This project uses Natural Language Processing (NLP) and machine learning to **predict diseases based on symptoms** written in plain English.
The model is trained on real-world symptom-disease mappings and can be used for early health screening or integrated into a chatbot.

---

## 🚀 Features

- 🔍 Input: Free-form symptoms in natural language (e.g., "I have fever and joint pain")
- 🎯 Output: Predicted disease (e.g., "dengue")
- 🧠 NLP with TF-IDF vectorization
- 🌲 Machine learning with RandomForestClassifier
- 🧪 Trained on HuggingFace's [Symptom2Disease](https://huggingface.co/datasets/Symptom2Disease)
---

## 🔧 Technologies Used
- Python 🐍
- Scikit-learn
- Pandas
- TF-IDF Vectorizer
- Random Forest Classifier
- Google Colab
---

## How to Run This Project
### Step 1: Clone the repository or upload the files
git clone https://github.com/your-username/disease-diagnosis-nlp.git cd disease-diagnosis-nlp
Or manually upload the files to [Google Colab](https://colab.research.google.com/).

### Step 2: Install dependencies

```bash
pip install -r requirements.txt

Step 3: Run the notebook
Open disease_predictor.ipynb
Run all cells
---

# Example Prediction
Input:
I have fever and joint pain
Output:
dengue

📁 Files Included
disease_predictor.ipynb – Jupyter notebook with full pipeline
train.jsonl – Training dataset
model/ – (Optional) Saved model directory
requirements.txt – List of Python libraries
README.md – This file
---

💡 Future Improvements

Add a Streamlit web app interface
Add more diseases and symptoms
Support other languages
Improve model accuracy with deep learning
---

📜 License

This project is open-source under the MIT License.
---

### What to Do Next

1. Save this as `README.md` in your project folder (or overwrite the old one).
2. Push or upload it to GitHub with your notebook and files.
3. Let me know if you want a **Streamlit web version** or a **chatbot** next!
