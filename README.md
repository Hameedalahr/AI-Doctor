# AI Doctor - Your Personal Health Assistant

AI Doctor is an intelligent web application that acts like a personal doctor. Users can input their symptoms, and the system provides comprehensive health recommendations, including the predicted disease, description, precautions, medications, workouts, and diet plans.

This project leverages machine learning models trained on a cleaned dataset sourced from [Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/noorsaeed/medicine-recommendation-system-dataset)) to provide accurate predictions.

---

## Features

- **Symptom-based Disease Prediction**: Enter your symptoms and get the most likely disease.
- **Detailed Disease Description**: Learn more about the predicted condition.
- **Precautions**: Health and lifestyle suggestions to prevent complications.
- **Medications**: Recommended medications for the predicted disease.
- **Workouts**: Suggested exercises to improve health.
- **Diet Plans**: Nutrition advice tailored for your condition.
- **Interactive UI**: Responsive and user-friendly interface built with Bootstrap 5.
- **Voice Input**: Users can provide symptoms via speech (optional feature).

---

## Screenshots

**Home Page**  
![Home Page](https://github.com/Hameedalahr/AI-Doctor/blob/main/Home%20page.png?raw=true)  

**Prediction Popup**  
![Prediction Page](https://github.com/Hameedalahr/AI-Doctor/blob/main/Predicted%20popup.png?raw=true)  




---

## Technologies Used

- **Backend**: Python, Flask
- **Machine Learning**: Scikit-learn (SVC used for final predictions)
- **Frontend**: HTML, CSS, Bootstrap 5
- **Data Handling**: Pandas, NumPy
- **Model Persistence**: Pickle
- **Deployment**: Render

---

## How It Works

1. **Data Preparation**: Collected and cleaned dataset from Kaggle containing symptoms and corresponding diseases.
2. **Model Training**: Multiple models were tested, including Random Forest, Logistic Regression, and SVC.
3. **Model Selection**: SVC (Support Vector Classifier) was selected due to its superior accuracy.
4. **Prediction**: Users submit symptoms through the web form, and the app predicts the disease.
5. **Recommendations**: The app provides description, precautions, medications, workouts, and diet plans based on the predicted disease.

---


