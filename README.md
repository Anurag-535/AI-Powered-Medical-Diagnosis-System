# HealthGuard - Disease Prediction System

\
*A Clinical Decision Support System for Predicting Disease*

## 🚀 Overview

HealthGuard is an AI-powered disease prediction system that helps users assess their risk levels for **Diabetes**, **Heart Disease**, and **Parkinson's Disease** based on input medical parameters. Built with **Streamlit**, this project leverages **machine learning models** to provide instant health assessments.

## 🏆 Features
AI-Powereed:
- **Diabetes Risk Assessment**: Predicts the likelihood of diabetes using relevant health indicators.
- **Heart Disease Assessment**: Evaluates cardiac health based on clinical parameters.
- **Parkinson's Disease Assessment**: Analyzes neurological data to determine Parkinson's risk.
- **Modern UI**: Intuitive and responsive interface designed with custom CSS.
- **Real-Time Predictions**: Instant results with color-coded risk assessments.
- **Multi-Disease Prediction**: Choose from multiple disease assessments via a sidebar menu.

## 📸 Project Screenshot
### Figure -1 : Diabetes risk assessment interface (Negative result)
 ![HealthGuard - Disease Prediction System - Google Chrome 19-03-2025 18_23_14](https://github.com/user-attachments/assets/c6a6fa1b-d8ac-4e57-836d-6439b1f82178)


-------


### Figure - 2 : Diabetes risk assessment interface (Positive result)
![HealthGuard - Disease Prediction System - Google Chrome 19-03-2025 18 24_02](https://github.com/user-attachments/assets/faa50533-1ed5-41ed-8849-48e0d7fef928)


------


 
### Figure - 3 : Cardiac risk assessment interface (Negative result)
![HealthGuard - Disease Prediction System - Google Chrome 19-03-2025 18_25_47](https://github.com/user-attachments/assets/e5ae38fa-22c5-486e-beaa-756ccab174ea)

--------

 

### Figure -4 : Cardiac risk assessment interface (Positive result)
![HealthGuard - Disease Prediction System - Google Chrome 19-03-2025 18_26_44](https://github.com/user-attachments/assets/a6ede311-832f-4b23-8e1a-3f49d6bbb6a0)



-------

### Figure - 5 : Parkinsons disease assessment interface (Negative result)
![HealthGuard - Disease Prediction System - Google Chrome 19-03-2025 18_36_26](https://github.com/user-attachments/assets/7f917899-89a1-4cc0-982d-1955c8986a6f)



-------
 

### Figure – 6 : Parkinsons disease assessment interface (Positive result)

![HealthGuard - Disease Prediction System - Google Chrome 19-03-2025 18_31_20](https://github.com/user-attachments/assets/027a8bbf-2438-460e-8f98-9755f064d92e)


 ---------------------





## 🏗️ Tech Stack

- **Python**
- **Streamlit** (for UI & interactivity)
- **Scikit-Learn** (for ML models)
- **Pickle** (for model serialization)
- **CSS** (for UI customization)

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
https://github.com/Anurag-535/AI-Powered-Medical-Diagnosis-System
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
streamlit run web.py
```

## 📊 Machine Learning Models Used

The system uses **pre-trained machine learning models** to predict diseases:

- **Diabetes Prediction Model** (Trained on the PIMA Indian Diabetes Dataset)
- **Heart Disease Prediction Model** (Based on UCI Heart Disease Dataset)
- **Parkinson's Disease Model** (Trained on Parkinson’s dataset)

## 📜 Usage

1. **Choose a Disease** from the sidebar menu.
2. **Enter the required health parameters** (e.g., glucose levels, blood pressure, BMI, etc.).
3. **Click the "Assess Risk" button** to get instant results.
4. **Interpret Results:**
   - ✅ **Green:** Low risk (Maintain healthy habits)
   - 🚨 **Red:** High risk (Consult a medical professional)

## 📁 Project Structure

```
HealthGuard/
│── models/  # Serialized ML models (.sav files)
│── app.py   # Main Streamlit app script
│── requirements.txt  # Dependencies
│── README.md  # Project documentation
```

## 💡 Future Enhancements

- 🏥 **Integration with Health APIs** (e.g., Fitbit, Apple Health)
- 📊 **Enhanced Data Visualization** for better risk analysis
- 🔍 **Improved Model Accuracy** using Deep Learning techniques

## 🤝 Contribution

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch.
3. Commit changes and push to your fork.
4. Submit a pull request.

## 📜 Disclaimer

This tool is for **research and educational purposes only**. It is not a substitute for professional medical advice. Always consult a healthcare provider for medical concerns.

## ⭐ Show Some Support

If you found this project helpful, give it a ⭐ on GitHub!

---

*Developed by **Anurag Jaiswal** 

