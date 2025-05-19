# 🛡️ Python Keylogger (For Educational Use Only)

This is a simple keylogger written in Python using the `pynput` library. It captures keystrokes from the user's keyboard and stores them in a local text file. The project is designed for **educational and ethical hacking purposes only**, helping students and cybersecurity learners understand how keylogging works and how to defend against it.

---

## ⚠️ Disclaimer

> **This tool is for educational, ethical, and research purposes only.**
>
> Unauthorized use of keyloggers to monitor someone else’s activity without their explicit consent is illegal and unethical. Use only in controlled environments or with permission.

---

## 📌 Features

- Logs every key press from the keyboard
- Saves the logs in `keylogger.txt` after every 10 keystrokes
- Uses the `pynput` library to listen for keyboard events
- Stops logging when the **Escape (Esc)** key is pressed
- Lightweight and easy to understand

---

## 📦 Requirements

- Python 3.x
- [`pynput`](https://pypi.org/project/pynput/)

Install dependencies using:

```bash
pip install pynput
