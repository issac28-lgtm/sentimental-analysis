🧠 Mental Health Prediction Using Social Media Analytics
📌 Project Description

This project focuses on predicting mental health conditions by analyzing social media text using Natural Language Processing (NLP) and Machine Learning techniques.
The system classifies user-generated text as indicating mental health risk (depression/stress) or normal mental state.

🎯 Objectives

Analyze social media posts using NLP techniques

Detect early signs of mental health issues

Build a machine learning model for text classification

Provide real-time prediction for user input

🛠️ Technologies Used

Programming Language: Python

Libraries: Pandas, NLTK, Scikit-learn

NLP Techniques: Text Cleaning, Stopword Removal, Lemmatization

Feature Extraction: TF-IDF Vectorizer

Machine Learning Model: Logistic Regression

📂 Project Structure
Mental_Health_Prediction/
│
├── dataset.csv
├── mental_health_prediction.py
├── README.md

📊 Dataset Description

Format: CSV file

Columns:

text – Social media post or user message

label – Mental health condition

1 → Mental Health Risk (Depressed / Stressed)

0 → Normal Mental State

Example:

text,label
"I feel sad and lonely",1
"I am happy and motivated",0

⚙️ How It Works

Load and preprocess social media text

Clean text using NLP preprocessing

Convert text to numerical features using TF-IDF

Train a Logistic Regression classifier

Predict mental health condition for new input

▶️ How to Run the Project
1️⃣ Install Dependencies
pip install pandas nltk scikit-learn

2️⃣ Run the Program
python mental_health_prediction.py

3️⃣ Enter Text for Prediction
Enter a social media post:
I feel hopeless and tired

📈 Output

Mental Health Risk Detected
or

No Mental Health Risk Detected

🧪 Sample Output
Prediction: ⚠ Mental Health Risk Detected (Depressed)

🚀 Applications

Early mental health risk detection

Social media monitoring

Healthcare and wellness platforms

Academic and research purposes

⚠️ Disclaimer

This project is for educational purposes only and should not be used as a replacement for professional mental health diagnosis.

👨‍🎓 Developed By

Final Year AI & Data Science Student
Academic Project

⭐ Future Enhancements

Deep Learning models (LSTM, BERT)

Multi-class classification (Anxiety, Stress, Depression)

Web application using Flask

Real-time social media data integration
