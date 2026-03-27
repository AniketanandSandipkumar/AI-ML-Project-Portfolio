🌍 Face Attribute Logic Demo (Nationality Detector)

📌 Overview

This project is a **rule-based AI demo application** that analyzes facial images to estimate:

* 🌍 Region (logic-based, not real nationality)
* 🎭 Emotion
* 👕 Dress color

⚠️ **Important Note:**
This is an **educational demonstration project**. It does **NOT determine actual nationality** and should not be used for real-world classification.

---

🚀 Features

* 📷 Upload face image (JPG, JPEG, PNG)
* 🧠 Face detection using OpenCV Haar Cascade
* 🎭 Emotion recognition using Deep Learning model
* 🌍 Region estimation using skin tone logic
* 👕 Dress color detection using pixel analysis
* ⚡ Real-time inference with Streamlit UI

---

🧠 Model & Logic Details

🎭 Emotion Detection

* Model: CNN-based Deep Learning model (`face_emotion.h5`)
* Input: Grayscale face image (48×48)
* Output: One of 7 emotions:

  * Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

🌍 Region Estimation (Logic-Based)

* Based on average brightness (HSV color space)
* Categories:

  * African (Logic-based)
  * Indian (Logic-based)
  * USA (Logic-based)

👕 Dress Color Detection

* Extracts region below face
* Uses average RGB values to classify:

  * Red / Blue / Green / Mixed

---

🛠️ Tech Stack

* Python
* Streamlit
* TensorFlow / Keras
* OpenCV
* NumPy

---

📂 Project Structure

```id="6i9k0n"
.
├── app.py
├── face_emotion.h5
├── requirements.txt
└── README.md
```

---

▶️ Run Locally

```bash id="p4t8dz"
git clone <your-repo-link>
cd Nationality-Detector
pip install -r requirements.txt
streamlit run app.py
```

---

🌐 Live Demo

👉 [https://nationality-detector-ugnp7s8xuvsyyzjdapvv4d.streamlit.app]

---

⚠️ Limitations

* ❌ Not a real nationality detection system
* ⚠️ Based on simplified rules (skin tone & brightness)
* 🎯 Accuracy depends on lighting and image quality
* 👤 Works best with clear frontal face images

---

🎯 Use Case

This project is designed for:

* 📚 Learning Computer Vision concepts
* 🧠 Understanding ML + rule-based hybrid systems
* 💼 Demonstrating logic-building in AI projects

---

👨‍💻 Author

**Aniketanand Sandipkumar**

---

⭐ If you like this project, consider giving it a star!
