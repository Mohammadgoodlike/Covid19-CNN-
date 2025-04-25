

---

## 🧠 COVID-19 Detection Using CNN

This project presents a **Convolutional Neural Network (CNN)** model trained to detect potential COVID-19 infection from medical lung images, such as chest X-rays or CT scans. The goal is to classify whether a patient is **infected with COVID-19 or not**, based on image analysis.

---

### 📁 Dataset

The dataset used includes lung images of both COVID-19 positive and negative cases.  
It has been split into training and testing sets to evaluate the model's generalization capability.

---

### 🧪 Methodology

- Model: **CNN (Convolutional Neural Network)**
- Image preprocessing:
  - Resizing
  - Normalization
- Data splitting: Training and Testing
- CNN architecture includes:
  - `Conv2D`, `MaxPooling2D`
  - `Flatten`, `Dense`, `Dropout` layers
- Performance evaluation using accuracy and loss metrics

---

### 📊 Results

After training for several epochs, the model showed promising performance in distinguishing COVID-19 cases from normal ones.  
Further improvements, such as hyperparameter tuning and dataset expansion, are planned.

---

### 📦 Requirements

Make sure the following libraries are installed:

```bash
tensorflow
numpy
matplotlib
scikit-learn
```


