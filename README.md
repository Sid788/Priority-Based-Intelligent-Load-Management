# Priority-Based-Intelligent-Load-Management

An embedded system project that intelligently manages electrical loads during overload conditions by continuously monitoring current consumption and automatically disconnecting lower-priority loads while keeping essential loads active.

---

## 📖 Overview

Traditional electrical protection systems disconnect the entire power supply when an overload occurs, causing both critical and non-critical devices to lose power.

This project demonstrates a smarter approach using an Arduino, ACS712 current sensor, and relay modules. The system continuously measures the total current and compares it with predefined threshold values. When an overload is detected, low-priority loads are disconnected automatically while high-priority loads continue operating.

The project serves as a practical demonstration of intelligent power management using embedded systems.

---

## 🚀 Features

- Real-time current monitoring
- Automatic overload detection
- Priority-based load management
- Automatic relay switching
- Selective load shedding
- Continuous monitoring and control
- Low-cost embedded implementation
- Easy to scale for larger applications

---

## 🛠 Hardware Used

- Arduino UNO
- ACS712 Current Sensor
- 4-Channel Relay Module
- 12V DC Trainer Kit
- 12V Bulbs (Loads)
- Jumper Wires
- Breadboard (optional)

---

## ⚙ Working Principle

1. All loads are initially turned ON.
2. The ACS712 continuously measures the total current.
3. Arduino reads the sensor output.
4. Current is compared with predefined threshold values.
5. If Threshold 1 is exceeded:
   - Lowest-priority load is disconnected.
6. If Threshold 2 is exceeded:
   - Medium-priority load is disconnected.
7. High-priority load remains ON.
8. Once the current returns to a safe range, disconnected loads are restored automatically.

---

## 📊 System Flow

Power Supply
↓
ACS712 Current Sensor
↓
Arduino UNO
↓
Relay Module
↓
Priority-Based Loads

---

## 📂 Project Structure

```
├── code/
│   ├── load_management.ino
│
├── images/
│   ├── setup.jpg
│   ├── block_diagram.png
│   ├── flowchart.png
│
├── report/
│   ├── Project_Report.pdf
│
└── README.md
```

---

## 🎯 Applications

- Smart Homes
- Residential Power Management
- Energy Saving Systems
- Educational Embedded Projects
- Industrial Load Monitoring
- Laboratory Demonstrations

---

## 🔮 Future Scope

- IoT-based Remote Monitoring
- Mobile Application for Load Priority Control
- AI-based Dynamic Threshold Adjustment
- Smart Grid Integration
- Energy Consumption Analytics
- Cloud-Based Monitoring Dashboard

---

## 📈 Results

The prototype successfully:

- Monitored current in real time
- Detected overload conditions
- Automatically disconnected lower-priority loads
- Maintained uninterrupted operation of critical loads
- Demonstrated reliable and stable embedded load management

---

## 📚 References

- Arduino Official Documentation
- ACS712 Datasheet (Allegro Microsystems)
- Getting Started with Arduino – Massimo Banzi
- Programming Arduino – Simon Monk

---

## 👥 Team Members

- Sidharth M
- Amrutha MA
- Maria Margret Victor

---

## 📜 License

This project is intended for academic and educational purposes.
