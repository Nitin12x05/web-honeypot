# 🐍 Web Honeypot – Flask-Based Honeypot for Cybersecurity Research

A simple Python-based web honeypot that mimics a login page and logs unauthorized access attempts. This project is designed for cybersecurity learning, penetration testing practice, and bug bounty training.

---

## 🚀 Features

- Simulated login portal (fake admin interface)
- Logs request data: IP, method, headers, form inputs
- Tracks unauthorized login attempts
- Deployable on ports 8080, 8000, and 8888
- Local log storage (`honeypot.log`) for incident analysis
- UFW firewall integration for basic port control

---

## 🛠️ Technologies Used

- **Python 3**
- **Flask**
- **HTML/CSS**
- **Linux (Ubuntu/Kali)**
- **UFW (Uncomplicated Firewall)**

---

## 📦 Installation & Usage

1. Clone the repo:

```bash
git clone https://github.com/yourusername/web-honeypot.git
cd web-honeypot
