# 🔐 Phixora AI – AI-Based Phishing Detection

Phixora AI is an AI-based web application designed to detect potentially **phishing emails** and help users identify suspicious email content.

The system analyzes email and domain-related features and classifies the input as **Phishing, Legitimate, or Suspicious**.

## ✨ Features

* 🔍 Detects potentially phishing emails
* 📧 Supports manual email text analysis
* 📂 Supports `.eml`, `.msg`, and `.txt` email files
* 🛡️ Analyzes email and domain-related features
* ⚠️ Provides three detection results:

  * Phishing
  * Legitimate
  * Suspicious
* 📊 Displays scan statistics and history
* 🌐 User-friendly web interface
* 🤖 Uses a Machine Learning model for detection

## 🛠️ Technologies Used

* Python
* Flask
* Machine Learning
* HTML
* CSS
* JavaScript
* Pandas
* NumPy
* Joblib

## 🔎 Detection Features

The system uses different domain-related features during detection, including:

* Domain length
* Number of subdomains
* Number of hyphens
* Number of digits
* Email-related information

These features are processed by the machine learning model to generate a detection result.

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Roshnikashyap/Phixora-AI.git
```

### 2. Open the project folder

```bash
cd Phixora-AI
```

### 3. Install the required packages

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

Then open the local URL shown in the terminal, usually:

```text
http://127.0.0.1:5000/
```

## 🎯 Project Objective

The main objective of Phixora AI is to provide a simple and user-friendly way to analyze suspicious emails and increase awareness about phishing threats.

## 🚀 Future Improvements

* Improve model accuracy with a larger dataset
* Add more email and URL-based features
* Provide detailed explanations for detection results
* Improve detection of different phishing techniques
* Deploy the application online

## 👩‍💻 Author

**Roshni Kashyap**

MCA Student
G H Raisoni Skill Tech University, Nagpur
