# Job AI Classifier

A web-based application for classifying the level of Artificial Intelligence (AI) exposure of occupations in Indonesia using IndoBERT.

## 📌 Overview

This project is part of my undergraduate thesis:

> **Klasifikasi Pekerjaan di Indonesia yang Terpengaruh oleh Teknologi Artificial Intelligence Berdasarkan Occupational Exposure Score Menggunakan IndoBERT**

The application predicts whether a job belongs to **High AI Exposure** or **Low AI Exposure** based on the job title and job tasks.

## ✨ Features

- Predict AI exposure from job title and job description
- Batch prediction using CSV files
- Highlight AI-related sentences
- Skill analysis visualization
- Prediction history
- Interactive dashboard built with Streamlit

## 🛠️ Technologies

- Python 3.12
- Streamlit
- TensorFlow / Keras
- PyTorch
- Hugging Face Transformers
- IndoBERT
- Scikit-learn
- Pandas
- NumPy
- SpaCy
- Plotly

## 📂 Project Structure

```
Job-AI-Classifier/
│
├── app.py
├── requirements.txt
├── models/
├── results/
├── assets/
├── testing/
├── utils/
└── README.md
```

## 🚀 Installation

Clone the repository

```bash
git clone git@github.com:keyynatwgm/Job-AI-Classifier.git
```

Move into the project

```bash
cd Job-AI-Classifier
```

Create virtual environment

```bash
python -m venv .venv
```

Activate virtual environment

Windows

```bash
.venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

## 📊 Model

- Base Model: IndoBERT (`indobenchmark/indobert-base-p1`)
- Fine-Tuning for binary classification
- Labels:
  - Low AI Exposure
  - High AI Exposure

## 📁 Dataset

The dataset is constructed from:

- KBJI 2014
- O*NET Database
- Google Patents AI Dataset

The labels are generated using the Occupational Exposure Score (OES) methodology.

## 📄 License

This project is intended for academic and research purposes.

## 👤 Author

**Kezia Natalia**

Universitas Sumatera Utara

GitHub: https://github.com/keyynatwgm
