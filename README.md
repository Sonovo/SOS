# SOS – SCADA On Smart Devices

**SOS** is a modern, mobile-first SCADA platform I developed for monitoring and controlling industrial PLC systems directly from iPhones and iPads. Designed for engineers who want flexibility, speed, and real-time insight without being tied to a desktop.

---

## 🔧 Key Features

- 📱 **Real-time PLC monitoring** – Access live values and control devices on the go
- 🔔 **Smart Alarm Notifications** – Get immediate alerts for critical events like fire alarms, pressure drops, compressor faults, and more
- 📷 **QR Code Scanning** – Scan physical parts to instantly load manuals, metadata, and live machine data
- 🤖 **Built-in AI Assistant** – Ask natural language questions about part functions, fault codes, or machine behavior – powered by GPT
- 📊 Energy, pressure, and temperature dashboards – all inside one smart app
- 🧾 Generate PDF reports and access technical documents linked to machines

---

## 🧠 Who It's For

- SCADA engineers & automation technicians  
- Utilities and manufacturing teams  
- Field engineers who need mobile access to control room data

---

## 🛠️ Tech Stack

- Swift (iOS native)
- Firebase (Realtime Database + Storage)
- Modbus TCP (for PLC data)
- OpenAI API (for AI assistant)
- QR scanning framework (e.g. QRCodeKit)

---

---

## 📷 Screenshots

### 📊 Main Dashboard – SOS ContentView

![SOS Dashboard](screens/dashboard.png)

This is the main screen of the SOS app. It shows:
- Live air pressure and cooling temperatures
- Real-time silo levels (Silo 1–6)
- Energy usage per machine (Husky18–20), with color-coded load bars
- Instant access to: AI Assistant 🤖, Search 🔎, QR Code Scanner 📷, and Alarm View 🔔

Designed for mobile-first SCADA control and quick response in field operations.
---

## 📄 About the Developer

Developed by Reza **(@Sonovo)** – SCADA Engineer and iOS Developer.  

---

## 📜 License

MIT License – Free to use, fork, and build upon.
