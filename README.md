# 🐾 Pokémon Image Classification using CNN

A Deep Learning project that classifies Pokémon images into three different classes using a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

The model is trained to identify the following Pokémon:
-  Pikachu
-  Charmander
-  Bulbasaur

---

## 📌 Project Overview

This project demonstrates how Convolutional Neural Networks (CNNs) can be used for multi-class image classification.

The dataset contains Pokémon images of different dimensions. Since CNN models require fixed-size inputs, all images were preprocessed and resized to **100 × 100 × 3** before training.

The trained model learns visual features such as edges, textures, and shapes to accurately classify images into one of the three Pokémon categories.

---

## 📂 Dataset

The dataset was downloaded using the following command:

```python
!wget https://www.dropbox.com/sh/s9r1av3m4eatd3y/AAA8zYti5b5tnyKfcah2Reaja -O dataset
```

### Dataset Classes

- Pikachu
- Charmander
- Bulbasaur

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Google Colab

---

## 📸 Data Preprocessing

The following preprocessing steps were performed:

- Loaded images from the dataset.
- Resized every image to **100 × 100 pixels**.
- Converted images into RGB format.
- Final input shape used for training:

```python
(100, 100, 3)
```

This ensures all images have the same dimensions before being fed into the CNN model.

---

## 🧠 CNN Model

The Convolutional Neural Network consists of:

- Convolutional Layers
- ReLU Activation
- Max Pooling Layers
- Flatten Layer
- Fully Connected (Dense) Layers
- Softmax Output Layer

The Softmax layer predicts the probability of an image belonging to one of the three Pokémon classes.

---

## 🚀 Project Workflow

1. Download the dataset.
2. Load the Pokémon images.
3. Resize images to **100×100×3**.
4. Preprocess the dataset.
5. Build the CNN model.
6. Train the model.
7. Evaluate model performance.
8. Predict the Pokémon class for unseen images.

---

## 📁 Project Structure

```
Pokemon-Image-Classification/
│
├── Pokemon_classification_using_cnn.ipynb
├── README.md
└── dataset/
    ├── Pikachu/
    ├── Charmander/
    └── Bulbasaur/
```

---

## 🎯 Output Classes

The model predicts one of the following classes:

- Pikachu
- Charmander
- Bulbasaur

---

## 💡 Future Improvements

- Apply Data Augmentation.
- Train on a larger Pokémon dataset.
- Use Transfer Learning models such as MobileNetV2 or EfficientNet.
- Deploy the model using Streamlit or Flask.
- Improve accuracy through hyperparameter tuning.

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/Pokemon-Image-Classification.git
```

Move to the project directory:

```bash
cd Pokemon-Image-Classification
```

Open the notebook:

```bash
jupyter notebook Pokemon_classification_using_cnn.ipynb
```

or run it directly in **Google Colab**.

---

## 📚 Learning Outcomes

Through this project, I learned:

- Image preprocessing
- Image resizing
- Building CNN architectures
- Multi-class image classification
- Model training and evaluation
- Predicting unseen images using Deep Learning

---

## 👩‍💻 Author

**Soni Jain**

- GitHub: https://github.com/SoniJain03
- LinkedIn: https://linkedin.com/in/sonijain03
