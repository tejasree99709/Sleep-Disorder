# Sleep Disorder Prediction using Machine Learning

**Project Overview**

Sleep Disorder Prediction is a Machine Learning–based web application designed to predict whether a person is likely to suffer from a sleep disorder such as Insomnia or Sleep Apnea based on various health and lifestyle attributes. Early detection of sleep disorders can help individuals seek timely medical advice and improve their overall well-being.
This application uses a Logistic Regression model and provides an interactive interface built with Streamlit, allowing users to input patient data and receive instant predictions.

**Features**

* Interactive and user-friendly Streamlit web application
* Real-time prediction using a trained Machine Learning model
* Supports multiple health and lifestyle input parameters
* One-hot encoding for categorical variables
* Lightweight and efficient Logistic Regression algorithm
* Beginner-friendly ML deployment project

**Machine Learning Workflow**

1. Data collection and preprocessing
2. Handling categorical variables using one-hot encoding
3. Training the Logistic Regression model
4. Saving the trained model using Pickle
5. Building the user interface with Streamlit
6. Generating real-time predictions

**Tech Stack**

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

**Project Structure**

```
Sleep-Disorder-Prediction/
│
├── app.py               # Streamlit application
├── logreg_model.pkl     # Trained Logistic Regression model
├── requirements.txt     # Project dependencies
└── README.md
```

**Installation & Setup**

**1. Clone the Repository**

```bash
git clone https://github.com/your-username/sleep-disorder-prediction.git
cd sleep-disorder-prediction
```

**2. Create a Virtual Environment (Recommended)**

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

**3. Install Dependencies**

```bash
pip install -r requirements.txt
```

If the requirements file is not available, install manually:

```bash
pip install streamlit pandas numpy scikit-learn
```

**4. Run the Application**

```bash
streamlit run app.py
```

The application will automatically open in your default web browser.

**How to Use**

1. Enter the patient details using the sidebar.
2. Adjust the sliders for numerical features such as age, sleep duration, and stress level.
3. Select appropriate options for gender, occupation, and BMI category.
4. Click the Predict button.
5. View the predicted sleep disorder instantly.

**Model Information**

Algorithm Used: Logistic Regression

