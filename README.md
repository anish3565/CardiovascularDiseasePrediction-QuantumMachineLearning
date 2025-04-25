# Cardiovascular Disease Prediction Web App

A Flask-based web application that predicts cardiovascular disease risk based on patient health parameters.

## 📋 Project Overview

This web application provides a simple interface for healthcare professionals and individuals to predict cardiovascular disease risk using a trained quantum support vector classifier (QSVC). Users can input relevant health parameters through a web form and receive instant prediction results.

## 🚀 Features

- User-friendly web interface
- Real-time prediction of cardiovascular disease
- Powered by a machine learning model
- Simple deployment with Flask

## 📁 Repository Structure

```
CardiovascularDiseasePrediction-QuantumMachineLearning/
├── app.py                  # Flask application entry point
├── qsvc_model.pkl          # Trained quantum SVC model
├── templates/              # HTML templates
│   └── cardio.html         # Main application interface
├── static/                 # Static files
│   ├── css/                # CSS stylesheets
│   │   └── style.css       # Main stylesheet
│   └── images/             # Image files
│       └── cardio_image.webp # Cardiovascular illustration
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

## 🔧 Technologies Used

- **Backend**: Flask, Python
- **Machine Learning**: Support Vector Classifier
- **Data Processing**: NumPy
- **Model Storage**: Pickle
- **Frontend**: HTML, CSS, JavaScript

## 💻 Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/anish3565/CardiovascularDiseasePrediction-QuantumMachineLearning.git
cd CardiovascularDiseasePrediction-QuantumMachineLearning
```

2. **Create and activate a virtual environment:**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install required packages:**
```bash
pip install -r requirements.txt
```

4. **Run the application:**
```bash
python app.py
```

5. **Access the application:**
   Open your web browser and navigate to `http://127.0.0.1:5000/`

## 🫀 How to Use

1. Enter the required patient parameters in the form:
   - **Systolic blood pressure**: The top number in a blood pressure reading
   - **Diastolic blood pressure**: The bottom number in a blood pressure reading
   - **Cholesterol Level**: Select from Normal, Above Normal, or Well Above Normal
   - **Glucose Level**: Select from Normal, Above Normal, or Well Above Normal
   - **Smoking Status**: Indicate if the patient smokes (1 for Yes, 0 for No)
   - **Alcohol Consumption**: Indicate if the patient consumes alcohol (1 for Yes, 0 for No)

2. Click the "Predict" button

3. View the prediction result, which will indicate whether the patient shows cardiovascular disease symptoms

## 🖼️ Application Interface

The application features a clean, user-friendly interface with:
- Form inputs for all required health parameters
- Dropdown selectors for categorical variables
- Clear prediction results display
- Visual representation of cardiovascular health

## 📄 License

This project is licensed under the MIT License.

## 📬 Contact

For questions or feedback, please contact Anish through GitHub.
