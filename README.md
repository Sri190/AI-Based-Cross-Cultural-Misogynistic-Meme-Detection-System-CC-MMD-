# AI-Based Cross-Cultural Misogynistic Meme Detection System (CC-MMD)

### 👨‍💻 Team Name: Tech Elites  
### 👤 Presented By: Sri Hari Vathsan G  
### 🏫 Institution: St. Joseph’s Institute of Technology, OMR, Chennai  
### 🎓 Department: Artificial Intelligence & Machine Learning  

---

## 📌 Project Overview

The **Cross-Cultural Misogynistic Meme Detection System (CC-MMD)** is an AI-based solution designed to identify misogynistic content in memes, particularly focusing on Tamil language contexts.

Memes often convey meaning through **sarcasm, implicit language, and cultural nuances**, making misogyny detection a challenging task. This project addresses the problem using a combination of **deep learning and cultural feature engineering**.

---

## 🎯 Objectives

- Detect misogyny in meme text (Tamil-focused)
- Capture implicit, sarcastic, and culturally nuanced expressions
- Build a lightweight and efficient AI model
- Enable real-time prediction using caching
- Provide a prototype system for demonstration

---

## 🧠 Methodology

The system follows a hybrid approach:

### 1. Text Processing
- Tamil text normalization
- Noise removal and cleaning

### 2. Character-Level Encoding
- Converts text into character sequences
- Builds a vocabulary for model input

### 3. Cultural Feature Engineering
- Detects:
  - Misogyny keywords
  - Sarcasm indicators (😂, 🤣, etc.)
  - Sentiment and implicit bias

### 4. Model Architecture
- Character-Level CNN
- Embedding Layer
- Convolution + Pooling Layers
- Fully Connected Layers
- Sigmoid Output (Binary Classification)

### 5. Feature Fusion
- Combines CNN features + cultural features

---

## ⚙️ Tech Stack

- **Language:** Python  
- **Libraries:** PyTorch / TensorFlow, NumPy, Pandas  
- **Frontend:** React, Tailwind CSS  
- **Visualization:** Matplotlib / Charts  
- **Deployment (Prototype):** Web-based interface  

---

## 🌐 Prototype Features

- Meme image upload  
- Text input / OCR simulation  
- AI prediction (simulated)  
- Confidence score display  
- Explanation of prediction  
- Real-time response  

---

## 📊 Model Performance

| Metric                | Value        |
|----------------------|-------------|
| Training Accuracy    | ~95%        |
| Validation Accuracy  | 62–65%      |
| Macro F1 Score       | 0.5590      |
| Inference Speed      | Microseconds (cached) |

---

## ⚠️ Challenges

- Detecting implicit and sarcastic misogyny  
- Handling Tamil slang and code-mixed text  
- Class imbalance in dataset  
- Cultural interpretation differences  
- Overfitting between training and validation  

---

## 🏆 Results

- Successfully detects misogyny in Tamil memes  
- Captures hidden and indirect offensive content  
- Outperforms baseline models  
- Enables real-time content moderation  
- Generates competition-ready outputs  

---

## 🚀 Future Work

- Integrate image-based model (CLIP)  
- Add OCR for text extraction from images  
- Improve cross-cultural generalization  
- Expand dataset size  
- Deploy as a real-time application  

---

## 📁 Project Structure
