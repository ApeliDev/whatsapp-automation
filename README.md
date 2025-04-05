# WhatsApp Automation Script

## 📌 Overview
This project automates sending messages on WhatsApp Web using Selenium and a Tkinter-based GUI for user interaction. It ensures smooth login and navigation through WhatsApp Web while providing logging for troubleshooting.

## 🛠 Features
- Automates sending messages to WhatsApp groups or contacts.
- Uses a GUI confirmation pop-up for user login.
- Handles different search box selectors for improved reliability.
- Logs automation activity for debugging.

---

## 🚀 Installation
### Prerequisites
Ensure you have the following installed:
- **Python 3.x**
- **Google Chrome**
- **Chrome WebDriver** (compatible with your Chrome version)
- Required Python libraries:

```bash
pip install selenium tkinter pyperclip pillow
```

---

## 💻 Usage
### 1️⃣ Run the Script
```bash
python script.py
```

### 2️⃣ WhatsApp Web Login
- The script will open WhatsApp Web.
- Scan the QR code using your phone.
- Click "Confirm Login" on the GUI to proceed.

### 3️⃣ Message Sending
- The script searches for a contact/group.
- Sends a predefined message.

---

## 📝 Configuration
### **Set ChromeDriver Path**
Update the following line in the script to point to your `chromedriver.exe`:
```python
chromedriver_path = "path/to/chromedriver"
```

### **Modify Message Content**
Edit the message inside the script:
```python
message = "Hello, this is an automated message!"
```

---

## 🔧 Troubleshooting
### ❌ Common Issues & Fixes
| Issue | Solution |
|--------|----------|
| ChromeDriver version mismatch | Update to match Chrome version |
| Search box not found | Ensure WhatsApp Web is loaded correctly |
| Messages not sending | Check if the recipient exists |
| Script crashes | Review logs in `whatsapp_automation_*.log` |

---

## 📸 Screenshots
Here are some screenshots of the project in action:

### WhatsApp Web Login Screen
![image](https://github.com/user-attachments/assets/f834eed6-2be6-4f66-9d58-0b1ad8ecf8e1)

### Log Output Example
![image](https://github.com/user-attachments/assets/3326f3e8-ae36-4e7b-8108-57873d6eef34)

---
## 📞 Contact Information  
Need help? Reach out to us!  

📧 **Email:** [apelinifa@gmail.com](mailto:apelinifagmail.com)  
📱 **Phone:** [+254 743161167](tel:+254743161167)  


## 👨‍💻 Author
**Apeli** 🚀

---

## 🐝 License
This project is licensed under the MIT License.

