# 🏏 Cricket Score Predictor

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)
[![ML](https://img.shields.io/badge/Machine%20Learning-Regression-green)]()
[![Flask](https://img.shields.io/badge/Flask-API-lightgrey?logo=flask)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

A Machine Learning-powered web application to predict cricket match scores based on match stats and current conditions. Built with Python, trained on real-world T20I data, and deployed using Flask.

---

## 📌 Project Highlights

- ⚙️ Built a regression-based model to predict scores based on historical T20I match data  
- 🧹 Cleaned and preprocessed raw data for model training  
- 📊 Performed Exploratory Data Analysis (EDA) to find patterns and insights  
- 🧠 Engineered and selected key features to improve model performance  
- 🔍 Trained and evaluated multiple regression models (Linear, Ridge, Lasso)  
- 🌐 Deployed a real-time prediction API using Flask  

---

## 🔧 Tech Stack

- **Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Modeling:** Linear Regression, Ridge, Lasso  
- **Deployment:** Flask (Web API)  
- **Tools:** Jupyter Notebook, Postman  

---

## 📁 Folder Structure

`cricket-score-prediction/` →  
`├── static/image/` – Static files for the web app  
`├── templates/` – HTML templates (Flask frontend)  
`├── app.py` – Flask backend  
`├── pipe.pkl` – Trained regression model  
`├── t20i_info.csv` – Raw dataset  
`├── Cricket Score Predictor.ipynb` – Model building & EDA notebook  
`├── requirements.txt` – Project dependencies  
`├── .gitignore` – Ignored files  
`├── LICENSE` – License file  
`└── README.md` – You're here!

## 🚀 Run the Project Locally

```bash
# 1. Clone the repository
git clone https://github.com/ayush4628/cricket-score-prediction.git
cd cricket-score-prediction
```
# 2. Set up virtual environment (optional)
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```
# 3. Install dependencies
```bash
pip install -r requirements.txt
```

# 4. Run the Flask app
```bash
python app.py
```

# 5. Open in browser or Postman
 Visit: http://localhost:5000/  
 Enter match details to get predicted final score

## 📊 Sample Input (JSON)
```bash
{
  "batting_team": "India",
  "bowling_team": "Australia",
  "venue": "Wankhede Stadium",
  "overs": 10.0,
  "runs": 85,
  "wickets": 2,
  "runs_last_5": 40,
  "wickets_last_5": 1
}
```

## ✅ Sample Output
```bash
{
  "predicted_score": 174.5
}
```

## 📈 Notebook Insights
*Explore the Jupyter notebook ``` (Cricket Score Predictor.ipynb)``` for:  
*Data exploration & cleaning  
*EDA visualizations  
*Model training & evaluation  
*Final pipeline creation and saving  

## 🌟 Future Improvements
*🏆 Add support for IPL and other leagues  
*📡 Integrate live match stats API  
*🎨 Create an interactive frontend using Streamlit or React   
*📊 Add explainable AI tools (e.g., SHAP)  

# 📜 License
This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details. 

## 🙏 Acknowledgments
*Kaggle & open-source cricket datasets  
*scikit-learn documentation  
*Flask community for backend deployment guides  

## 📬 Contact
📧 Email: [kushwahasatak@gmail.com](mailto:kushwahasatak@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ayush4628)
