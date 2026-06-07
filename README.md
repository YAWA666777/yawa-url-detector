# YAWA URL Detector

[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Security](https://img.shields.io/badge/security-VirusTotal-brightgreen.svg)](https://www.virustotal.com/)

**YAWA URL Detector** is a high-performance, multi-threaded threat intelligence tool designed to analyze suspicious URLs in real-time. By leveraging the VirusTotal API v3, this application provides users with actionable security insights, helping identify potential phishing, malware, or malicious domains directly from their desktop.

---

## Key Features

* **Intelligent Analysis:** Real-time integration with VirusTotal’s comprehensive threat database.
* **Asynchronous Processing:** Multi-threaded architecture ensures the GUI remains fluid and responsive during network-intensive operations.
* **Security First:** Implements secure credential management using environment variables, ensuring API keys are never exposed in source code.
* **Intuitive UI:** Built with `Tkinter`, providing a clean and accessible user experience for security analysis.

---

## Setup Instructions

### Prerequisites
* **Python 3.8+**
* **API Key:** Obtain your free [VirusTotal API Key](https://www.virustotal.com/) by creating an account.

### Installation & Configuration

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YAWA666777/yawa-url-detector.git](https://github.com/YAWA666777/yawa-url-detector.git)
    cd yawa-url-detector
    ```

2.  **Environment Setup:**
    Create a `.env` file in the project's root directory and input your API key:
    ```bash
    # Create the file and add your key
    echo "VIRUSTOTAL_API_KEY=your_actual_key_here" > .env
    ```

3.  **Run the Application:**
    ```bash
    python yawa-url-detector.py
    ```

---

## Security Guidelines

This project emphasizes security best practices:
* **Credential Protection:** Your `.env` file is explicitly ignored by Git (`.gitignore`). **Never** commit your `.env` file to a public repository.
* **Responsible Usage:** This tool is intended for educational and defensive cybersecurity purposes. Ensure you comply with VirusTotal’s Terms of Service when using their API.

## Contributions
Contributions are welcome! If you find a bug or have suggestions for improvements, please submit a pull request or open an issue.

---
*Developed with focus on cybersecurity and clean code principles.*
