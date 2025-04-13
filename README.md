# 🕵️‍♂️ Advance Keylogger in Python

A Python-based advanced keylogger that records keystrokes, captures screenshots, logs system information, records microphone audio, and securely emails the logs.

## 📌 Features

- Records all keystrokes with timestamps
- Takes periodic screenshots of the screen
- Logs system information (IP, platform, etc.)
- Records microphone audio
- Sends logs via email automatically
- Stores logs locally in encrypted format (optional)

## 🛠 Technologies Used

- **Python**  
- `pynput` – For keystroke logging  
- `PIL` – For screenshot capture  
- `sounddevice` & `scipy.io.wavfile` – For audio recording  
- `smtplib` & `email` – For sending emails  
- `getpass`, `platform`, `requests` – For system information

## 📦 Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/Bhavdiprathwa/Advance-Keylogger.git
    cd Advance-Keylogger
    ```

2. Install dependencies:
    ```bash
    pip install pynput Pillow sounddevice scipy requests
    ```

3. Configure your email in the script for sending logs:
    - Use app password for Gmail.
    - Enable less secure apps (or app-specific password) if using Gmail.

4. Run the script:
    ```bash
    python keylogger.py
    ```

## ⚠️ Disclaimer

This project is intended for **educational purposes only**. Unauthorized use of keyloggers is illegal and unethical.

## 📫 Contact

For queries or collaborations:  
📧 bhavdiprathwa728@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/bhavdip-rathwa/)
