# 🏥 Tumor Classification  

## 📌 Project Overview  
Breast cancer is one of the leading causes of death among women worldwide. **Early detection** through **ultrasound imaging** can significantly improve treatment outcomes.  

This project aims to classify breast ultrasound images into **three categories**:  
✔ **Normal**  
✔ **Benign Tumors**  
✔ **Malignant Tumors**  

Using **machine learning techniques**, we analyze breast ultrasound images to assist in accurate tumor classification.  

---

## 📂 Dataset  
The dataset includes **780 breast ultrasound images** collected from **600 female patients** (ages **25–75**).  

📌 **Dataset Details:**  
- **Image Format**: PNG  
- **Image Size**: ~500×500 pixels  
- **Categories**: Normal, Benign, Malignant  
- **Collected in**: 2018  

🔗 **Access the dataset here:** [Kaggle Competition](https://www.kaggle.com/competitions/tumor-classification)  

---

## 🛠️ Skills Applied  
✔ **Image Preprocessing & Augmentation** (resizing, normalization, contrast adjustment)  
✔ **Feature Extraction** (Gabor filters for texture analysis)  
✔ **Dimensionality Reduction** (LDA for optimized classification)  
✔ **Machine Learning Model Development** (SVM, Random Forest)  

---

## 📜 Project Steps  
1️⃣ **Data Preprocessing & Augmentation**  
   - Resize images to standard dimensions.  
   - Apply **contrast enhancement, noise reduction, and augmentation** (rotation, flipping).  

2️⃣ **Feature Engineering & Extraction**  
   - Extract **texture features** using **Gabor filters**.  
   - Reduce dimensionality using **Linear Discriminant Analysis (LDA)**.  

3️⃣ **Model Development & Training**  
   - Train models: **SVM, Random Forest**.  
   - Use **cross-validation and hyperparameter tuning**.  

4️⃣ **Performance Evaluation**  
   - Assess models using **Accuracy, Precision, Recall, and F1-score**.  
   - Visualize **confusion matrices** to analyze classification errors.  

5️⃣ **Insights & Medical Impact**  
   - Identify key **features distinguishing benign from malignant tumors**.  
   - Improve **automated diagnostic support** for radiologists.  

---

## 📊 Key Insights  
📌 **Which features help classify tumors?**  

📌 **Which model performed best?**  

📌 **How can this project help in real life?**  

---

## 🖥️ Technologies Used  
- **Python** (scikit-image, NumPy, pandas, scikit-learn)  
- **Feature Extraction** (Gabor Filters, Histogram Equalization)  
- **Dimensionality Reduction** (LDA)  
- **Data Augmentation** (Image flipping, rotation, scaling)  

---
