# 🌿 Smart Plant Disease Detector

<p align="center">
  <strong>An AI-powered web application that detects plant leaf diseases using Deep Learning.</strong>
</p>

<p align="center">

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)]()
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)]()
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge\&logo=keras\&logoColor=white)]()
[![Gradio](https://img.shields.io/badge/Gradio-FF4B4B?style=for-the-badge)]()
[![Hugging Face](https://img.shields.io/badge/Live%20Demo-Hugging%20Face-yellow?style=for-the-badge\&logo=huggingface)](https://huggingface.co/spaces/Nasibbb/plant-disease-detector)

</p>

---

## 🌟 Overview

**Smart Plant Disease Detector** is a Deep Learning-based application that identifies plant leaf diseases from images using a Convolutional Neural Network (CNN).

The model is trained on the **PlantVillage Dataset** and deployed using **Gradio** on **Hugging Face Spaces**, allowing users to upload an image and instantly receive disease predictions.

---

## ✨ Features

* 🌿 Detects multiple plant leaf diseases
* 📷 Upload images through an interactive web interface
* 🤖 CNN-based image classification
* 📊 Displays prediction confidence scores
* ⚡ Fast and lightweight Gradio deployment

---

## 🛠 Tech Stack

| Category         | Technologies      |
| ---------------- | ----------------- |
| Language         | Python            |
| Deep Learning    | TensorFlow, Keras |
| Data Processing  | NumPy             |
| Image Processing | Pillow (PIL)      |
| Web Interface    | Gradio            |

---

## 📂 Dataset

**Dataset:** PlantVillage Dataset

🔗 https://www.kaggle.com/datasets/emmarex/plantdisease

### Dataset Highlights

* 🌱 Around **20,000+** labeled leaf images
* 🍅 Tomato
* 🥔 Potato
* 🫑 Bell Pepper
* Multiple healthy and diseased plant categories

---

## 🧠 Model Overview

The model is built using a **Convolutional Neural Network (CNN)** with TensorFlow/Keras.

### Training Pipeline

* ImageDataGenerator for augmentation
* CNN-based classifier
* Categorical Crossentropy Loss
* Adam Optimizer

### Performance

| Metric              |       Value |
| ------------------- | ----------: |
| Training Accuracy   | **100.00%** |
| Validation Accuracy |  **92.76%** |
| Training Loss       |   **0.00%** |
| Validation Loss     |  **43.75%** |

---

## 🚀 Live Demo

Try the deployed application here:

👉 **https://huggingface.co/spaces/Nasibbb/plant-disease-detector**

Upload a plant leaf image and receive instant disease predictions.

---

## 📓 Kaggle Notebook

The complete training workflow is available on Kaggle.

🔗 https://www.kaggle.com/code/nasibyun/smart-plant-disease-detector

The notebook includes:

* Data preprocessing
* Model training
* Evaluation
* Prediction examples

---

## 📂 Project Structure

```text
Smart_Plant_disease_detector/
│
├── app.py
├── Plant_disease_detector.h5
├── requirements.txt
├── README.md
└── assets/
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Smart_Plant_disease_detector.git
```

Move into the project

```bash
cd Smart_Plant_disease_detector
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

---

## 📸 Preview

> Add screenshots or GIFs of the Gradio interface here for a better showcase.

---

## 🔮 Future Improvements

* 🌾 Support additional crop species
* 📱 Mobile-friendly interface
* 💊 Disease treatment recommendations
* ☁️ Cloud deployment
* 📈 Model performance dashboard

---

## 👨‍💻 Author

**Nasib Yun**

* 💼 LinkedIn: https://www.linkedin.com/in/nasib-khan-0123459z786/
* 🏆 Kaggle: https://www.kaggle.com/nasibyun

---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub.
