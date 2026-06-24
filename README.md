# Image Caption Generator

## 📌 Project Overview

Image Caption Generator is a deep learning-based application that automatically generates meaningful textual descriptions for uploaded images. The system combines computer vision and natural language processing techniques to understand image content and produce human-readable captions.

The application uses a pre-trained Convolutional Neural Network (CNN) for image feature extraction and a Long Short-Term Memory (LSTM) network for caption generation. A user-friendly Streamlit interface allows users to upload images and instantly receive generated captions.

---

## 🚀 Features

* Upload images through an interactive web interface.
* Automatic image caption generation.
* Deep learning-based prediction using CNN and LSTM architectures.
* Real-time caption display.
* Simple and user-friendly Streamlit application.
* Pre-trained model support for faster inference.

---

## 🛠️ Technologies Used

* Python
* Streamlit
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Pickle

---

## 📂 Project Structure

```text
IMAGE_CAPTION_GENERATOR/
│
├── models/
│   ├── feature_extractor.keras
│   ├── model.keras
│   └── tokenizer.pkl
│
├── main.py
├── uploaded_image.jpg
├── README.md
└── requirements.txt
```

---

## ⚙️ How It Works

1. The user uploads an image.
2. The CNN-based feature extractor processes the image and extracts visual features.
3. The extracted features are passed to the trained LSTM caption generation model.
4. The model predicts words sequentially to form a meaningful sentence.
5. The generated caption is displayed to the user.

---

## ▶️ Installation and Execution

### Clone the Repository

```bash
git clone https://github.com/VanshikaN11/Image_caption_generation.git
cd Image_caption_generation
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run main.py
```

The application will open in your browser at:

```text
http://localhost:8501
```

---

## 🎯 Applications

* Image Understanding Systems
* Assistive Technology for Visually Impaired Users
* Social Media Content Generation
* Digital Asset Management
* Automated Image Annotation

---

## 🔮 Future Enhancements

* Transformer-based caption generation models.
* Multi-language caption generation.
* Real-time webcam captioning.
* Cloud deployment support.
* Improved caption accuracy using larger datasets.

---

## 📊 Deep Learning Concepts Used

* Convolutional Neural Networks (CNN)
* Long Short-Term Memory Networks (LSTM)
* Image Feature Extraction
* Natural Language Generation (NLG)
* Sequence Prediction

---

## 👩‍💻 Author

**Vanshika N11**

Image Caption Generator Project using Deep Learning, TensorFlow, Keras, and Streamlit.
