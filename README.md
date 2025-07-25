# SMART ID Entry System Using RFID Technology

A real-time project designed to improve secure access control using RFID (Radio Frequency Identification) technology. This Smart ID Entry System efficiently automates identity verification and data logging, applicable across educational institutions, corporate environments, healthcare facilities, and more.

---

## 📌 Project Summary

This project presents a practical implementation of a Smart ID Entry System using RFID tags, ESP32 microcontroller, and Google Sheets API for real-time access tracking. By replacing traditional keys or manual logs, the system provides a faster, secure, and contactless method of identity verification.

---

## 👨‍💻 Developed By

- **V. Sai Charan** (22911A35C1) 
- **P. Varshith Naidu** (22911A35A7)   
- **A. Sri Ram** (22911A3565)  

Under the guidance of:  
**Dr. A. Anusha**, Associate Professor  
**Department of Artificial Intelligence**, Vidya Jyothi Institute of Technology

---

## 🧪 Technologies & Tools Used

- **RFID Reader** (MFRC522)
- **ESP32 / NodeMCU**
- **Arduino IDE**
- **Google Sheets API**
- **WiFi Communication**
- **LCD Display**
- **Google Cloud Platform (GCP)**

---

## ⚙️ System Architecture

The system is divided into two key components:

### 1. **RFID Data Registration**
- Reads and registers user information via Serial Monitor
- Stores RFID tag ID and user data
- Tags are uniquely associated with individuals

### 2. **RFID-Based Access Control**
- Reads tag and verifies authorization
- Updates Google Sheet with entry/exit timestamps
- Displays status on LCD (Success / Denied)

---

## 📈 Features

- 🔐 **Secure Access Control**
- 📶 **Real-Time Logging** using Google Sheets
- 💡 **LCD Feedback** for user status
- ♻️ **Scalable & Extendable** design for institutions or enterprises
- 💾 **Data Analytics-Ready** logs for audits or attendance reports

---

## 🏗️ Hardware Requirements

- RFID Reader (MFRC522)
- Passive RFID Cards/Tags
- ESP32 / NodeMCU
- LCD Display
- Jumper Wires, Breadboard
- WiFi Module
- Power Supply

---

## 🛠️ Software Requirements

- Arduino IDE
- ArduinoJson, HTTPSRedirect libraries
- Google Cloud Project (with Sheets API enabled)
- JSON Key File (Service Account)

---

## 🖥️ Setup Instructions

1. **Connect the Hardware** as per wiring diagram
2. **Upload the Arduino Code** via Arduino IDE
3. **Enable Google Sheets API** on GCP
4. **Use the JSON Key File** to connect ESP32 with your spreadsheet
5. **Test by scanning RFID tag** — data should appear in Google Sheet

---

## 📊 Applications

- Educational Institutions (student & staff attendance)
- Corporate Office Access Control
- Libraries, Labs, Hostels
- Event Entry Management
- Residential Societies & Parking Systems

---

## 🏁 Result Highlights

- ✅ Reduced unauthorized access attempts
- 🚀 Real-time monitoring of entries & exits
- 🗂️ Automated, tamper-proof logs
- 🧾 Detailed insights for audits and security

---

## 🔭 Future Scope

- 🔐 Biometric + RFID multi-factor authentication
- ☁️ Cloud dashboard for analytics
- 📊 Advanced data visualization of user activity
- 🔋 Energy-efficient, eco-friendly tag options

---

## 📜 References

1. [RFID in IoT](https://doi.org/10.1109/CECNet.2012.6201508)  
2. Smart Attendance Monitoring (IJAEM 2021)  
3. [Smart Transportation Using RFID](https://doi.org/10.1145/3316615.3316719)  
4. Circuit Specialists - RFID Setup Guide  
5. RFID Journal - Data Analytics in Industry  

---

## 📬 Contact

- **Email**: vennusaicharan09@gmail.com  
- **GitHub**: [SAI-CHARAN09](https://github.com/SAI-CHARAN09)

---

## 🏫 Affiliation

**Department of Artificial Intelligence**  
**Vidya Jyothi Institute of Technology**  
(An Autonomous Institution, Affiliated to JNTUH, Accredited by NAAC & NBA)

---

