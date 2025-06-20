# 🔐 Keylogger Demonstration Project 🖥️

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-green?logo=flask)
![License](https://img.shields.io/badge/License-MIT-yellow)
![GitHub stars](https://img.shields.io/github/stars/Durga939282/Keylogger-Demonstration?style=social)

Welcome to the **Keylogger Demonstration** project! 🚀 This educational tool showcases a keylogger implementation and detection system using Python, Flask, and a web interface. Designed for **learning purposes only**, it demonstrates how keyloggers work and how to detect them, promoting cybersecurity awareness.

> ⚠️ **Disclaimer**: This project is strictly for **educational purposes**. Unauthorized use of keyloggers is **illegal** and **unethical**. Always obtain explicit consent and comply with all applicable laws and ethical guidelines. Misuse may result in legal consequences.

---

## 🎯 Project Overview

The Keylogger Demonstration project provides a web-based platform to:
- **Simulate a keylogger** that captures keystrokes and logs them to `keyfile.txt`.
- **Detect running keyloggers** on the system using process scanning.
- **Control and visualize** the keylogger through an interactive web interface built with Flask.

### Key Features
- 🕹️ **Keylogger Control**: Start/stop the keylogger via a user-friendly web UI.
- 🔍 **Keylogger Detection**: Scan for suspicious processes indicating keylogger activity.
- 📊 **Real-Time Feedback**: Display keylogger status and detection results dynamically.
- 📁 **Log Management**: Keystrokes are saved to `keyfile.txt` for review.
- 🎨 **Modern UI**: Responsive, colorful design using custom CSS.

---

## 🛠️ Technologies Used

- **Python 3.8+**: Core programming language for backend logic.
- **Flask**: Web framework for serving the UI and API endpoints.
- **pynput**: Library for capturing keyboard inputs.
- **psutil**: Library for process monitoring and detection.
- **HTML/CSS/JavaScript**: Frontend for the web interface.

---

## 📂 Project Structure

```plaintext
Keylogger-Demonstration/
│
├── static/
│   ├── detector.js        # JavaScript for keylogger detection page
│   ├── keylogger.js       # JavaScript for keylogger control
│   ├── script.js          # General JavaScript utilities
│   └── styles.css         # CSS for styling the web interface
│
├── templates/
│   ├── detector.html      # HTML for keylogger detection page
│   ├── index.html         # HTML for homepage
│   └── keylogger.html     # HTML for keylogger control page
│
├── keyfile.txt            # File where keystrokes are logged
├── keylogger.py           # Keylogger implementation
├── keylogger_detector.py  # Keylogger detection logic
├── server.py              # Flask server for web interface
├── launch.json            # VS Code debug configuration
├── .gitignore             # Git ignore file for sensitive data
└── README.md              # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites
- Python 3.8 or higher
- Git installed
- A code editor (e.g., VS Code)
- Basic knowledge of Python and Flask

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Durga939282/Keylogger-Demonstration.git
   cd Keylogger-Demonstration
   ```

2. **Create a Virtual Environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install flask pynput psutil
   ```

4. **Run the Application**:
   ```bash
   python server.py
   ```
   - Open your browser and navigate to `http://127.0.0.1:5000`.

---

## 🖱️ Usage

1. **Homepage**:
   - Access at `http://127.0.0.1:5000`.
   - Navigate to **Keylogger** or **Detector** sections.

2. **Keylogger Section**:
   - Click **Start Keylogger** to capture keystrokes.
   - Keystrokes are saved to `keyfile.txt`.
   - Click **Stop Keylogger** to halt capturing.
   - View the log file path and status.

3. **Detector Section**:
   - Click **Start Scan** to detect potential keyloggers.
   - View detected processes (PID, name, path).
   - Terminate suspicious processes (except the current process) with the **Terminate** button.

---

## 📸 Screenshots

> **Note**: Upload actual screenshots to an `assets/` folder in your repository (e.g., `assets/homepage.png`) or an external host (e.g., Imgur) and update the URLs below.

### Homepage
![Screenshot (43)](https://github.com/user-attachments/assets/2f5de789-26ce-4eb8-aa76-4b2f523b1cf3)


### Keylogger Control
![Screenshot (44)](https://github.com/user-attachments/assets/ce0504b1-712f-4011-9dad-a89dfcb09cab)


### Detector Results
![Screenshot (45)](https://github.com/user-attachments/assets/72e8131d-3d76-4aeb-bfae-4e42904f6e28)


---

## 🔐 Ethical Considerations

- This project is for **educational and demonstration purposes only**.
- **Do not use** this code to harm systems or networks.
- Always obtain **explicit permission** before testing on any system.
- Ensure compliance with **local laws and regulations**.
- The `keyfile.txt` file may contain sensitive data; ensure it’s included in `.gitignore` to prevent accidental commits.

---

## 🛠️ Troubleshooting

- **Keylogger not starting**:
  - Ensure `pynput` is installed (`pip install pynput`).
  - Check for keyboard input permissions (e.g., run as administrator on Windows).

- **Detector not finding processes**:
  - Verify `psutil` is installed (`pip install psutil`).
  - Some processes may require elevated privileges.

- **Server not running**:
  - Confirm Flask is installed (`pip install flask`).
  - Check if port `5000` is free or change it in `server.py`.

- **Git push errors**:
  - If you see `src refspec main does not match any`:
    ```bash
    git add .
    git commit -m "Initial commit"
    git push -u origin main
    ```
  - Ensure authentication with a [Personal Access Token](https://github.com/settings/tokens) or SSH.

---

## 🤝 Contributing

Contributions are welcome! 🙌 To contribute:
1. Fork the repository.
2. Create a branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m "Add feature"`).
4. Push to your fork (`git push origin feature-branch`).
5. Open a Pull Request.

---



## 🙏 Acknowledgments

- Thanks to the open-source community for libraries like Flask, pynput, and psutil.
- Inspired by cybersecurity education and ethical hacking demonstrations.

---

## 📬 Contact

- **GitHub**: [Durga939282](https://github.com/Durga939282)

⭐ **Star this repository** if you found it helpful! Let’s promote cybersecurity awareness! 🌟
