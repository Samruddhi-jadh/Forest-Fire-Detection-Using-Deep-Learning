# Forest-Fire-Detection-Using-Deep-Learning
Edunet_AICTE_Cycle_6_Internship
Your notebook doesn’t contain any markdown cells, which suggests the code may not be documented with explanations or headings. Based on the code structure I reviewed, I’ll create a clean, well-organized, and professional **README.md** file for your **Forest Fire Detection Using Deep Learning** project.

---

## 🌲 Forest Fire Detection Using Deep Learning 🔥

### Overview

This project leverages deep learning to detect forest fires from image data. Utilizing a convolutional neural network (CNN), the model learns to distinguish between fire and non-fire scenarios in forest environments, helping in early wildfire detection and environmental safety.

---

### 🚀 Features

* Downloads and uses **The Wildfire Dataset** from Kaggle.
* Image preprocessing using `ImageDataGenerator`.
* Built with a CNN model using TensorFlow/Keras.
* GPU support for faster training .
* Performance visualization with accuracy/loss plots.

---

### 🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy, Matplotlib
* KaggleHub (for dataset download)

---

### 📁 Dataset

* **Source**: [The Wildfire Dataset on Kaggle](https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset)
* The dataset is automatically downloaded using `kagglehub`.

---

### 🏗️ Model Architecture

The CNN model typically includes:

* Convolutional Layers (Conv2D)
* Max Pooling Layers (MaxPooling2D)
* Fully Connected Layers (Dense)
* Dropout for regularization
* Flatten layer for transition from 2D to 1D

---

### 📊 Training and Evaluation

* Uses training and validation sets with real-time data augmentation.
* GPU is utilized (if available) to accelerate training.
* Metrics like accuracy and loss are plotted post-training.

---

### 💻 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/forest-fire-detection-dl.git
   cd forest-fire-detection-dl
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook Forest_Fire_Detection_using_DL.ipynb
   ```

---

### 📬 Contact

For any queries or contributions, feel free to reach out via mail or open an issue on GitHub.

---


