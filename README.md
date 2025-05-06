# 🧠 We Speak: Real-Time Indian Sign Language Recognition

**We Speak** is a real-time sign language interpretation system focused on **Indian Sign Language (ISL)**, capable of recognizing both individual **letters** and **dynamic gestures**. The system leverages computer vision, machine learning, and deep learning to interpret sign language from webcam input and provide voice feedback.

---

## ✨ Key Features

- 🖐️ **Hand Tracking** with [MediaPipe](https://github.com/google/mediapipe)
- 🔤 **ISL Letter Recognition** using a **Random Forest classifier**
- 🤲 **Gesture Sequence Classification** using a **Recurrent Neural Network (LSTM)**
- 🔊 **Text-to-Speech** output for spoken feedback
- 🖼️ **User Interface** built with `tkinter`
- 💻 Runs entirely offline after setup

---

## 📦 Technologies Used

| Component              | Technology           |
|------------------------|----------------------|
| Hand detection         | MediaPipe Hands + cvzone |
| Static gesture model   | RandomForestClassifier (scikit-learn) |
| Dynamic gesture model  | LSTM (TensorFlow/Keras) |
| Voice feedback         | pyttsx3 (offline TTS) |
| GUI                    | tkinter + PIL        |
| Audio control (Windows)| pycaw + comtypes     |

---

## 🔧 Setup Instructions

### 1. Clone the Repository
### 2. Unzip the weights folder into the root directroy (or in directory with the GUI_Window.py).

```bash
git clone https://github.com/your-username/we-speak.git
cd we-speak
