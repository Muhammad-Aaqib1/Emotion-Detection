## 😃 Real-Time Emotion Detection

This is a Python-based real-time face emotion detection system using OpenCV. It detects human faces from webcam input and labels them with an emotion. Currently, it uses a simulated random prediction method (model integration is planned in the next phase).

---

### 📂 Project Structure

```
emotion-detector/
├── dataset/
│   ├── train/
│   │   ├── Angry/
│   │   ├── Happy/
│   │   └── ... (7 classes)
│   └── test/
│       └── ... (same 7 classes)
├── haarcascade/
│   └── haarcascade_frontalface_default.xml
├── emotion_detector.py
├── README.md
```

---

### 🔧 Requirements

Install dependencies using:
```bash
pip install opencv-python
```

---

### 🚀 How to Run

Make sure your webcam is connected. Then run:

```bash
python emotion_detector.py
```

A window will open showing the webcam feed with detected faces labeled with simulated emotion names.

---

### 🧠 Emotions Included

- Happy
- Sad
- Angry
- Disgust
- Fear
- Neutral
- Surprise

---

### 🎯 Current Progress

- ✅ Dataset organized
- ✅ Face detection working
- ✅ Real-time webcam feed
- ⚠️ Emotion prediction is mocked using `random.choice()` for now
- 🔜 Next: Train CNN model for real emotion detection

---

### 👨‍💻 Author

**Muhammad Aaqib**

B.S. Computer Science  
Sukkur IBA University (Kandhkot Campus)

---
