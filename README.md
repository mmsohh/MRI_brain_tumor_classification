# MRI_brain_tumor_classification
Developed a CNN (Image Classification) model using a public MRI dataset from Kaggle that classifies brain MRI images into one of four categories: no tumor, pituitary tumor, glioma tumor, and meningioma tumor. 

Achieved a 94.00% Test accuracy, 95.03% Test Precision, 94.00% Recall and 93.95% F1 score in 21 epochs. 

I've included detailed commentary explaining each step and how to interpret the code and results. Even if you're new to Python or machine learning, I break down each section clearly—from convolution layers to dense layers to F1 scores. Feel free to explore the final product!

### 🧠 Key Findings  
**Final Test Accuracy**: **94.00%**  
**Precision**: **94.03%** | **Recall**: **94.00%** | **F1 Score**: **93.95%**  

- **Meningioma tumors** had the **lowest F1 score (0.91)**, with **11 cases misclassified as glioma** and **8 cases misclassified as "no tumor."**  
- **"No tumor" and pituitary tumor** categories performed **best**, each achieving an **F1 score of 0.96 (96%)**.  
- **Pituitary tumors had the highest recall (99%)**, indicating an **excellent detection rate**.  
- **The model achieved strong overall performance** but shows **room for improvement in distinguishing meningioma from other categories**.  

---

### 🛠️ Skills Applied  
- **Machine Learning and Artificial Intelligence (AI)**  
- **Convolutional Neural Networks (CNNs)**  
- **Medical Image Processing**  
- **Data Analysis and Model Evaluation**  
