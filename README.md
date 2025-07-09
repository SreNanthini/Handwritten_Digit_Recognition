# 🧠 Handwritten Digit Recognition using CNN

This is a machine learning project where I built a **Convolutional Neural Network (CNN)** using the **MNIST dataset** to recognize handwritten digits from 0 to 9. The trained model is integrated into a **Tkinter GUI**, where users can draw a digit with their mouse and get real-time predictions!

---

## 📌 Project Overview

- **Goal:** Recognize handwritten digits drawn by the user.
- **Model:** CNN built using TensorFlow/Keras.
- **GUI:** Built with Tkinter for real-time drawing and prediction.
- **Accuracy:** ~99% on test data (MNIST).

---

## 🗂️ Project Files

| File | Description |
|------|-------------|
| `app.py` | Tkinter GUI to draw and predict digits |
| `digit_model_v1.keras` | Trained CNN model (saved format) |
| `digrecog(1).ipynb` | Jupyter notebook for training the model |
| `README.md` | This file |

---

## 📊 Model Architecture

- `Conv2D(32)` + MaxPooling  
- `Conv2D(64)` + MaxPooling  
- `Flatten`  
- `Dense(128)` with ReLU  
- `Dense(10)` with Softmax (for 0–9 prediction)

---

## 🧪 Accuracy Achieved

| Metric | Value |
|--------|-------|
| Validation Accuracy | 99.01% |
| Test Accuracy       | 99.01% |

---

## 🖼️ How the App Works

1. Run the `app.py` script:
   ```bash
   python app.py
   ```

2. A GUI window opens where you can **draw a digit** using the mouse.
3. Click **"Predict"** to see what digit the AI thinks you wrote.
4. Click **"Clear"** to draw a new digit.

---

## 🛠 Requirements

Install the required libraries using pip:

```bash
pip install tensorflow pillow numpy tkinter
```

---

## 🤖 Dataset Used

- MNIST Handwritten Digits Dataset
- 60,000 training samples and 10,000 testing samples
- 28x28 grayscale images of handwritten digits

---

## 🎯 Future Improvements

- Add drawing smoothing for better input quality
- Host the app with Streamlit or Gradio for web version
- Extend to recognize letters (EMNIST dataset)

---

## 🙌 Acknowledgments

- Part of **RISE Internship** by Tamizhan Skills – June 2025 batch.

