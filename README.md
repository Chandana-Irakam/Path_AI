# Path_AI
# PathAI: Intelligent Classification of Rural Infrastructure Projects

## 📌 Project Overview
**PathAI** is a machine learning-based solution developed to classify rural road and bridge construction projects under the correct PMGSY scheme (PMGSY-I, PMGSY-II, RCPLWEA, etc.) using their physical and financial characteristics. This project aims to assist policy analysts, infrastructure planners, and government agencies in automating the classification process, improving efficiency, and enhancing transparency.

This capstone project is built using IBM Cloud Lite services and integrates data science practices for a real-world application in rural infrastructure monitoring.

---

## 🎯 Objectives
- Automatically classify PMGSY projects into their respective schemes.
- Reduce manual effort and misclassification errors in large datasets.
- Support data-driven decisions for monitoring, budgeting, and policy planning.

---

## 🛠️ Technology Stack
- **Platform:** IBM Cloud Lite
- **Tools:** IBM Watson Studio, IBM Cloud Functions, IBM Cloud Object Storage
- **Languages:** Python 3.x
- **Libraries:**
  - `pandas`, `numpy` – Data handling
  - `scikit-learn` – Preprocessing and evaluation
  - `xgboost` – Core classification model
  - `imblearn` – Class balancing using SMOTE
  - `streamlit` / `flask` – (Optional) UI for predictions
  - `ibm_watson_machine_learning` – (Optional) IBM model deployment

---

## 🧠 Machine Learning Approach

### Algorithm Selection
- **XGBoost** was selected for its strong performance on structured data and its ability to handle imbalanced classes and missing values.

### Input Features
- **Physical:** Project length, terrain type, project type (road/bridge)
- **Financial:** Sanctioned cost, expenditure
- **Administrative:** State, district, funding agency
- **Time:** Start date, completion date, project duration

### Training
- Data split: 80/20 train-test
- Preprocessing: Encoding, normalization
- Class balancing: SMOTE
- Tuning: GridSearchCV
- Evaluation: Accuracy, F1-score, Confusion Matrix

---

## 🚀 Deployment
- Trained and tested using **IBM Watson Studio**
- Model deployed via **IBM Cloud Functions**
- Optional UI built with **Streamlit** for end-user interaction

---

## 📈 Results
- Achieved high classification accuracy and balanced performance across all classes
- Reduced manual classification time drastically
- Demonstrated effective real-time scheme prediction for new project data

---

## 🔮 Future Scope
- Integrate GIS/satellite data for richer context
- Expand to cover more regions and schemes
- Use deep learning or AutoML for model enhancement
- Add edge computing support for field-level prediction

---

## 📚 References
- Chen, T. & Guestrin, C. (2016). *XGBoost: A Scalable Tree Boosting System*.
- He, H. & Garcia, E. A. (2009). *Learning from imbalanced data*. IEEE TKDE.
- Pedregosa, F. et al. (2011). *Scikit-learn: Machine Learning in Python*. JMLR.
- IBM Cloud Documentation: [https://cloud.ibm.com/docs](https://cloud.ibm.com/docs)

---

## 👩‍💻 Prepared By
**Irakam Chandana**  
Chaitanya Bharathi Institute of Technology  
B.E. CSE – Specialization in AI & ML  
📧 irakamchandana@gmail.com
