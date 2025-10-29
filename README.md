# 🧬 Dami Project — Machine Learning on Gene Expression Data

## 📖 Overview
The **Dami Project** applies **machine learning techniques** to classify and analyze a biological dataset containing **gene expression data**.  
The goal is to build and evaluate predictive models capable of identifying patterns and efficiently classifying biological samples.

This notebook provides a complete **data science workflow**, from cleaning and preprocessing to model training and evaluation.

---

## ⚙️ Project Structure

| Step | Description |
|------|--------------|
| **1. Data Loading** | Import the dataset and display its structure (rows, columns, and data types). |
| **2. Data Exploration** | Visualize class distribution and data variation using bar charts and boxplots. |
| **3. Data Preprocessing** | Handle missing values, remove outliers, and standardize features. |
| **4. Dimensionality Reduction** | Apply **Principal Component Analysis (PCA)** to reduce data dimensions. |
| **5. Clustering** | Perform **K-Means clustering** to explore sample groupings. |
| **6. Model Training** | Train supervised ML models: <br> - **K-Nearest Neighbors (KNN)** <br> - **Decision Tree** <br> - **Naive Bayes** |
| **7. Evaluation** | Measure model performance using **accuracy**, **F1-score**, and confusion matrices. |
| **8. Visualization** | Show data distributions, PCA results, and model performance graphs. |

---

## 🧰 Technologies Used

- **Python 3.9+**
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computation  
- **Matplotlib / Seaborn** – Visualization  
- **Scikit-learn** – Machine learning models and metrics  
- **Jupyter Notebook** – Development environment  

---

## 🧪 How to Run the Project

### 🔧 Requirements
Install dependencies using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### ▶️ Run Instructions
1. Open **Google Colab** or **Jupyter Notebook**.  
2. Upload `Dami_project.ipynb`.  
3. Run all cells in order.  
4. The notebook will:
   - Load and preprocess the dataset  
   - Visualize class distributions  
   - Train models (KNN, Decision Tree, Naive Bayes)  
   - Display performance metrics and plots  

---

## 📊 Example Results

| Model | Accuracy | F1-Score |
|--------|-----------|----------|
| Decision Tree | ~85% | ~0.83 |
| KNN | ~88% | ~0.85 |
| Naive Bayes | ~82% | ~0.80 |

> *Note: Results may vary depending on the dataset and random initialization.*

---

## 📈 Visualizations
- **Bar charts** for class distribution  
- **Boxplots** for gene expression levels  
- **PCA plots** for dimensionality reduction  
- **Confusion matrices** for classification evaluation  

---

## 🧩 Key Insights
- PCA improved model interpretability and clustering quality.  
- KNN achieved the best accuracy among tested models.  
- Feature standardization was crucial for performance stability.  

---

## 👩‍💻 Author
**Dami Project Team**  
Master’s Program — Data Science and Artificial Intelligence  

---

## 📜 License
This project is for **academic and educational use only**.  
You are free to use and modify it for learning purposes.
