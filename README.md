# Serverless Email API

## Project Overview
**Serverless Email API** is a lightweight REST API built with **Python** and **Serverless Framework**.  
It allows sending emails via **SMTP** without managing any server.  
The project demonstrates **serverless architecture**, **environment variable management**, and **local API testing**.

---

## Key Features
- Send emails using a simple **POST request**.
- Uses **.env file** for secure storage of sensitive credentials.
- Fully **serverless architecture** – no server management required.
- Local testing via **Serverless Offline**.
- Proper **error handling** and **JSON response**.

---

## Technologies Used
- **Python** – Backend language  
- **Serverless Framework** – Function deployment & local simulation  
- **SMTP** – Sending emails securely  
- **python-dotenv** – Environment variable management  
- **Postman** – API testing  

---

## Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/karan705014/serverless_email_app.git
cd serverless_email_app/myservice

Create virtual environment 

python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate # Linux/Mac



Install dependencies

pip install -r requirements.txt




Install Serverless Framework

npm install -g serverless


Create .env file:

SENDER_EMAIL=your_email@gmail.com
SENDER_PASSWORD=your_app_password
