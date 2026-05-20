# 🔐 Secure Password Manager with Encryption

A Python-based secure password manager that stores and manages user credentials using encryption to ensure privacy and data protection.

---

## 📌 Project Overview

This project is a CLI-based Password Manager built using Python. It allows users to securely store, retrieve, search, and delete passwords. All passwords are encrypted using strong symmetric encryption before being saved to a local JSON file.

---

## 🚀 Features

- 🔐 Master password authentication
- ➕ Add new credentials (Website, Username, Password)
- 🔎 Search saved credentials
- 📋 View all stored passwords
- ❌ Delete specific entries
- 🔑 Password encryption using Fernet
- 🎲 Strong password generator
- 💾 Persistent storage using JSON file
- ⚠️ Error handling for corrupted or missing data

---

## 🛠 Technologies Used

- Python 3.x  
- Cryptography Library (Fernet Encryption)  
- JSON for data storage  
- OS module for file handling  
- Random & String modules for password generation  

---

## 📁 Project Structure


SecurePasswordManager/
│
├── main.py
├── password_manager.py
├── encryption.py
├── auth.py
├── generator.py
├── requirements.txt
│
├── data/
│ └── passwords.json
│
├── keys/
│ └── secret.key
│
└── README.md


---

## ⚙️ Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/your-username/SecurePasswordManager.git
cd SecurePasswordManager
2. Install Dependencies
pip install -r requirements.txt
3. Run the Application
python main.py
🔐 Security Features
Passwords are encrypted using Fernet symmetric encryption
Encryption key is stored separately in keys/secret.key
No plain-text passwords are saved
Master password required to access system
🧪 How It Works
User logs in with master password
System loads encrypted data from JSON file
Passwords are encrypted before saving
Decryption happens only when viewing/searching data
Data is safely stored locally
📸 Example Output
===== Secure Password Manager =====
Enter Master Password: ******
Access Granted!

===== MENU =====
1. Add New Password
2. View Saved Passwords
3. Search Credentials
4. Delete Entry
5. Generate Strong Password
6. Exit
🎯 Future Improvements
GUI version using Tkinter
Clipboard copy with auto-clear
Auto-lock after inactivity
Database (SQLite) integration
Hashed master password (bcrypt)
👨‍💻 Author

Developed as part of a Python security project assignment.

📄 License

This project is for educational purposes only.
