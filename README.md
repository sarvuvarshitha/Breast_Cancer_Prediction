

---

# Breast Cancer Tumor Classification using ANN and Genetic Algorithm

## 📌 Project Overview

Breast cancer is a critical health issue affecting millions of women globally. Early and accurate detection is crucial for improving treatment outcomes and survival rates.

This project presents a **Deep Learning-based classification model** that predicts whether a tumor is **benign or malignant** using clinical data. The model leverages an **Artificial Neural Network (ANN)** for prediction and a **Genetic Algorithm (GA)** for optimal feature selection, ensuring both accuracy and efficiency.

---

## ⚙️ Technologies Used

* **Python**
* **TensorFlow & Keras** – for building and training the ANN model
* **GeneticAlgorithm library** – for feature selection
* **NumPy, Pandas, Scikit-learn** – for data preprocessing and analysis

---

## 🧠 Model Architecture

* Input Layer: Features selected via Genetic Algorithm
* Hidden Layers: Multiple dense layers with ReLU activation
* Output Layer: Sigmoid activation for binary classification
* Loss Function: Binary Crossentropy
* Optimizer: Adam

---

## 🧬 Genetic Algorithm for Feature Selection

The **Genetic Algorithm (GA)** is used to automatically select the most relevant features from the dataset. This optimization:

* Improves model **accuracy**
* Reduces **computational complexity**
* Prevents **overfitting**

---

## 📂 Dataset

* **File:** `simplified_dataset.csv`
* **Source:**

  * [Kaggle - Breast Cancer Datasets](https://www.kaggle.com/datasets?search=breast+cancer)
  * [Google Dataset Search](https://datasetsearch.research.google.com)

---

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/breast-cancer-ann-ga.git
   cd breast-cancer-ann-ga
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the model**

   ```bash
   python main.py
   ```

---

## 📊 Results

* Improved classification accuracy using optimized features
* Reduced training time and model complexity
* Successfully distinguished between benign and malignant tumors

---

## 📚 References

* TensorFlow & Keras: [https://www.tensorflow.org/](https://www.tensorflow.org/)
* Genetic Algorithm Library: [https://pypi.org/project/geneticalgorithm/](https://pypi.org/project/geneticalgorithm/)
* Dataset Sources:

  * [https://www.kaggle.com/datasets?search=breast+cancer](https://www.kaggle.com/datasets?search=breast+cancer)
  * [https://datasetsearch.research.google.com](https://datasetsearch.research.google.com)

---

## 📫 Contact

For questions or contributions, feel free to open an issue or pull request.
sarvuvarshitha@gmail.com

---


