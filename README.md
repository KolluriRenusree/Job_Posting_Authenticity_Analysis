# **Job Fraud Detection Application**

-> **Live: https://job-posting-authenticity-analysis.onrender.com**

## **Overview**
This project is a web-based application designed to detect fraudulent job postings. Using machine learning models and a user-friendly interface, the application predicts whether a job posting is legitimate or fraudulent based on the provided job description.

---

## **Features**
- **Multi-Model Prediction**:
  - Predictions from five machine learning models: Naive Bayes, SVM, Random Forest, XGBoost, and Logistic Regression.
- **User-Friendly Interface**:
  - A simple, responsive web interface for inputting job descriptions and viewing predictions.
- **Real-Time Results**:
  - Displays predictions from all models along with a final aggregated result.
- **Keyword-Based Fraud Detection**:
  - Quick identification of fraudulent postings based on specific keywords.

---

## **Tech Stack**
### **Front-End**
- **HTML**: Structuring the web page.
- **CSS**: Styling the interface for a modern, responsive design.

### **Back-End**
- **Flask**: Web framework for handling requests and rendering templates.
- **Python**: Logic for integrating machine learning models and processing input.

### **Machine Learning**
- Models used: Naive Bayes, SVM, Random Forest, XGBoost, Logistic Regression.
- Libraries: Scikit-learn, XGBoost, Pandas, NumPy, Pickle.

---

## **Setup Instructions**

### 1. Clone the Repository
```bash
git clone https://github.com/Harsh-beep/Job-Posting-Authenticity-Analysis.git
cd Job-Posting-Authenticity-Analysis
```
### 2. Set Up a Virtual Environment
#### For Linux/Mac:
```bash
python -m venv venv
source venv/bin/activate
```
#### For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
python app.py
```
### 5. Access the Application
- Open your browser and navigate to http://127.0.0.1:5000

## **Usage**
1. Enter a job description in the text area on the homepage.
2. Click the Predict button to analyze the input.
3. View the prediction results for all models:
4. Legitimate or Fraudulent for each model.
5. Aggregated prediction result is displayed prominently.

## **Project Structure**
```
Job-Posting-Authenticity-Analysis/
├──Job_Posting_Authenticity_Analysis.ipynb   # Code Fiile
├── app.py                 # Flask application
├── templates/
│   └── index.html         # Front-end HTML template
├── models/
│   ├── best_lr_model.pkl  # Logistic Regression model
│   ├── best_nb_model.pkl  # Naive Bayes model
│   ├── best_rf_model.pkl  # Random Forest model
│   ├── best_svm_model.pkl # Support Vector Machine model
│   ├── best_xgb_model.pkl # XGBoost model
│   └── vectorizer.pkl     # TF-IDF Vectorizer
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## **Screenshots**
### Homepage
![image](https://github.com/user-attachments/assets/69abc4a6-92d5-46d0-b92c-a3974b61b01a)
![image](https://github.com/user-attachments/assets/73096720-3f12-4a54-9fbb-a4fb12b9d9ef)

## Contributors
We'd like to thank the following individuals for their contributions:

<table>
<tr>
      <td align="center">
        <a href="https://github.com/Harsh-beep">
            <img src="https://avatars.githubusercontent.com/u/76943884?v=4" width="100;" alt="Harsh-beep"/>
            <br />
            <sub><b>Harsh</b></sub>
        </a>
    </td>
  <td align="center">
        <a href="https://github.com/Anuragk0106">
            <img src="https://avatars.githubusercontent.com/u/76943884?v=4" width="100;" alt="Anuragk0106"/>
            <br />
            <sub><b>Harsh</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/sneha9231">
            <img src="https://avatars.githubusercontent.com/u/76943884?v=4" width="100;" alt="sneha9231"/>
            <br />
            <sub><b>Sneha</b></sub>
        </a>

</tr>
</table>

### Mentor
<table>
    <tr>
    <td align="center">
        <a href="https://www.linkedin.com/in/sai-vishal-varma-nadimpalli/">
            <img src="https://media.licdn.com/dms/image/v2/C5103AQFpd869wSrNvw/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1566318630295?e=1741219200&v=beta&t=uyHsGf-pSukg44SMdLBOIKd_cGC7iOHuwSBx9cYH-Ek" width="100;" alt="[NAME]"/>
            <br />
            <sub><b>Mr. Sai Vishal Varma Nadimpalli</b></sub>
        </a>
    </td>
    </tr>
</table>




