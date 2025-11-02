# 📧 Spam Detection with PySpark

##  Project Overview

This project demonstrates how to build, evaluate, and deploy a **Spam Detection System** using **PySpark MLlib**. It uses two different datasets:

* **Dataset 1:** SMS spam messages (ham/spam)
* **Dataset 2:** YouTube comment spam classification (non-spam/spam)

The workflow covers all major steps of an end-to-end machine learning pipeline, from preprocessing to model deployment using **Gradio**.

---

##  Objectives

* Build scalable text classification models using **Apache Spark**.
* Apply **NLP preprocessing** (tokenization, stopword removal, TF-IDF).
* Train multiple classifiers (Naive Bayes, Random Forest, Logistic Regression).
* Evaluate models using accuracy and F1-score.
* Deploy interactive web apps using **Gradio** for real-time predictions.

---

##  Tech Stack

* **Language:** Python 3
* **Framework:** Apache Spark (PySpark)
* **Libraries:**

  * `pyspark.ml` for MLlib pipeline
  * `matplotlib` and `pandas` for visualization
  * `gradio` for deployment interface

---

##  Step-by-Step Workflow

 **Initialize Spark** – Start a Spark session for distributed data processing.
 **Load and Explore Data** – Read datasets and visualize class balance.
 **Preprocess Text** – Tokenize, remove stopwords, and vectorize using TF-IDF.
 **Split Data** – Divide into training and test sets.
 **Train Models** – Use Naive Bayes, Random Forest, and Logistic Regression.
 **Evaluate Models** – Compare performance using accuracy and F1-score.
 **Deploy Models** – Create Gradio interfaces for Dataset 1 and Dataset 2.

---

##  Visualizations

* Class distribution (Ham vs Spam)
* Most frequent words in each class
* Model accuracy & F1-score comparison charts

---

##  Results Summary

| Dataset                      | Best Model          | Accuracy  | F1-Score  |
| ---------------------------- | ------------------- | --------- | --------- |
| Dataset 1 (SMS Spam)         | Logistic Regression | **0.957** | **0.959** |
| Dataset 2 (YouTube Comments) | Logistic Regression | **0.909** | **0.908** |

Logistic Regression provided the best performance across both datasets, showing its robustness for binary text classification tasks.

---

## 🌐 Gradio Interfaces

Below are example screenshots of the two deployed Gradio interfaces and a sample test result.

### 🖼️ Dataset 1 Interface (SMS Spam Detection)


![Dataset 1 Interface](images/emailspam_interface.png)

### 🖼️ Dataset 2 Interface (YouTube Comment Spam Detection)


![Dataset 2 Interface](images/spamdetector_interface.png)



---

## 👩‍💻 Author

**Developed by:** [Nada Ammar | AI and Data Science Engineer]


