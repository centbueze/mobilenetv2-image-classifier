# 🐱🐶 Cat vs Dog Classification with MobileNet

This project demonstrates **image classification** using **MobileNetV2** to distinguish between **cats** and **dogs**.  
The model is lightweight, fast, and optimized for deployment on edge devices or web apps.  

---

## 📌 Project Overview
- 📂 **Dataset**: [Kaggle Cats and Dogs Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)  
- 🧠 **Model**: Pretrained **MobileNetV2** (transfer learning)  
- 🎯 **Task**: Binary classification (**Cat** vs **Dog**)  
- 🌍 **Deployment**: Flask / Streamlit Web App  

---

## 📂 Repository Structure
```bash
cat-dog-classifier/
│── dataset/            # Training & validation images
│── models/             # Saved models (mobilenet_catdog.h5)
│── notebooks/          # Jupyter notebooks for training & experiments
│── app.py              # Flask/Streamlit app for prediction
│── train.py            # Training script
│── requirements.txt    # Python dependencies
│── README.md           # Project documentation

---

## ⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/your-username/cat-dog-classifier.git
cd cat-dog-classifier

2️⃣ Create & Activate Virtual Environment
python -m venv venv
.\venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

---

## 📜 requirements.txt (minimal)
tensorflow
flask
opencv-python
numpy
matplotlib

---

## 🚀 Training the Model
python t_learning.ipyng  

---

## 🖼️ Using the Model
app.py 

---

## 🌐Open in Browser
Open in Browser 

---

## 📊 Training Results
Accuracy: ~95% on validation set

Loss: ~0.15 after 10 epochs

📈 (Add a graph here showing training vs validation accuracy/loss) 

---

## 🔧 Troubleshooting
ModuleNotFoundError: No module named 'tensorflow' → Install requirements inside virtual env.

Low accuracy → Ensure dataset is balanced (equal cats & dogs).

---

## 🙏 Acknowledgements
Kaggle Dogs vs Cats Dataset 

---



