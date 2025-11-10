# 🔍 UPI Fraud Detection System  

A Machine Learning web application built with **Flask**, **Python**, and **Scikit-learn**, designed to detect potential **fraudulent UPI transactions** in real time.  

This project applies classification algorithms and data preprocessing to analyze transaction behavior and identify anomalies, helping prevent digital payment frauds.  

---

## 🚀 Live Demo  
👉 **[View Project Live](https://bhanuja11.github.io/UPI-Fraud-Detection-System/)**  
> *(Note: If hosted locally via Flask, run `python app.py` and visit `http://127.0.0.1:5000`.)*

---

## 🧠 Features  

✅ Detects potential UPI fraud using machine learning models  
✅ Interactive web interface built with **Flask**  
✅ Real-time prediction via trained **Random Forest Classifier**  
✅ Data preprocessing, encoding, and scaling using **pandas** and **scikit-learn**  
✅ Clear visualization of model accuracy and confusion matrices  
✅ Responsive HTML/CSS interface  

---

## 🧰 Tech Stack  

**Frontend:** HTML5, CSS3, Bootstrap  
**Backend:** Python, Flask  
**Machine Learning:** Scikit-learn, Pandas, NumPy, Joblib  
**Visualization:** Matplotlib, Seaborn  

---

## 📂 Project Structure  

UPI-Fraud-Detection-System/
├── static/
│ └── styles.css
├── templates/
│ └── index.html
├── 4algos.py
├── app.py
├── upi_fraud_dataset.csv
├── rf_model.pkl
├── requirements.txt
└── README.md

---

## ⚙️ How to Run Locally  

1. Clone the repository:  
   ```bash
   git clone https://github.com/bhanuja11/UPI-Fraud-Detection-System.git
   cd UPI-Fraud-Detection-System
   
2. Install dependencies:
   pip install -r requirements.txt

3. Run the app:
   python app.py

4. Open your browser and visit:
   http://127.0.0.1:5000

📊 Model Training

The dataset (upi_fraud_dataset.csv) is processed and trained using the following models:

1.Random Forest Classifier
2.Logistic Regression
3.Decision Tree
4.Support Vector Machine

Random Forest achieved the highest accuracy (~94%) during testing.

🧾 Output Example

The app predicts:
Fraud → suspicious UPI transaction
Not Fraud → safe transaction

👩‍💻 Author

Bhanuja Maddi
Aspiring Software Engineer | Full Stack Developer | Cloud Enthusiast

📧 maddibhanuja@gmail.com

⭐ Acknowledgment

Special thanks to the open-source community and resources that helped in building this project.

If you find this project useful, don’t forget to ⭐ star the repo and share feedback!
