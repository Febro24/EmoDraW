# ✨ EmoDraw - Draw in the Air with Your Hand!

EmoDraw is an AI-powered system that lets you draw objects like a **tree**, **mountain**, or **star** using just your fingers in the air. It uses your webcam to track your hand, lets you draw virtually, and then predicts what you've drawn using a custom-trained CNN model. Once recognized, it shows a matching image or animation.

---

## 🔧 How It Works

1. Show your hand to the webcam.
2. Pinch your **index finger** and **thumb** to start drawing on the screen.
3. The model captures and predicts your drawing.
4. If recognized, it displays a visual output (like a 🌲 tree, ⛰️ mountain, ⭐ star, etc.).

---

## 🧠 Model Info

- **Model**: CNN trained on hand-drawn images (webcam-based)
- **Training Accuracy**: 100%
- **Validation Accuracy**: 73.3%
- **Dataset**: Self-created and augmented (~40 images per label)

---

## 🚫 Limitations

- ✅ **Tree**, **Mountain**, and **Star** are predicted accurately most of the time.
- ⚠️ Other classes (like **Bird**, **Butterfly**, etc.) are not consistent and may fail.
- 📸 Hand tracking is currently done using **MediaPipe**, which is not always stable or precise for complex gestures.


## 📦 Tech Stack

- Python
- OpenCV
- MediaPipe (to be replaced by Wilor)
- TensorFlow / Keras
- NumPy



