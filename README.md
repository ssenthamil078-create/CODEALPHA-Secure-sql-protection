# 🔐 Cloud-Based Secure Data Protection System

A secure cloud-based web application designed to **prevent SQL injection attacks**, protect sensitive data using **AES-256 encryption**, and ensure safe database operations with a **double-layer security mechanism**.

---

## 📌 Project Overview

This project focuses on securing user data in web applications by preventing SQL injection attacks and encrypting sensitive information before storing it in the database.

The system is deployed on the cloud and designed to be lightweight, secure, and scalable.

---

## 🎯 Objectives

- Prevent SQL injection attacks  
- Secure user data using AES-256 encryption  
- Implement capability-based secure access  
- Provide double-layer security mechanism  
- Deploy system on cloud for remote access  

---

## ✨ Key Features

- 🔐 **AES-256 Encryption** for sensitive data storage  
- 🛡️ **SQL Injection Prevention** using parameterized queries  
- 🔑 **Secure Authentication System**  
- 🧠 **Capability Code Mechanism** for controlled access  
- 🧾 **Secure Data Input Module**  
- 📊 **Admin Dashboard for Monitoring**  
- ☁️ **Cloud Deployment (AWS EC2)**  

---

## 🏗️ System Architecture

User → Web Interface → Flask Backend → Secure Query Layer → MySQL Database → Cloud Server (AWS EC2)

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap  
- **Backend:** Python (Flask)  
- **Database:** MySQL  
- **Security:** AES-256 (Cryptography), Input Validation  
- **Cloud:** AWS EC2  

---

## 🔐 Security Implementation

### 1. SQL Injection Prevention
- Used **parameterized queries** instead of raw SQL  
- Prevents malicious inputs like:
  ```sql
  ' OR '1'='1
2. AES-256 Encryption
Sensitive data encrypted before storing in database
Decrypted only when required
3. Double Layer Security
Input validation + encrypted storage
Reduces risk of data leakage
4. Capability Code System
Access control using special secure codes
Restricts unauthorized operations
⚙️ Installation & Setup
1. Clone Repository
git clone https://github.com/your-username/secure-data-system.git
cd secure-data-system
2. Create Virtual Environment
python -m venv myenv
source myenv/bin/activate   # Linux
myenv\Scripts\activate      # Windows
3. Install Requirements
pip install -r requirements.txt
4. Setup MySQL Database
Create database (e.g., securedb)
Create required tables
5. Configure Database

Update config.py:

MYSQL_HOST = 'localhost'
MYSQL_USER = 'root'
MYSQL_PASSWORD = 'your_password'
MYSQL_DB = 'securedb'
6. Run Application
python app.py
<img width="1920" height="1080" alt="Screenshot (97)" src="https://github.com/user-attachments/assets/5289bc6b-73b5-4f61-8692-aaf888b165bd" />
<img width="1920" height="1080" alt="Screenshot (94)" src="https://github.com/user-attachments/assets/c44eac24-f645-410e-839f-0d1c6710de66" />
<img width="1920" height="1080" alt="Screenshot (95)" src="https://github.com/user-attachments/assets/3e59f19a-eec1-49f0-a38c-2f9731baef27" />
<img width="1920" height="1080" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/aace8ae7-e211-4f8f-8f2a-5abd44c7f04e" />
<img width="1920" height="1080" alt="Screenshot (93)" src="https://github.com/user-attachments/assets/505425af-f526-41ab-b3b7-a42ebc71fb5e" />
