# 🏥 Hospital AI Intelligence Dashboard

![Dashboard Preview](file:///C:/Users/SHREEJA/Downloads/hospital_dashboard%20(1).html)

## 📌 Project Overview
A Real-time Hospital Patient Management System 
that uses Machine Learning to predict patient 
discharge probability and Groq AI API for 
intelligent insights.

## 🚀 Live Demo
[Click here to view Dashboard](file:///C:/Users/SHREEJA/Downloads/hospital_dashboard%20(1).html)

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, JavaScript, Chart.js
- **ML Model**: Random Forest Classifier (87.3% accuracy)
- **AI API**: Groq API (llama3-8b-8192)
- **Dashboard**: Power BI Style Charts
- **Backend**: Python, Flask

## 📊 Key Metrics
| Metric | Value |
|--------|-------|
| Daily Admissions | 247 patients |
| Discharge Rate | 76.5% |
| ML Accuracy | 87.3% |
| AUC Score | 0.91 |
| Bed Occupancy | 78% |

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/YourName/hospital-ai-dashboard.git
cd hospital-ai-dashboard
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Add your Groq API key
```python
# In api/groq_api.py
GROQ_API_KEY = "your_groq_api_key_here"
```

### 4. Run the app
```bash
python api/app.py
```

### 5. Open dashboard
Open `file:///C:/Users/SHREEJA/Downloads/hospital_dashboard%20(1).html` in browser

## 🤖 ML Model Details
- **Algorithm**: Random Forest Classifier
- **Training Data**: 50,000+ patient records
- **Features**: Severity, Days, Age, Department, Insurance
- **Accuracy**: 87.3%

## 🔑 Groq API Setup
1. Get free API key: https://console.groq.com
2. Add key to `api/groq_api.py`
3. Model: `llama3-8b-8192`

## 👨‍💻 Author
Shreeja Gupta 
- GitHub: [@Shreejaahh](https://github.com/Shreejaahh)
- LinkedIn: [https://linkedin.com/in/shreeja-gupta-647527361](https://linkedin.com/in/shreeja-gupta-647527361)


