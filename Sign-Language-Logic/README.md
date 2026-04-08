# 🤟 Sign Language Detection System

A lightweight, rule-based **Sign Language Detection Web App** built using **Streamlit**.  
This project demonstrates gesture classification logic using basic image processing techniques.

---

## 🚀 Live Demo
🔗 [Click here to try the app](https://sign-language-logic-bmx4hwrn4unijxk7zdfzsf.streamlit.app)

---

## 📌 Features

- ⏰ **Time-Restricted Access (6 PM – 10 PM)**
- 🖼️ Upload hand gesture images
- 🤟 Predicts sign labels (A, B, C, D, E)
- 📊 Displays confidence score
- ⚡ Fast and lightweight (No ML model required)

---

## 🧠 How It Works

This is a **rule-based system** (no deep learning model).

The app analyzes:
- 🎨 Average color intensity (RGB values)
- 💡 Brightness of the image

Based on these values:
- Low brightness → Sign **A**
- Medium brightness → Sign **B**
- Green dominant → Sign **D**
- Red dominant → Sign **C**
- Otherwise → Sign **E**

---

## ⚠️ Limitations

- Not a real sign language recognition system
- Uses simple heuristic rules (not trained on datasets)
- Works best with clear hand images
- Time-restricted for demonstration purposes

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **OpenCV**
- **NumPy**

---

## 📂 Project Structure
Sign_Language_Detection/
│
├── app.py
├── requirements.txt
└── README.md


---

## ▶️ Run Locally    

git clone YOUR_REPO_LINK  
cd Sign_Language_Detection  
pip install -r requirements.txt  
streamlit run app.py  

---

🎯 Use Case  
Demonstration of rule-based AI logic  
Beginner-friendly computer vision project  
Academic mini-project / internship submission  

---

👨‍💻 Author  

Aniketanand Sandipkumar  
B.Tech Computer Science | AI/ML Enthusiast  

⭐ If you like this project  

Give it a ⭐ on GitHub and share it!  

---

If you want, next I can:
- Create **one MASTER README** that links all 6 projects 🔥  
- Add **badges + animations + GitHub profile optimization** (this boosts recruiter impact a
