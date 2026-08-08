# KeyLogger Analyzer and Detector

## 🛡️ Project Overview

**KeyLogger Analyzer and Detector (VKDDS)** is a defensive cybersecurity application developed to identify and analyze suspicious keylogger-related activity.

The application monitors running processes for suspicious keywords and provides a graphical dashboard to help users understand potentially malicious activity. It also includes a safe keylogger simulation and log analysis features for cybersecurity testing and educational purposes.

---

## 🎯 Objectives

- Detect suspicious processes associated with keylogging activity.
- Analyze simulated keylogger data.
- Categorize collected test data into meaningful categories.
- Provide alerts when suspicious activity is detected.
- Allow users to terminate suspicious processes.
- Generate CSV and text-based analysis logs.
- Provide a simple graphical interface for cybersecurity analysis.

---

## 🚀 Main Features

### 1. Detection Dashboard
The application scans running processes and checks for suspicious indicators such as:

- `keylog`
- `keyboard`
- `pynput`
- `hook`
- `keystroke`
- `logger`
- `python`

When suspicious activity is detected, the application can display a warning notification.

### 2. Keylogger Simulation

The project includes a controlled simulation environment for generating test keylogging data.

This allows the detection system to be tested without using the application as a real-world keylogger.

### 3. Log Categorization

The application analyzes simulated text and categorizes information into types such as:

- Username
- Password
- Email
- Website
- Credentials
- Website text
- Conversation

The categorized information is stored in a CSV file for further analysis.

### 4. Process Management

The application displays suspicious processes and provides an option to terminate a detected process.

### 5. Notifications

The application can display a warning when suspicious activity is detected.

Example:

**"Suspicious activity detected!"**

### 6. Email Alert Support

The application contains an optional email notification feature for sending security alerts.

Email functionality is disabled by default and should only be configured using secure environment variables or other protected credential storage.

---

## 🖥️ Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Core application development |
| Tkinter | Graphical User Interface |
| psutil | Process monitoring |
| CSV | Log storage and analysis |
| Regular Expressions | Data categorization |
| Plyer | Desktop notifications |
| SMTP | Optional email alerts |
| HTML | Project report |

---

## 📂 Project Structure

```text
Keylogger-Analyzer-and-Detector/
│
├── vkdds.py
├── vkdds.exe
├── project_report.html
├── simulated_keylog.txt
├── categorized_keylog.csv
└── README.md
