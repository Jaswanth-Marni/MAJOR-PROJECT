# ChronoMind
### Neuro-Symbolic Narrative Coherence Verification Framework

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-green)

---

# 📌 Overview

ChronoMind is a neuro-symbolic AI framework developed for automated narrative coherence evaluation. The system analyzes stories and narrative text to detect logical inconsistencies, temporal conflicts, contextual contradictions, and stylistic irregularities.

Unlike traditional NLP systems that mainly operate at sentence level, ChronoMind performs document-level analysis using transformer-based contextual learning, symbolic reasoning, and tone analysis.

The framework combines neural and symbolic AI techniques to provide accurate and interpretable narrative verification.

---

# 🚀 Project Highlights

- Document-level narrative coherence analysis
- Transformer + symbolic hybrid AI framework
- Logical and temporal inconsistency detection
- Tone-aware narrative understanding
- Interactive Streamlit-based web application
- Weighted fusion decision mechanism
- Achieved **97.41% Accuracy** and **0.994 ROC-AUC**

---

# ✨ Features

- Narrative coherence classification
- Logical contradiction detection
- Temporal consistency verification
- Tone and sentiment analysis
- Neuro-symbolic reasoning pipeline
- Visualization dashboard
- Real-time analysis reports
- Interactive UI for narrative evaluation

---

# 🧠 Technologies Used

## Machine Learning & AI
- RoBERTa-base
- PyTorch
- Hugging Face Transformers
- Transformer-based Deep Learning
- Self-Attention Mechanism
- Supervised Learning

## NLP Libraries
- spaCy
- NLTK
- RoBERTa Tokenizer
- VADER Sentiment Analyzer

## Symbolic Reasoning
- Z3 Solver
- Rule-Based NLP Engine

## Data Processing
- NumPy
- Pandas

## Visualization
- Plotly
- Matplotlib
- Scikit-learn

## Frontend
- Streamlit

## Database
- SQLite3

## Development Tools
- Python 3.x
- Jupyter Notebook
- VS Code
- Google Colab

---

# 🏗️ System Architecture

The ChronoMind pipeline works as follows:

```text
Input Narrative
      ↓
Preprocessing
      ↓
RoBERTa Neural Analysis
      ↓
Symbolic Reasoning
      ↓
Tone Analysis
      ↓
Weighted Fusion
      ↓
Final Coherence Decision
```

---

# ⚙️ Models Used

## 1. RoBERTa-Based Transformer Model
Used for:
- Contextual understanding
- Narrative coherence classification
- Semantic relationship extraction

### Model Details
- 125 Million Parameters
- 12 Transformer Layers
- Self-Attention Architecture
- Fine-tuned on narrative datasets

---

## 2. Symbolic Reasoning Module
Used for:
- Event sequence validation
- Logical consistency checking
- Temporal relationship analysis
- Contradiction detection

---

## 3. Tone Analysis Module
Used for:
- Sentiment analysis
- Sarcasm detection
- Tone interpretation
- Stylistic analysis

Implemented using:
- VADER Sentiment Analyzer

---

# 📂 Dataset Information

- Structured narrative dataset
- Approximately **101,307 narrative segments**
- Coherent and incoherent narrative classes
- Multi-year narrative corpus

## Dataset Split
- Training Set
- Validation Set
- Testing Set

---

# 🧹 Preprocessing Steps

- Text cleaning
- Sentence segmentation
- Tokenization
- Text normalization
- Transformer token generation
- Sequence padding and truncation

Libraries used:
- spaCy
- NLTK
- RoBERTa Tokenizer

---

# 🔥 Weighted Fusion Mechanism

Final prediction is generated using weighted fusion:

```text
Final Score =
0.50 × Neural Score +
0.30 × Symbolic Score +
0.20 × Tone Score
```

This improves:
- Reliability
- Interpretability
- Contextual understanding
- Logical validation

---

# 📊 Results & Performance

| Metric | Value |
|---|---|
| Accuracy | 97.41% |
| Precision | 97%+ |
| Recall | 97%+ |
| F1-Score | 0.9745 |
| ROC-AUC | 0.994 |

---

# 📈 Evaluation Techniques

- Confusion Matrix
- ROC Curve
- Training Loss Curve
- Accuracy Curve
- Classification Report

---

# 💡 Novelty of the Project

ChronoMind introduces a hybrid neuro-symbolic framework that combines:
- Transformer-based contextual learning
- Symbolic logical reasoning
- Tone and stylistic analysis

Unlike traditional sentence-level NLP systems, ChronoMind performs document-level narrative coherence evaluation.

---

# 🌍 Applications

- Intelligent writing assistants
- Educational content analysis
- Automated storytelling evaluation
- Narrative quality assessment
- AI-based content moderation
- Computational linguistics research

---

# ⚠️ Limitations

- Computationally intensive for large narratives
- Performance depends on dataset diversity
- Symbolic reasoning rules can be expanded further

---

# 🔮 Future Enhancements

- Multilingual narrative analysis
- Explainable AI integration
- Cloud deployment support
- Advanced event graph reasoning
- Multimodal storytelling analysis
- Adaptive reinforcement learning

---

# 🖥️ Installation & Setup

## Step 1: Clone Repository

```bash
git clone <repository-link>
cd ChronoMind
```

## Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

## Step 3: Run Streamlit Application

```bash
streamlit run app.py
```

## Step 4: Open Application

Go to:

```text
http://localhost:8501
```

---

# 📌 Usage

1. Upload or paste narrative text
2. Run coherence analysis
3. View:
   - Final coherence verdict
   - Fusion score
   - Neural score
   - Symbolic reasoning score
   - Tone analysis
4. Explore visualizations and evaluation reports

---

# 📸 Suggested Screenshots

Add these images to improve repository presentation:
- System architecture diagram
- Streamlit UI screenshot
- Confusion matrix
- ROC curve
- Sample output report

---

# 🧪 Evaluation Metrics

The project is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

---

# 📜 Research Contribution

This project contributes to:
- Narrative intelligence research
- Neuro-symbolic AI systems
- Document-level NLP analysis
- Automated coherence verification

---

# 👨‍💻 Authors

ChronoMind Project Team  
Department of Computer Science & Engineering

---

# 📄 Research Paper

**ChronoMind: A Neural Framework for Logical and Temporal Consistency Verification in Short Stories**

---

# ⭐ Final Note

ChronoMind demonstrates how transformer-based deep learning, symbolic reasoning, and tone analysis can be integrated into a unified framework for intelligent narrative understanding and automated coherence evaluation.
