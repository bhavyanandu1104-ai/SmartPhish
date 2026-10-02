# 🛡️ SmartPhish – Phishing URL Detection System

SmartPhish is a web-based phishing URL detection and security analysis system developed as a final-year BSc Computer Science project.

It analyzes website URLs for common suspicious characteristics and provides a risk classification. SmartPhish also uses VirusTotal-based online analysis to provide additional security information.

## 🎯 Objectives

- Detect suspicious characteristics in website URLs.
- Provide a simple risk classification.
- Show the reasons behind detected risks.
- Provide online URL reputation analysis.
- Help users understand common phishing warning signs.
- Promote safer browsing practices.

## ✨ Features

- 🔍 URL scanning
- ⚡ Fast rule-based detection
- 🔒 URL security analysis
- 📊 Risk score and risk classification
- 📋 Scan history
- 🦠 VirusTotal online analysis
- ℹ️ Phishing safety precautions
- 📱 Responsive web interface

## 🔎 Detection Checks

SmartPhish analyzes several URL characteristics:

1. HTTPS usage
2. URL length
3. `@` symbol
4. IP-address usage
5. Suspicious keywords
6. Multiple hyphens
7. Unusual dots
8. URL-shortening services
9. Excessive subdomains

The detected characteristics are combined into a risk score.

## 📊 Risk Classification

- 🟢 **Low Risk** – Few or no warning signs detected
- 🟡 **Suspicious** – Some warning signs detected
- 🔴 **High Risk** – Multiple warning signs detected

> SmartPhish is an educational security project and should not be treated as a guaranteed determination that a website is safe or malicious.

## 🛠️ Technologies Used

### Frontend

- HTML
- CSS
- JavaScript

### Backend

- Python
- Flask
- Flask-CORS
- Requests

### Security Analysis

- VirusTotal API

### Deployment

- GitHub Pages
- Render

## ⚙️ How SmartPhish Works

```text
User enters a URL
        ↓
SmartPhish analyzes URL characteristics
        ↓
Detection rules are applied
        ↓
Risk score is calculated
        ↓
Risk classification is displayed
        ↓
VirusTotal online analysis
        ↓
Security Analysis Report
