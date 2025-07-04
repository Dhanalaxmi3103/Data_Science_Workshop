# 🔢 Handwritten Digit Recognition with PCA (MNIST)

This project applies **Principal Component Analysis (PCA)** to reduce the dimensionality of the MNIST handwritten digit dataset and visualizes the results.

## 📌 Objective
To demonstrate dimensionality reduction using PCA and observe how it captures the structure of high-dimensional image data.

## 🗂️ Dataset
- **File**: `hmnist_28_28_L.csv.zip`  
- Contains 28x28 grayscale images of digits (0–9), flattened into 784 features + labels.

## 🛠️ Tools & Libraries
- Python, NumPy, Pandas
- Matplotlib, Seaborn
- scikit-learn (PCA)

## 📈 Workflow
1. Load and preprocess MNIST dataset
2. Apply PCA to reduce dimensions from 784 to 2 or 3
3. Visualize digit clusters using 2D/3D plots

## ✅ Results
- PCA successfully visualizes digit clusters
- 2D scatter plot shows class separability

## 📎 How to Run
1. Upload the dataset
2. Run the notebook in Colab or Jupyter
3. Scroll to the visualization section for PCA output

## 📚 Extensions
- Use PCA as a preprocessing step before classification (e.g., SVM)
- Try t-SNE or UMAP for better clustering visualizations
