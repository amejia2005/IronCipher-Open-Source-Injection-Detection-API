# IronCipher-Open-Source-Injection-Detection-API
IronCipher – A Django-based open source project for detecting injection attacks and malicious file uploads. (Showcase only, no public code)

This repository serves as a showcase for **IronCipher**, a Django-based open source project focused on **injection detection and file security**.  
The source code is kept private for security reasons, but this page documents the project and links to the live deployment.

🔗 **Live Demo:** [ironcipher.pythonanywhere.com](https://ironcipher.pythonanywhere.com/)

---

## 🚀 About the Project
IronCipher is a cybersecurity-focused web application designed to detect and mitigate common injection attacks as well as malicious file uploads.

Key features include:
- **Injection Detection:** Identifies SQL, XML, JS, HTML, and CSS injections from user-submitted text inputs.
- **File Analysis:** Scans uploaded images and PDFs for embedded malicious code.
- **OAuth2 Integration:** Protects endpoints and ensures secure user authentication.
- **Threat Flagging:** Backend logic prioritizes suspicious requests for further analysis.
- **Request Security:** Limits repeated requests from the same IP and requires a **request code** on each POST request to ensure safe interactions.

The project was built with **Django** and integrates both real-time input validation and file inspection capabilities to provide early-stage threat detection.

---

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Security:** OAuth2, injection detection algorithms, IP rate limiting, POST request codes
- **Deployment:** PythonAnywhere
- **File Handling:** Secure parsing for images & PDFs

---

## 📄 Project Context
This is a **personal open source project**, built by applying knowledge from:
- **SI 364**: Building Data Driven Web Applications  
- **EECS 388**: Introduction to Computer Security  

For more details, visit the project documentation here:  
👉 [https://ironcipher.pythonanywhere.com/home/docs/](https://ironcipher.pythonanywhere.com/home/docs/)

---

## ⚠️ Disclaimer
This repository is for **showcasing purposes only**. The source code is not publicly available to ensure security and prevent misuse.
