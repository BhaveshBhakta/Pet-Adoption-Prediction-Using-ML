## 🐾 Pet Adoption Prediction

### 📌 Project Overview

This project aims to predict the **likelihood of pet adoption** based on various pet-related features such as breed, color, age, vaccination status, and shelter history. The goal is to assist shelters and adoption agencies in identifying pets that are less likely to be adopted and to take proactive measures.

---

### ⚙️ Technical Highlights

* **Dataset**: [Kaggle - Predict Pet Adoption Status](https://www.kaggle.com/datasets/rabieelkharoua/predict-pet-adoption-status-dataset)
* **Size**: 2007 entries, 13 columns
* **Key Features**:

  * Pet Type, Breed, Age, Color, Size, Vaccination, Health Condition, Time in Shelter, Adoption Fee, Previous Ownership
* **Approach**:

  * Data Cleaning, Visualization (Histograms, Boxplots, Heatmaps)
  * Label Encoding, Feature Scaling
  * Binary Classification (Adopted: `1`, Not Adopted: `0`)
  * Models Used:

    * Logistic Regression, Ridge Classifier, SVC, Random Forest, XGBoost, AdaBoost, Gradient Boosting, Bagging, Decision Tree
* **Best Accuracy**:

  * \~100% with ensemble models (Random Forest, AdaBoost, Gradient Boosting)
  * \~96% with SVC
  * \~94%+ with Logistic Regression

---

### 🎯 Purpose and Applications

* Help animal shelters prioritize care and outreach for pets less likely to be adopted
* Provide predictive insights to optimize resources and improve adoption rates
* Support NGOs and municipal animal services in reducing shelter overpopulation
* Enhance user experience on pet adoption platforms with smart suggestions

---

### 🛠️ Installation

 Clone the repository:

   ```bash
   git clone https://github.com/BhaveshBhakta/Pet-Adoption-Prediction-Using-ML.git
   cd Pet-Adoption-Prediction-Using-M
   ```


---

### 🤝 Collaboration

We welcome contributions to improve the project. You can help by:

* Improving model robustness via hyperparameter tuning
* Adding explainability (e.g., SHAP or LIME)
* Deploying the model via API or dashboard
