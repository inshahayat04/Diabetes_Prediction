# Diabetes_Prediction using Machine Learning

A machine learning-based system to predict the likelihood of diabetes in individuals using medical attributes. The project leverages the Pima Indians Diabetes Dataset, applies K-Nearest Neighbors (KNN) for classification, and integrates the trained model into a Django web application for real-time predictions.

🔗 Live Demo: https://predictdiabetes.pythonanywhere.com/ 

📌 Project Overview

Diabetes is one of the most widespread chronic diseases worldwide. Early detection plays a crucial role in reducing complications and improving patient outcomes. This project applies machine learning to clinical features such as:

1. Pregnancies
2. Glucose concentration
3. Blood pressure
4. Skin thickness
5. Insulin level
6. BMI
7. Diabetes Pedigree Function
8. Age

The trained model classifies individuals as diabetic (1) or non-diabetic (0).

⚙️ Features

✅ Machine Learning Model trained using KNN classifier
📊 Exploratory Data Analysis (EDA) with visualization of key patterns
🖥️ Django Web Application with a clean, responsive UI
⚡ Real-time Predictions on patient health data
☁️ Deployed on PythonAnywhere for accessibility

## Project Structure
DiabetesPrediction/
│── diabetes_project/       # Django project
│── predictor/              # Main app containing views and logic
│   ├── templates/          # HTML templates (home, result pages)
│   ├── static/             # CSS, images, background files
│   ├── views.py            # Prediction logic integrated with ML model
│── diabetes_model.pkl      # Serialized KNN model
│── manage.py
│── folder_structure.txt

## 📊 Dataset
The project uses the Pima Indians Diabetes Dataset, a well-known benchmark dataset in medical machine learning research.

Source: https://www.kaggle.com/code/aneevinay/diabetics-prediction/input 
Target Variable: Outcome → 1 (Diabetic) / 0 (Non-Diabetic)

🚀 Deployment

Steps followed for deployment on PythonAnywhere:

1. Upload project folder and model file (diabetes_model.pkl)
2. Create virtual environment & install dependencies
3. Configure Django settings & static files
4. Run migrations & start server

📈 Model Performance

The model was evaluated using:

Accuracy
Precision
Recall
F1-score
Confusion Matrix

Key Observations:
1. Glucose, BMI, and Age are the strongest predictors.
2. KNN classifier provided reliable predictions with balanced performance metrics.

📌 Future Enhancements

1. Add more advanced models (Logistic Regression, Random Forest, Deep Learning)
2. Expand dataset for higher accuracy
3. Integrate wearable device data for real-time monitoring
4. Add Tailwind CSS for modern UI with dark mode

📚 References

1. Scikit-learn Documentation: https://scikit-learn.org/stable/modules/neighbors.html#neighbors 
2. Django Documentation: https://docs.djangoproject.com/en/5.2/ 
