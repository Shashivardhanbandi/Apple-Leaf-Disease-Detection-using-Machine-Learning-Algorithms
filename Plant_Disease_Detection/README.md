
# 🍏 Apple Leaf Disease Classification using Machine Learning 🌿🧠

This project applies machine learning techniques to classify **apple leaf diseases** using image features or metadata. We implemented **Logistic Regression**, **Random Forest**, and **K-Nearest Neighbors** models — each with both **default** and **tuned** hyperparameters — to evaluate performance and improve accuracy.

## 📁 Repository Structure

```
Apple-Leaf-Disease-Classification/
├── notebooks/
│   ├── lr_apple_00.ipynb     # Logistic Regression (default)
│   ├── lr_apple_01.ipynb     # Logistic Regression (tuned)
│   ├── rf_apple_00.ipynb     # Random Forest (default)
│   ├── rf_apple_01.ipynb     # Random Forest (tuned)
│   ├── knn_apple_00.ipynb    # K-Nearest Neighbors (default)
│   └── knn_apple_01.ipynb    # K-Nearest Neighbors (tuned)
├── data/
│   └── dataset.csv           # Apple leaf dataset
└── README.md                 # Project overview and instructions
```

## 🧪 Models Used

- **Logistic Regression (LR)**
- **Random Forest (RF)**
- **K-Nearest Neighbors (KNN)**

Each model is developed with:
- 🟢 **Default parameters**
- 🔵 **Tuned parameters** using grid/randomized search to boost performance

## ⚙️ How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Apple-Leaf-Disease-Classification.git
   ```

2. **Navigate to the project folder:**
   ```bash
   cd Apple-Leaf-Disease-Classification
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook and open a notebook:**
   ```bash
   jupyter notebook notebooks/lr_apple_00.ipynb
   ```

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

## 📌 Dataset

The dataset used contains features relevant to **apple leaf disease detection**, which may include:
- Color histograms
- Texture descriptors
- Shape features
- Class labels indicating disease type

## 🚀 Future Enhancements

- Incorporate image-based deep learning using CNNs
- Develop a GUI for real-time leaf disease detection
- Deploy the model as a web/mobile application

## 📬 Contact

If you have any questions or suggestions, feel free to reach out:  
📧 **shashibandi564@gmail.com**
