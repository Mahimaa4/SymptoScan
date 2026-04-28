# 🩺 SymptoScan

SymptoScan is an AI-powered disease prediction system that analyzes user symptoms and predicts possible diseases using Deep Learning. It also provides health recommendations and Explainable AI insights to improve transparency and trust.

## 🚀 Features

- Symptom-based disease prediction
- Deep Learning model for classification
- Explainable AI (XAI) for prediction transparency
- AI health recommendation assistant
- Prediction history tracking
- Model evaluation metrics and confusion matrix

## 🛠 Tech Stack

- Python
- Flask
- TensorFlow / Keras
- Scikit-learn
- MongoDB
- HTML, CSS, JavaScript

## 📂 Project Structure

```text
SymptoScan/
│── app.py
│── predict.py
│── train_model.py
│── model_evaluation.py
│── health_agent.py
│── explainer.py
│── data/
│── static/
│── templates/
│── .gitignore
```

## ⚙ Installation

### Clone repository

```bash
git clone https://github.com/your-username/SymptoScan.git
cd SymptoScan
```

### Create virtual environment

```bash
python -m venv venv
```

Activate:

Windows:
```bash
venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Setup environment variables

Create `.env` file:

```env
MONGO_URI=your_mongodb_uri
GROQ_API_KEY=your_api_key
```

### Run application

```bash
python app.py
```

Open:
```text
http://127.0.0.1:5000/
```

## 🧠 How it works

1. User selects symptoms  
2. Model predicts disease probability  
3. XAI explains key contributing symptoms  
4. AI agent provides recommendations  
5. Results are stored in MongoDB  

## 📊 Model Performance

- Accuracy: 96%
- Precision: 96.5%
- Recall: 96%
- F1 Score: 96%

## 🔒 Security

Sensitive data like API keys and database credentials are stored securely using environment variables.

## 📌 Future Improvements

- Cloud deployment
- Better dataset expansion
- Real-time chatbot integration
- Advanced medical analytics

## 👩‍💻 Author

Mahima
B.Tech AIML Student
