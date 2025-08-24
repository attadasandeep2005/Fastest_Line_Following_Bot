# 🚀 Fastest Line Following Bot

This project demonstrates the design and implementation of a **high-speed line following robot** using **Arduino Nano** and **TB6612FNG Motor Driver**. The bot is optimized for precision, stability, and speed, capable of following complex tracks using a 7-channel IR sensor array.

---

## 🛠 Components Used
- **Arduino Nano** – Microcontroller for processing sensor data and motor control  
- **TB6612FNG Motor Driver** – Dual motor driver to control N20 gear motors  
- **7-Channel IR Sensor Array** – For accurate line detection and corrections  
- **2 × N20 Gear Motors (6V 600RPM)** – Provides high-speed motion  
- **Acrylic Chassis** – Lightweight and durable base  
- **2 × Silicone Wheels** – Ensures grip and stability on track  
- **Motor Brackets** – For secure mounting of gear motors  
- **M2 & M3 Screws + Hex Spacers** – Assembly and fitment hardware  
- **Jumper Wires** – Circuit connections  
- **Caster Wheel** – For stability and smooth movement  

---

## ⚙️ Working Principle
1. The **7-channel IR sensor array** detects the black line against the white background.  
2. Sensor values are processed by the **Arduino Nano**, which applies correction algorithms (like proportional/PID).  
3. The **TB6612FNG motor driver** adjusts the speed of the left and right motors to keep the bot aligned with the line.  
4. The **high RPM N20 motors** allow for quick responses and fast movement along the track.  

---

## 🚧 Assembly Overview
- Mount the **N20 motors** on the acrylic chassis using brackets and hex spacers.  
- Attach the **silicone wheels** for enhanced grip.  
- Fix the **7-channel IR sensor array** at the front, close to the ground.  
- Place the **Arduino Nano** and **TB6612FNG motor driver** securely on the chassis.  
- Use the **caster wheel** at the back for balance.  
- Connect components using jumper wires.  

---

## 🔌 Wiring Guide
- **7-Channel IR Sensor Array → Arduino Nano** (Analog pins for readings)  
- **Arduino Nano → TB6612FNG** (PWM & Direction pins)  
- **TB6612FNG → Motors** (Outputs A & B)  
- **Power**: 6V–9V battery pack (with sufficient current capacity)  

---

## 📊 Algorithm
- **Step 1**: Read analog values from the 7-channel sensor array.  
- **Step 2**: Determine the position of the line relative to the center.  
- **Step 3**: Apply correction using proportional/PID logic.  
- **Step 4**: Adjust left/right motor speeds accordingly.  
- **Step 5**: Repeat continuously for smooth and fast line tracking.  

---

## 🎯 Features
- High-speed tracking with **600RPM motors**  
- Enhanced stability using **silicone wheels**  
- Accurate line sensing with **7-channel IR array**  
- Lightweight acrylic chassis with optimized hardware fitment  

---

## 📸 Future Improvements
- Fine-tuned **PID control** for sharper turns  
- Improved **track detection** for different lighting conditions  
- Addition of **OLED display** for debugging sensor values  
- Option for **Bluetooth / Wireless debugging**  

---

## 🤝 Contribution
Feel free to fork this repo, suggest improvements, or share your own track designs.  

---

## 📜 License
This project is open-source under the **MIT License**.  
