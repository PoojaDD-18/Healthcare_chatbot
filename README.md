🏥 Healthcare Chatbot using Machine Learning
📌 Project Overview

The Healthcare Chatbot is a machine learning–based intelligent system designed to predict possible diseases based on user-provided symptoms. The chatbot interacts with users in a conversational format, asks follow-up questions, evaluates symptom severity, and provides disease descriptions and precautionary measures.

This project uses Decision Tree and Support Vector Machine (SVM) algorithms trained on medical symptom datasets to achieve high prediction accuracy.

🎯 Features

Interactive chatbot-based symptom input

Disease prediction using Machine Learning

Secondary prediction logic for better accuracy

Severity-based health risk analysis

Disease description and precaution suggestions

Voice output support using pyttsx3

High accuracy (97%–100%)

🧠 Machine Learning Models Used

Decision Tree Classifier (Primary model)

Support Vector Machine (SVM) (For comparison)

📊 Model Performance
Model	Accuracy
Decision Tree (Training)	100%
Decision Tree (Cross Validation)	~97.7%
Support Vector Machine	100%
📂 Dataset Details

The project uses the following CSV files:

Training.csv – Dataset used for training the models

Testing.csv – Dataset used for testing

Symptom_severity.csv – Severity score for each symptom

symptom_Description.csv – Description of diseases

symptom_precaution.csv – Precautionary measures for diseases

⚙️ Technologies & Libraries

Programming Language: Python

Libraries:

Pandas

NumPy

Scikit-learn

pyttsx3

re (Regular Expressions)

🖥️ How the System Works

User enters their name

User inputs the main symptom

Chatbot suggests related symptoms

User selects the correct symptom

User provides the number of days symptoms are experienced

Chatbot asks additional yes/no symptom questions

Machine Learning model predicts the disease

Chatbot displays:

Predicted disease(s)

Disease description(s)

Severity-based consultation advice

Precautionary measures

💻 Sample Output
-----------------------------------HealthCare ChatBot-----------------------------------

Your Name? -> pooja
Hello, pooja

Enter the symptom you are experiencing -> fever
searches related to input:
0 ) high_fever
1 ) mild_fever
Select the one you meant (0 - 1): 0

Okay. From how many days ? : 7

You should take the consultation from doctor.
You may have Typhoid or Peptic ulcer disease

Take following measures :
1 ) eat high calorie vegetables
2 ) antibiotic therapy
3 ) consult doctor
4 ) medication
----------------------------------------------------------------------------------------

🚀 Installation & Execution
Step 1: Clone the Repository
git clone https://github.com/your-username/Healthcare-Chatbot.git
cd Healthcare-Chatbot

Step 2: Install Required Libraries
pip install pandas numpy scikit-learn pyttsx3

Step 3: Run the Application
python health.py

📁 Project Structure
Healthcare-Chatbot/
│
├── health.py
├── Training.csv
├── Testing.csv
├── Symptom_severity.csv
├── symptom_Description.csv
├── symptom_precaution.csv
└── README.md

🎓 Use Cases

Healthcare assistance systems

Disease prediction tools

Machine Learning academic projects

College mini / major projects

⚠️ Disclaimer

This project is developed only for educational purposes.
It is not a replacement for professional medical advice or diagnosis.

👩‍💻 Author

Pooja Daydar
B.Tech – Information Technology
