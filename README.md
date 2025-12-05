# Automatic Street Light System

An automated lighting system that switches street lights **ON during low-light conditions** and **OFF during daylight** using a simple light/dark detection circuit.  
This project demonstrates basic sensor-based automation using an LDR (Light Dependent Resistor), transistors, resistors, and LEDs to replicate how real-world automatic street lighting works.

Developed as part of an educational project to understand analog electronics, sensors, and automation principles.

---

## 🌙✨ Project Overview

This circuit detects ambient light levels using an **LDR**.  
Depending on the surrounding light intensity:

- **If it is dark → Street Light turns ON**  
- **If it is bright → Street Light turns OFF**

The system operates **fully automatically**, requiring no manual switch.

---

## 🧠 Features

- Light/dark activated switching  
- Automatic ON/OFF control  
- Energy-efficient behaviour  
- Simple and cost-effective circuit  
- Demonstrates practical analog electronics fundamentals  
- Suitable for educational, prototype, or low-power automation use cases  

---

## 🔧 Components Used

| Component | Description |
|----------|-------------|
| **LDR (Light Dependent Resistor)** | Detects light intensity |
| **Transistor / MOSFET / Relay (depending on build)** | Used as the switching device |
| **Resistors** | For biasing and voltage division |
| **LED or Bulb** | Represents the street light |
| **Breadboard / PCB** | Circuit assembly |
| **Power Supply (5V / 9V)** | Provides system power |

---

## ⚙️ How It Works

1. When the ambient light is **bright**, the LDR’s resistance decreases:  
   - Transistor remains **OFF**  
   - Street light stays **OFF**

2. When it becomes **dark**, the LDR’s resistance increases:  
   - Transistor turns **ON**  
   - Street light (LED/bulb) **turns ON automatically**

The LDR forms a **voltage divider**, and the transistor acts as an **electronic switch**.

---

## 📘 Learning Outcomes

- Understanding of **analog sensors (LDRs)**  
- Basics of **voltage dividers**  
- Knowledge of **transistor switching circuits**  
- Building simple prototypes on breadboard  
- Practical exposure to **automation system design**  

---

## 🛠 Possible Improvements

- Use a relay to support high-power street lights  
- Add a timer (RTC module) for scheduled dimming  
- Implement solar charging + battery system  
- Add microcontroller-based fine control  
- Integrate IoT to monitor and report light usage  

---

## 📄 License

This project is meant for educational use.  
You may modify or reuse with attribution.

---

## 👤 Author

**Sadeep Dilshan Kasthuriarachchi**  
Electronics | Automation | Embedded Systems | IoT
























# Automatic-Street-Light-System
The circuit employed here should be an uncomplicated light/dark activated switch, which simply turns ON/OFF street lights based on light condition.


https://www.tinkercad.com/things/bdXEQxbnwdw-street-lighting-system01/editel

https://www.tinkercad.com/things/e4uAuA3tnGE-street-lighting-system02/editel

<h2>Street Lighting System_01</h2>

<img width="1440" alt="Screenshot 2022-01-07 at 08 57 41" src="https://user-images.githubusercontent.com/76505825/148486651-8dacacc1-a8d3-48dd-8184-ae53a86e8f06.png">

<h2>Street Lighting System_02</h2>

<img width="1440" alt="Screenshot 2022-01-07 at 08 57 18" src="https://user-images.githubusercontent.com/76505825/148486885-147dfc71-03fe-4cc4-af21-639452016c23.png">
