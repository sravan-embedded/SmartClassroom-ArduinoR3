# 🧩 Smart Classroom Automation using IoT and Arduino Uno R3

## 🔍 Abstract
The Smart Classroom System automates classroom management using **Arduino Uno R3** and **IoT concepts**. It detects student entry and exit through **IR sensors**, updates student count on an **LCD display**, and operates a **motorized door** automatically. Lights and fans switch ON when students are inside and OFF when the room is empty, improving **energy efficiency** and **security**.

---

## ⚙️ Hardware Components
- Arduino UNO R3  
- IR Sensors (Entry / Exit / Door Detection)  
- 16×2 LCD Display (I²C Interface)  
- L293D Motor Driver Module  
- DC Motor (Door Control)  
- 5 V Relay Module  
- Fan & LED (Load Control)  
- Power Supply, Wires, Breadboard  

---

## 💡 Working Principle
1. **Detection:** IR sensors detect students entering/exiting.  
2. **Door Control:** Arduino drives the motor to open / close the door.  
3. **Counting:** LCD shows total students inside/outside.  
4. **Lighting & Fan Control:** Appliances turn ON only when room is occupied.  
5. **Manual Override:** Allows manual operation if required.  

---

## 🧠 Software & Programming
- Platform – Arduino IDE  
- Language – Embedded C / C++  
- Libraries – `Wire.h`, `LiquidCrystal_I2C.h`  
- Board – Arduino UNO R3  

---

## ✅ Results
- Successfully counted student entries / exits.  
- Automatic door and light control worked accurately.  
- Energy consumption was reduced when classroom was empty.  
- LCD displayed real-time information.  

---

## 🧾 Conclusion
This project demonstrates how low-cost components and microcontroller programming can automate and optimize classroom operations. It simplifies human effort, increases energy efficiency, and creates a smart, secure environment suitable for schools and colleges.

---

## 🚀 Future Scope
- **IoT Integration:** Connect to ThingSpeak or Firebase for remote monitoring.  
- **Mobile App Control:** Teacher app for manual operation.  
- **Solar Power Support:** Use solar panels for eco-friendly operation.  
- **RFID / Facial Recognition:** Automatic attendance tracking.  
- **AI Optimization:** Predict usage patterns and save more energy.  

---

### 🎯 Project by  
**Illuru Sravan Kumar Reddy**  
B.Tech – Electronics and Communication Engineering (ECE)  
Madanapalle Institute of Technology & Science
