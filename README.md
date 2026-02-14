# 🔐 Phishing & Malicious URL Detection using Machine Learning

## 📌 Project Overview

This project is a **Cybersecurity + Machine Learning** based system that detects whether a website URL is **SAFE or MALICIOUS (Phishing/Malware)**.

Cyber criminals often create fake websites (bank login pages, PayPal, Instagram, etc.) to steal user credentials.
This tool analyzes a given URL and predicts the risk level using a trained Machine Learning model.

The system works similar to basic browser security filters and antivirus web protection.

---

## 🎯 Objectives

* Detect phishing websites
* Identify suspicious URL patterns
* Prevent users from visiting dangerous links
* Demonstrate practical application of cybersecurity concepts

---

## 🧠 How It Works

The model does **feature-based security analysis** instead of simply memorizing links.

It extracts security indicators from URLs such as:

* URL length
* Presence of IP address in URL
* HTTPS usage
* Suspicious characters (`-`, `?`, `=`, `@`)
* Number of digits in URL
* Domain length

Then a **Random Forest Machine Learning model** classifies the website as:

* ✅ Benign (Safe)
* ⚠️ Malicious (Phishing / Malware / Defacement)

---

## 🧪 Example

```
Enter a website URL (or type 'exit'): http://paypal-security-update-login.com

⚠️ WARNING: This website is MALICIOUS or PHISHING
Risk Score: 92.41 % dangerous
```

```
Enter a website URL (or type 'exit'): https://google.com

✅ SAFE: This website appears legitimate
Risk Score: 3.18 % dangerous
```

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Scikit-Learn
* Pandas
* NumPy
* tldextract
* Machine Learning (Random Forest Classifier)

---

## 📊 Dataset

Malicious URL dataset from Kaggle containing:

* Benign URLs
* Phishing URLs
* Malware URLs
* Defacement URLs

---

## ⚙️ Installation

1. Clone the repository

```
git clone https://github.com/your-username/URL-Phishing-Detector.git
cd URL-Phishing-Detector
```

2. Install dependencies

```
pip install pandas numpy scikit-learn matplotlib seaborn tldextract requests
```

3. Place the dataset file `malicious_phish.csv` in the project folder.

DOWNLOAD the data set from kaggle.com

5. Run Jupyter Notebook

```
jupyter notebook
```

5. Open:

```
CyberSecurity_URL_Detector.ipynb
```

Run all cells and start testing URLs.

---

## 🚀 Features

* Real-time URL checking
* Risk percentage score
* Machine learning classification
* Interactive user input
* Beginner-friendly cybersecurity tool

---

## 📚 Cybersecurity Concepts Covered

* Phishing attacks
* Social engineering
* URL spoofing
* Web security analysis
* Threat detection using AI

---

## 🔮 Future Improvements

* Browser extension integration
* Android application
* Email phishing detection
* Live website content analysis

---

## 👨‍💻 Author

**Ankit Kumar Panda**
Aspiring Cybersecurity & AI Engineer

---

## ⭐ If you found this useful

Please give this repository a star!
