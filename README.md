# 🍔 Food Image Classification Using Deep Learning

### 📌 Project Overview  
This project applies **deep learning techniques** to classify images of food into one of **three categories**, using a subset of the **Food-101** dataset. It demonstrates how convolutional neural networks (CNNs) and **transfer learning** (MobileNetV2) can be applied to real-world image classification tasks like meal tracking, restaurant automation, or dietary assessment.

The analysis was implemented in Python using **TensorFlow**, **Keras**, and **Matplotlib** in a **Jupyter Notebook** environment.

---

### 📁 Folder Structure

<pre>/food-image-classification/
│
├── data/
│ └── tacos_breakfast_burrito_ravioli_10_percent zipfile with images from 3 food categories
│
├── notebooks/
│ └── food-image-classification.ipynb # Full workflow with preprocessing, model training, and evaluation </pre>

---

## 🔍 Key Insights
- 🍱 Built a deep learning pipeline for **multi-class image classification** using CNNs.
- 🖼️ Applied **real-time image augmentation** for better model generalization.
- 🧠 Trained both a **custom CNN** and a **transfer learning model (MobileNetV2)**.
- 📉 Visualized training/validation loss and accuracy curves for performance insights.
- 🚀 Achieved high validation accuracy despite limited sample size and class count.

---

### 🛠 Tools & Technologies
- **Python** – Core programming language  
- **TensorFlow & Keras** – Deep learning frameworks  
- **NumPy & Pandas** – Data handling and structure  
- **Matplotlib** – Visualization of training metrics  
- **Jupyter Notebook** – Interactive analysis and documentation  

---

### 🔄 Workflow
- ✅ **Data Loading**: Imported food images from structured directories  
- 🧹 **Image Preprocessing**: Resizing, normalization, augmentation via `ImageDataGenerator`  
- ⚙️ **Model Training**:
  - Custom CNN from scratch
  - MobileNetV2 with fine-tuning
- 📊 **Evaluation**: Tracked model accuracy and loss; compared architectures

---

### 📈 Results  
This project showcases the feasibility of:
- Using CNNs and transfer learning for fast and accurate food classification  
- Building a foundational system for **AI-powered nutrition or culinary applications**  
- Scaling up to broader categories (e.g., all 101 classes from the full Food-101 dataset)

---

### 🔗 Links  
📂 [Dataset – ETH Zurich: Food-101](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/)

---

### ⚠️ Disclaimer  
This project is for educational and demonstration purposes only.  
- Images are sourced from a **public academic dataset (Food-101)**.  
- No personal or sensitive data is used.  
- For feedback or inquiries, contact the project maintainer via [GitHub](https://github.com/matmarcinek).

