# 🔐 Phixora AI – AI-Based Phishing Detection

Phixora AI is an AI-based web application designed to detect potentially **phishing emails** and help users identify suspicious email content.

The system analyzes important email and domain-related features and classifies the input as **Phishing, Legitimate, or Suspicious**.

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

* **Python**
* **Flask**
* **Machine Learning**
* **HTML**
* **CSS**
* **JavaScript**
* **Pandas**
* **NumPy**
* **Joblib**

## 🔎 Detection Features

Phixora AI uses different domain-related features during detection, including:

* Domain length
* Number of subdomains
* Number of hyphens
* Number of digits
* Email content and related information

These features are processed by the machine learning model to generate a detection result.

## 📁 Project Structure

```text
Phixora-AI/
│
├── app.py
├── requirements.txt
├── README.md
│
├── models/
│   └── phishing_detection_model.pkl
│
├── templates/
│   ├── landing.html
│   └── main.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── ...
```

> The exact folder structure may vary depending on the final version of the project.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Roshnikashyap/Phixora-AI.git
```

### 2. Open the project folder

```bash
cd Phixora-AI
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install the required packages

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

Then open the local URL shown in the terminal, usually:

```text
http://127.0.0.1:5000/
```

## 🖥️ How It Works

1. Open the Phixora AI application.
2. Enter email information manually or upload an email file.
3. The system extracts relevant information and features.
4. The trained machine learning model analyzes the input.
5. The application displays the detection result.
6. The result is categorized as **Phishing, Legitimate, or Suspicious**.

## 🎯 Purpose

The main purpose of Phixora AI is to provide a simple and user-friendly way to analyze suspicious emails and increase awareness about phishing threats.

## 🚀 Future Improvements

* Improve model accuracy with a larger and more diverse dataset
* Add more email and URL-based features
* Add detailed explanations for detection results
* Improve detection of different phishing techniques
* Deploy the application online
* Add user authentication and secure scan history

## 👩‍💻 Author

**Roshni Kashyap**

MCA Student
G H Raisoni Skill Tech University, Nagpur

---

