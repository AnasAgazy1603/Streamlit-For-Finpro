# Customer Churn Prediction App

This is a Streamlit-based web application to predict **customer churn** using a trained **LightGBM model**. Users can input customer details, get real-time predictions, and view data insights through a user-friendly dashboard.

 **Live App:**  
[https://bradlees-churn-prediction-uzwev9edpkgrmdmzjqvdxr.streamlit.app/](https://bradlees-churn-prediction-uzwev9edpkgrmdmzjqvdxr.streamlit.app/)

---

## Features

1. Interactive dashboard with churn summary and customer metrics
2. Form-based prediction input
3. LightGBM model with high accuracy and SHAP interpretability
4. Visualizations for churn distribution and customer tenure
5. Prediction history saved and viewable
   
---

## Technologies Used

- Python
- Streamlit
- pandas, numpy
- scikit-learn, imbalanced-learn
- LightGBM
- matplotlib
- joblib
  
---

## Folder Structure

```bash
Streamlit-For-Finpro/
├── apps baru/
│   └── churn_stream.py         # Main Streamlit app file
├── Final_Model_Churn_Analysis_Project.pkl  # Pretrained LightGBM model
├── X_train_cleaned.csv         # Cleaned training data
├── history.csv                 # Auto-created prediction history
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

---

## Running the App Locally

```bash
Copy
Edit
git clone https://github.com/AnasAgazy1603/Streamlit-For-Finpro.git
cd Streamlit-For-Finpro
pip install -r requirements.txt
streamlit run "apps baru/churn_stream.py"
```
---

## Model Info

Model: Light Gradient Boosting Machine (LightGBM)

Training Features:

Device count, order history, tenure, satisfaction score, payment mode, complaints, etc.

Output: Binary classification → Churn vs Not Churn

---

## Reference

Dong, S., Khattak, A., Ullah, I., Zhou, J., & Hussain, A. (2022).
Predicting and analyzing road traffic injury severity using boosting-based ensemble learning models with SHAPley Additive exPlanations.
International Journal of Environmental Research and Public Health, 19(5), 2925.

---

## About

Developed by Abdillah Zaraaifa Al Farisa, Abdul Hadi, Anas Agazy
