# Medical-Department-Classifier
# 🏥 Medical Department Classifier

**Natural Language Processing | Healthcare AI | Transformers**

This project builds a robust NLP pipeline to classify medical questions into 20+ departments such as **Neurology**, **Cardiology**, **Oncology**, and more — leveraging domain-specific models and healthcare datasets.

---

## 🚀 Overview

Using the **MedQuAD** dataset (a collection of medical question-answer pairs), this project processes and classifies medical questions into their respective departments.

Key components of the pipeline:

-  **XML Parsing** of QA pairs from the MedQuAD dataset.
-  **Text Preprocessing** using **SciSpaCy**:
  - Named Entity Recognition (NER)
  - Lemmatization
  - Stopword removal
-  **Vectorization** using TF-IDF
-  **Multi-class Classification** using **BioBERT** (fine-tuned via Hugging Face Transformers)
-  **Label Encoding** and performance evaluation with classification reports and visualizations

---

##  Tech Stack

- **SciSpaCy** – Biomedical text preprocessing
- **BioBERT** – Domain-specific language model for biomedical classification
- **Hugging Face Transformers** – Fine-tuning and training
- **Scikit-learn** – Vectorization, LabelEncoder, evaluation metrics
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Performance visualization

---

##  Files

- `health_identity_classifier.ipynb` – Main Jupyter notebook with full code pipeline

---

##  Results

Achieved high classification accuracy across 20+ medical departments with a well-structured NLP pipeline and domain-adapted model.

---

## ⚙ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Rudransh-1508/Medical-Department-Classifier.git
   cd Medical-Department-Classifier
   pip install -r requirements.txt
   jupyter notebook health_identity_classifier.ipynb


