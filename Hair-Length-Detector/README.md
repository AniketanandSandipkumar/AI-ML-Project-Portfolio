# 🧓 Senior Citizen Detection System

## 📌 Overview

This project is an AI-powered web application that detects **age group, gender, and senior citizen status** from an uploaded image.

It uses **Deep Learning (CNN models)** along with **Computer Vision (OpenCV)** for face detection and classification, and is deployed using **Streamlit** for an interactive UI.

---

## 🚀 Features

* 📷 Upload image support (JPG, JPEG, PNG)
* 🧠 Face detection using Haar Cascade
* 👤 Gender classification (Male/Female)
* 🎂 Age group prediction (0–20, 21–30, 31–60, 60+)
* 🧓 Senior citizen detection (60+)
* ⚡ Fast and real-time predictions

---

🧠 Model Details

* **Age Model**

  * Type: Multi-class Classification (4 classes)
  * Output: Age group prediction

* **Gender Model**

  * Type: Binary Classification
  * Output: Male / Female

* **Face Detection**

  * Method: OpenCV Haar Cascade Classifier

---

🛠️ Tech Stack

* Python
* Streamlit
* TensorFlow / Keras
* OpenCV
* NumPy

---

📂 Project Structure

```
.
├── app.py
├── face_age.h5
├── face_gender.h5
├── requirements.txt
└── README.md
```

---

▶️ Run Locally

```bash
git clone <your-repo-link>
cd Senior-Citizen-Detection
pip install -r requirements.txt
streamlit run app.py
```

---

🌐 Live Demo

👉 [https://senior-citizen-detection-aguaghvgnfnaywcu3gmhex.streamlit.app]

---

⚠️ Limitations

* Requires clear frontal face for accurate detection
* Performance may vary with low lighting or blurry images
* Works best with single-face images

---

👨‍💻 Author

**Aniketanand Sandipkumar**

---

⭐ If you like this project, consider giving it a star!
