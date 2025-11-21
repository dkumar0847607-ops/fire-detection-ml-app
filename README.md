# 🔥 Fire Detection Machine Learning App  
A Flask web application that predicts whether a given set of environmental conditions will result in **Fire** or **Not Fire**, based on the Algerian Forest Fires dataset.

This project includes:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training (Ridge Regression / Classification)
- A Flask-based web interface for end users
- Pre-trained ML model and scaler (`ridge.pkl`, `scaler.pkl`)

---

## 📁 Project Structure

L-29_model/
│
├── application.py # Flask application
├── models/
│ ├── ridge.pkl # Trained ML model
│ └── scaler.pkl # StandardScaler
│
├── templates/
│ ├── index.html # Homepage
│ └── home.html # Prediction output page
│
├── notebooks/
│ ├── 2.0-EDA And FE Algerian Forest Fires.ipynb
│ ├── 3.0-Model Training.ipynb
│ └── Algerian_forest_fires_dataset_UPDATE.csv
│
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## 🚀 How to Run the Project Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/dkumar0847607-ops/fire-detection-ml-app.git
cd fire-detection-ml-app
2️⃣ Create and activate virtual environment
Mac/Linux:
python3 -m venv .venv
source .venv/bin/activate
Windows:
python -m venv .venv
.venv\Scripts\activate
3️⃣ Install all dependencies
pip install -r requirements.txt
4️⃣ Run the Flask app
python application.py
5️⃣ Open the app in your browser
http://127.0.0.1:5000/
🧠 Model Information
The model uses:
Ridge Classifier
StandardScaler for feature normalization
Trained on:
Algerian Forest Fires Dataset (UCI)
Target classes:
1 → Fire
0 → Not Fire
📊 Features Used
Example features include:
Temperature
Relative Humidity
Wind Speed
Rain
FFMC, DMC, DC, ISI
Region
… and others depending on preprocessing.
🌐 Deployment (Optional)
You can deploy this app to:
Render
Railway
PythonAnywhere
Heroku (paid)
If you want deployment files (Procfile, runtime.txt, etc.), ask me.
✨ Future Improvements
Add interactive visualizations
Add multi-model comparison
Add API endpoint
Deploy live demo
🤝 Contributing
Pull requests are welcome.
For major changes, please open an issue first.
📜 License
This project is licensed under the MIT License.
👨‍💻 Author
Divyanshu Kumar
GitHub: dkumar0847607-ops

---

# 🎉 Done!
This README is clean, professional, and ready to paste.

If you want:
- A better folder structure  
- Badges (Python version, Flask, Model accuracy)  
- A preview screenshot  
- Deployment instructions  

Just tell me **“Add advanced README”**.


