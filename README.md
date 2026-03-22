# 🧠 AI Lie Detector (Text Classification)

## 📌 Project Overview

This project is an **AI-powered Lie Detection system** built using **Deep Learning (LSTM)** and deployed with **Streamlit**. It analyzes user-input text and predicts the corresponding class (e.g., truthful or deceptive categories).

The model uses **Natural Language Processing (NLP)** techniques to process and classify text inputs in real time.

---

## 🎯 Objectives

* Build a text classification model using LSTM
* Detect patterns in text to classify statements
* Deploy an interactive web app using Streamlit
* Provide real-time predictions based on user input

---

## 🚀 Features

* 🧾 User-friendly text input interface
* ⚡ Real-time prediction
* 🧠 Deep Learning model (LSTM)
* 🔄 Text preprocessing (cleaning & tokenization)
* 📊 Multi-class classification (6 classes)

---

## 🛠️ Tech Stack

* **Python**
* **TensorFlow / Keras**
* **Streamlit**
* **Scikit-learn**
* **Pickle (for tokenizer & encoder)**

---

## 📂 Project Structure

```
├── app.py                # Streamlit application
├── final_model1.h5       # Trained LSTM model weights
├── tokenizer.pkl        # Tokenizer for text processing
├── encoder.pkl          # Label encoder
├── requirements.txt     # Dependencies
├── runtime.txt          # Python version
```

---

## ⚙️ Model Architecture

* Embedding Layer
* LSTM Layer (64 units)
* Dense Layer (ReLU)
* Output Layer (Softmax – 6 classes)

---

## 🧪 How It Works

1. User enters text in the app
2. Text is cleaned (lowercase, remove special characters)
3. Tokenized and padded
4. Passed to LSTM model
5. Model predicts class
6. Label is decoded and displayed

Example from code: 

---

## ▶️ How to Run Locally

### 1. Clone the repository

```bash
git clone <your-repo-link>
cd your-project-folder
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Dependencies used: 

### 3. Run the app

```bash
streamlit run app.py
```

---

## 🌐 Deployment

You can deploy this app using:

* Streamlit Cloud
* Render
* Hugging Face Spaces

Python version: 

---

## 🔍 Key Highlights

* Real-time NLP application
* End-to-end ML pipeline (training → deployment)
* Lightweight and interactive UI
* Suitable for demonstration of NLP + DL skills

---

## 📌 Future Improvements

* Improve model accuracy with Transformers (BERT)
* Add confidence score visualization
* Expand dataset for better generalization
* Add explainability (why prediction was made)

---

## 👨‍💻 Author

**Santhosh Kumar G**
Aspiring Data Scientist / Data Analyst

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!
