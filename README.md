# Cross-Lingual-NER-for-Assamese-The-A-LINC-Approach

This project presents a comparative study of **Named Entity Recognition (NER)** techniques for **Assamese**, focusing on the performance difference between:

1. **Baseline Monolingual Training** — a model trained purely on tokenized Assamese dataset, and  
2. **Cross-Lingual Transfer Learning (A-LINC Approach)** — leveraging multilingual models ( XLM-RoBERTa) pre-trained on high-resource languages to improve performance for low-resource Assamese.

---

## Project Overview

NER (Named Entity Recognition) identifies entities such as **names of people, organizations, locations, and miscellaneous terms** in text.  
While high-resource languages like English and Hindi have abundant data, **Assamese** has limited annotated corpora, creating a challenge for training high-performing models.

This project addresses that by comparing:
- a **standard Assamese-trained model** (baseline), and  
- a **cross-lingual model** using multilingual embeddings and transfer learning.  

The approach aims to show how multilingual models can compensate for the lack of Assamese training data.

---

## Objectives

- Develop a **baseline Assamese NER model** using direct tokenization and supervised training.  
- Implement a **Cross-Lingual Transfer NER** using multilingual transformer models.  
- Compare both models based on precision, recall, and F1-score.  
- Analyze the effect of tokenization, transfer learning, and model architecture on low-resource NER.

---

##  Key Features

- Assamese dataset preprocessing and tokenization (with IndicNLP)
- Comparison between monolingual and multilingual training strategies
- Fine-tuning transformer-based models ( `XLM-RoBERTa`)
- Performance evaluation on entity-level metrics (Precision, Recall, F1)
- Visualization of entity predictions and label distribution
- End-to-end Colab notebook with all experiments

---


