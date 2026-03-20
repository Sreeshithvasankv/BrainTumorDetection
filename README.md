# 🧠 Brain Tumor Detection using Deep Learning

A deep learning-based system to detect and classify brain tumors from 
MRI scan images using Convolutional Neural Networks (CNN).

---

## 🎯 Objective

To build an accurate and efficient deep learning model that can:
- Detect the presence of brain tumors in MRI scans
- Classify tumor types automatically
- Assist medical professionals in early diagnosis

---

## 🌟 Features

- 🔍 Automatic tumor detection from MRI images
- 🏷️ Multi-class tumor classification
- 📊 Training and validation accuracy visualization
- 🖼️ Image preprocessing and augmentation
- 📈 Performance evaluation with confusion matrix

---

## 🛠️ Tech Stack

| Technology      | Purpose                        |
|-----------------|--------------------------------|
| Python 3        | Core programming language      |
| TensorFlow/Keras| Deep learning framework        |
| NumPy           | Numerical computations         |
| Matplotlib      | Data visualization             |
| OpenCV          | Image processing               |
| Scikit-learn    | Model evaluation metrics       |
| Google Colab    | Training environment (GPU)     |

---

## 📁 Project Structure
```
BrainTumorDetection/
├── brain_tumor_detection.ipynb   # Main notebook with full pipeline
├── README.md                     # Project documentation
```

---

## 🧬 Dataset

The model is trained on brain MRI images dataset containing:

| Class | Description |
|-------|-------------|
| Glioma | Type of tumor in brain/spine |
| Meningioma | Tumor in brain membranes |
| Pituitary | Tumor in pituitary gland |
| No Tumor | Healthy brain scan |

---

## 🔄 How It Works
```
MRI Image Input
      │
      ▼
Image Preprocessing
(Resize, Normalize, Augment)
      │
      ▼
CNN Model
(Convolutional Layers)
      │
      ▼
Feature Extraction
      │
      ▼
Classification
(Tumor Type / No Tumor)
      │
      ▼
Result Output
```

---

## 🏗️ Model Architecture
```
Input Layer (MRI Image)
      │
Conv2D + ReLU + MaxPooling
      │
Conv2D + ReLU + MaxPooling
      │
Conv2D + ReLU + MaxPooling
      │
Flatten
      │
Dense + Dropout
      │
Output Layer (Softmax)
```

---

## ⚙️ Setup & Run

### Option 1: Run on Google Colab (Recommended)
1. Open the notebook:
   👉 [Open in Colab](https://colab.research.google.com/drive/1TgYKP0xroPgFgCGJaj8__1WsbXn13xVg)
2. Click **Runtime → Run All**
3. GPU will be used automatically

### Option 2: Run Locally
```bash
# Clone the repo
git clone https://github.com/Sreeshithvasankv/BrainTumorDetection.git
cd BrainTumorDetection

# Install dependencies
pip install tensorflow numpy matplotlib opencv-python scikit-learn

# Open notebook
jupyter notebook brain_tumor_detection.ipynb
```

---

## 📊 Results

| Metric | Score |
|--------|-------|
| Training Accuracy | ~95% |
| Validation Accuracy | ~93% |
| Loss | Low |

> Note: Results may vary based on dataset and hyperparameters.

---

## 📈 Visualizations

The notebook includes:
- ✅ Training vs Validation Accuracy graph
- ✅ Training vs Validation Loss graph
- ✅ Confusion Matrix
- ✅ Sample predictions with labels

---

## 🔮 Future Improvements

- [ ] Deploy as web app using Flask/Streamlit
- [ ] Add more tumor classes
- [ ] Use Transfer Learning (VGG16, ResNet)
- [ ] Real-time MRI scan analysis
- [ ] Mobile app integration

---

## 👨‍💻 Developer

**Sreeshith Vasan KV**  
M.Tech AI & Data Science — 2026  
📧 sreeshithvasankv@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/sreeshith-vasan-k-v-19a8a6278)

---

## 📄 License

MIT License — free to use and modify

---

## 🙏 Acknowledgements

- Dataset: [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- Framework: TensorFlow/Keras
- Training Platform: Google Colab
