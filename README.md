# 🔐 Password Checker 🐍

🚀 A simple yet powerful Python script to check how many times your password has been hacked or used before! This tool leverages the Pwned Passwords API to ensure your credentials remain secure. 🔒

## 📜 Features
✅ Checks if a password has been compromised
✅ Uses the Pwned Passwords API securely
✅ Easy-to-use command-line interface
✅ Fast and efficient

---

## 🛠️ How to Use

### 📌 Prerequisites
Ensure you have Python 3 installed on your system. 🐍

### 📥 Installation
Clone this repository and navigate into the project directory:
```bash
$ git clone https://github.com/prabhatadvait/Password-Checker.git
$ cd Password-Checker
```

### ▶️ Running the Script
To check if a password has been compromised, run:
```bash
$ python3 password_check.py <your-password>
```
Example:
```bash
$ python3 password_check.py hello
```
🔍 This will check if the password "hello" has been leaked and how many times it has been used.

⚠️ **Note:** Avoid using your real passwords in the terminal. Instead, test weak passwords for security awareness.

---

## 🖥️ Example Output
```
Password "hello" has been found 3,290,324 times! ⚠️
Choose a stronger password.
```
OR
```
Password "securepassword123!" was NOT found. ✅
Looks like a safe choice!
```

---

## 🔒 Security Notice
This script hashes the password before sending it to the API, ensuring privacy. Your full password is never exposed over the internet. 🛡️

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing
Feel free to submit issues and pull requests to enhance the project!

🔗 **GitHub Repository:** [Password Checker](https://github.com/prabhatadvait/Password-Checker)
