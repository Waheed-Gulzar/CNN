# 🧠 Sign Language Digit Classification 

This project uses a **Convolutional Neural Network (CNN)** to classify hand signs representing digits (0–9) from images. It includes preprocessing, data augmentation, model training, evaluation, and visualization of results.

---

## 🧩 Model Architecture

* **Conv2D → MaxPooling → Dropout**
* **Conv2D → MaxPooling → Dropout**
* **Flatten → Dense(128, ReLU, L2) → Dropout → Dense(10, Softmax)**
---

## 🚀 How to Run

```bash
git clone https://github.com/<your-username>/SignLanguageDigits.git
cd SignLanguageDigits
python model.py
```

Make sure your dataset path in the script matches your local directory.
You can check how the different Hyperparameter affected the training in the report.
---
