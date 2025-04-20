#  Chest X-ray Classification: Pneumonia vs. Normal (Deep Learning with Grad-CAM)

![image](https://github.com/user-attachments/assets/eb0373ca-2bd8-4018-aab1-eab78ba0827c)


A deep learning project built to classify chest X-ray images into **PNEUMONIA** or **NORMAL** classes. The solution leverages a **Convolutional Neural Network (CNN)** architecture for classification and uses **Grad-CAM** for model explainability. This project showcases how AI can support medical diagnostics with high accuracy and transparency.

---

## 📂 Dataset Structure

Dataset used: [Kaggle Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

```
chest_xray/
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
├── val/
│   ├── NORMAL/
│   └── PNEUMONIA/
└── test/
    ├── NORMAL/
    └── PNEUMONIA/
```

- Each subfolder contains raw chest X-ray images in `.jpeg` format.

---

## ⚙️ Stack & Frameworks

- **Python 3.8+**
- **Torch**
- **Torchvision**
- **OpenCV** for image handling
- **Matplotlib** for visualizations
- **Scikit-learn** for evaluation metrics
- **Grad-CAM** for model interpretability

---

## 🚀 Features

- 📈 High-accuracy CNN-based image classification
- ✅ Precision, Recall, F1-Score based performance evaluation
- 🧠 Grad-CAM integration for visual explanation of model decisions
- 📊 Support for dynamic batch validation from folders
- 🧪 Tested on validation images from both classes for real-world verification

---

## ✅ Model Performance (Validation Set)

| Metric      | NORMAL | PNEUMONIA | Avg |
|-------------|--------|-----------|-----|
| Precision   | 1.00   | 0.89      | 0.94 |
| Recall      | 0.88   | 1.00      | 0.94 |
| F1-Score    | 0.93   | 0.94      | 0.94 |
| **Accuracy**|        |           | **0.94** |

![image](https://github.com/user-attachments/assets/76943a26-f542-43a2-9102-de5bb73c41f0)


![image](https://github.com/user-attachments/assets/51aaa176-8ca1-46fd-982a-2a6bd314c74d)


> Final model shows high generalization with minimal false positives/negatives.

## 📈 Possible Enhancements

- ✅ Add GUI using Flask or Streamlit for drag-drop predictions
- ✅ Deploy model on Hugging Face Spaces or AWS SageMaker
- ✅ Incorporate mobile support (TF Lite)
- ✅ Explore ensemble or transformer-based backbones (e.g., ViT)

---

## 💡 Real-World Impact

> This model can assist radiologists in preliminary screening for pneumonia using chest X-rays, potentially accelerating diagnosis and treatment.

