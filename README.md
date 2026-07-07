# 🚌 Smart Bus Ticketing System

## 📖 Project Overview

The Smart Bus Ticketing System is an IoT-based solution designed to automate passenger ticket verification, occupancy monitoring, and gate control in public transportation. The system uses RFID technology for contactless ticket validation and IR sensors to monitor passenger entry and exit. An ESP32-S3 acts as the main controller, while two Arduino Nano boards independently control the entry and exit gates using servo motors.

---

## 🚀 Features

- RFID-based passenger authentication
- Automatic fare verification
- Real-time passenger counting
- LCD display for occupancy status
- Automatic entry and exit gate control
- Bus full detection
- Audio feedback using buzzer
- LED status indication
- Dual-controller architecture using ESP32-S3 and Arduino Nano

---

## 🛠️ Components Used

| Component | Quantity |
|-----------|:--------:|
| ESP32-S3 Development Board | 1 |
| Arduino Nano | 2 |
| MFRC522 RFID Reader | 1 |
| RFID Cards/Tags | 2 or more |
| IR Sensors | 2 |
| Servo Motors | 2 |
| 16×2 LCD with I2C Module | 1 |
| Push Button | 1 |
| Red LED | 1 |
| Green LED | 1 |
| Buzzer | 2 |
| Breadboard | 1 |
| Jumper Wires | As required |
| USB Cables | 3 |

---

## 💻 Software Used

- Arduino IDE
- C/C++ (Arduino Programming)
- ESP32 Board Package
- MFRC522 Library
- Servo Library
- LiquidCrystal_I2C Library
- Wire Library
- SPI Library

---

## 📂 Folder Structure

```
Smart-Bus-Ticketing-System
│
├── README.md
├── ESP32_Code
├── Arduino_Nano_Entry
├── Arduino_Nano_Exit
├── Documentation
├── Project_Images
├── Circuit_Diagram
├── Block_Diagram
└── Demo
```

---

## ⚙️ Working Principle

1. Passenger scans an RFID card.
2. ESP32 verifies the RFID card.
3. If the passenger is authorized and seats are available, access is granted.
4. Passenger presses the entry button.
5. ESP32 sends a command to the Entry Arduino Nano.
6. Entry Nano opens the servo gate and activates the buzzer.
7. Entry IR sensor detects the passenger and updates the passenger count.
8. LCD displays the updated occupancy.
9. Exit IR sensor detects passengers leaving the bus.
10. Exit Arduino Nano operates the exit gate and updates the passenger count.

---

## 📁 Source Code

- ESP32 Main Controller → `ESP32_Code`
- Entry Gate Controller → `Arduino_Nano_Entry`
- Exit Gate Controller → `Arduino_Nano_Exit`

---

## 📷 Project Images

Project images are available in the **Project_Images** folder.

---

## 🔌 Circuit Diagram

The circuit diagram is available in the **Circuit_Diagram** folder.

---

## 🧩 Block Diagram

The block diagram is available in the **Block_Diagram** folder.

---

## 📄 Documentation

The complete project report is available in the **Documentation** folder.

---

## 🎥 Demo Video

The project demonstration video link is available in the **Demo/video_link.txt** file.

---

## 👩‍💻 Developed By

**Aswanthika A V**

B.Tech Computer Science and Engineering (AI & Robotics)

VIT Chennai

---

## 📜 License

This project is developed for educational and academic purposes.