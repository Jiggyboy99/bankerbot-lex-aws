# BankerBot – Amazon Lex Chatbot with CloudFormation Deployment

This project is an intelligent banking chatbot built with **Amazon Lex**, **AWS Lambda**, and **CloudFormation**.  
It handles **balance checks** and **fund transfers between accounts** using multi-slot intents, a confirmation flow, and automated deployment.

---

## 🚀 Features
- Multi-slot intent for money transfer (`sourceAccountType`, `targetAccountType`, `transferAmount`)
- Shared custom slot type `accountType`
- Confirmation prompt before executing transfers
- AWS Lambda fulfillment (Python 3.12)
- CloudFormation template for one-click deployment

---

## 🧩 Tech Stack
- Amazon Lex V2
- AWS Lambda
- AWS CloudFormation (YAML)
- Python 3.12
- CloudWatch for logging

---

## 🧠 How to Deploy
1. Upload the `bankerbot-template.yaml` to **AWS CloudFormation**.
2. Wait for stack creation to complete.
3. Go to **Amazon Lex Console** and test your bot.
4. Edit Lambda logic to add real fulfillment code.

---

## 📸 Demo
See `/demo` folder for screenshots of intents, slot setup, and deployment.

---

Made with ❤️ by [Oluwatobi Akinloye](https://www.linkedin.com/in/akinloye-oluwatobiloba-b83756286/)

