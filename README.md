# EDUNET_AICTE
CROP RECOMMENDATION SYSTEM 
rop Recommendation Using Machine Learning

This project presents a machine learning–based system that recommends the most suitable crop for cultivation based on soil and environmental conditions such as Nitrogen, Phosphorous, Potassium, temperature, humidity, pH, and rainfall. The system is built using Python and various ML models, with Random Forest Classifier providing the best results (~98% accuracy).

---

# Problem Statement

Farmers often rely on traditional knowledge rather than data-driven insights to choose crops, which may lead to poor yield and financial loss. This project aims to provide a reliable, accurate, and easy-to-use system for recommending the most appropriate crop based on current soil and climate data.

---

# Solution Overview

- Trained multiple machine learning models on the **Crop Recommendation Dataset** from Kaggle.
- Best accuracy achieved using **Random Forest Classifier**.
- Input features include: `N`, `P`, `K`, `temperature`, `humidity`, `pH`, and `rainfall`.
- Final model exported using **Pickle** for deployment.

---

##Technologies & Tools Used

- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` – Data handling  
  - `matplotlib`, `seaborn` – Data visualization  
  - `scikit-learn` – Machine learning models and preprocessing  
  - `pickle` – Model serialization
 
Machine Learning Models Used

- Logistic Regression  
- Gaussian Naive Bayes  
- Support Vector Machine (SVC)  
- K-Nearest Neighbors  
- Decision Tree, Extra Tree  
- Random Forest 🌟 (Best performer)  
- Bagging, AdaBoost, Gradient Boosting

**Final Accuracy:** ~98% (Random Forest)
