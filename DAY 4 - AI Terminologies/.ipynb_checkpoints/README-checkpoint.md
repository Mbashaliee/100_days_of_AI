# 📘 Day 4: AI Terminology

## 📌 Overview

> This day demystifies key AI/ML terms so learners have a solid vocabulary.  
> We explain what **model**, **training**, **testing**, **inference**, and **features** mean in simple terms.  
> This glossary-style session ensures everyone uses the same language when talking about AI.

---

## 🔑 Core Terminology

- **🧠 Model**  
  A trained program or function that makes predictions or decisions.

- **🎓 Training**  
  The process of teaching the model by feeding it data and adjusting its internal parameters (weights).

- **🧪 Testing (Evaluation)**  
  Measuring a model’s performance on new, unseen data.

- **📊 Inference**  
  Using the trained model to make predictions on new inputs.

- **📥 Features**  
  Input variables or attributes the model uses to make predictions (e.g. age, pixel values).

---

## 🧵 Detailed Explanation and Insights

### 🧠 What is a Model in AI/ML?

> A model is the result of training a learning algorithm on a dataset.  
> It maps input data to output predictions, capturing patterns within the data.

**Examples:**
- A spam detection model classifies emails as `spam` or `not spam`.
- A medical model predicts diseases based on symptoms.

> *“A model is a mathematical framework or algorithm that has been trained to recognize patterns or make decisions based on data.” – FlintK12*

**Types of Models:**
- Linear Regression
- Decision Trees / Random Forests
- Neural Networks
- Support Vector Machines (SVMs)
- Naive Bayes

---

### 🎓 Training the Model

> Training is like studying for a test.  
> The model learns from labeled data to minimize prediction errors.

**Process:**
1. Feed input-output pairs to the model.
2. Use a loss function to measure error.
3. Apply optimization (e.g., gradient descent) to adjust weights.

**Example:**  
Train a model with cat/dog images so it learns to classify them correctly.

**Training ends when:**
- Desired accuracy is reached
- Predefined number of epochs is complete
- Overfitting starts to occur

---

### 🧪 Testing and Evaluation

> Once trained, we test the model on data it hasn't seen before.

**Data Splits:**
- `Training Set` – to learn from
- `Validation Set` – to tune hyperparameters
- `Test Set` – to evaluate performance

**Key Evaluation Metrics:**
- Accuracy
- Precision, Recall, F1-score
- ROC-AUC
- Confusion Matrix

> *“Can this model perform well on data it hasn't seen before?”*

---

### 📊 Inference: Putting the Model to Use

> Inference is using the trained model to predict outcomes from new data.  
> No learning happens at this stage—it's purely application.

**Examples:**
- Voice to text conversion on smartphones
- Real-time fraud detection by banks
- Live translation of spoken language

> *“Inference is the process of feeding a piece of content through a trained model to get a prediction, score, or label.” – Shelf AI Glossary*

---

### 📥 Features: The Inputs That Drive Predictions

> Features are measurable properties or variables used as input for models.

**Examples:**

🏠 *House Price Prediction Model*
- Size (sq ft)
- Number of Bedrooms
- Location
- Year Built

💳 *Loan Approval Model*
- Credit Score
- Annual Income
- Employment Status

🖼 *Image Classifier*
- Pixel values
- Color histograms
- Deep features from CNN layers

> *“An individual measurable property or characteristic within a recorded dataset.” – Domino Data Lab*

**Common Feature Engineering Techniques:**
- Normalization / Scaling
- One-hot Encoding
- Dimensionality Reduction (e.g., PCA)
- Polynomial Feature Expansion

---

## 🧩 Additional Concepts Related to Models

- **⚙️ Hyperparameters**  
  Configuration values (e.g., learning rate, number of layers), set *before* training.

- **📉 Weights**  
  Internal parameters adjusted during training that determine input importance.

- **🎯 Bias vs. Variance**  
  - High **bias** = underfitting  
  - High **variance** = overfitting  
  - 🎯 Goal: balance both

- **🚀 Model Deployment**  
  Making the trained model accessible via APIs, mobile apps, or embedded systems.

---

## 📚 Recommended Resources

- 🔹 [**FlintK12 AI Glossary**](https://flint.global/): Beginner-friendly breakdown of model, training, parameters, and inference.
- 🔹 [**Domino Data Lab: What is a Feature?**](https://www.dominodatalab.com/): Clear definitions and use cases of features.
- 🔹 [**Shelf AI Glossary**](https://shelf.io/): Extensive glossary of AI terms including inference, features, and model evaluation.
- 🔹 [**GeeksforGeeks: Model Evaluation**](https://www.geeksforgeeks.org/): Explains train/test splits and evaluation techniques.
- 🔹 [**Word.Studio AI Glossary**](https://word.studio/): A beginner-oriented glossary covering core AI/ML terms.

---

> _“Understanding AI terminology builds confidence, encourages curiosity, and bridges the gap between beginner and expert.”_

---
