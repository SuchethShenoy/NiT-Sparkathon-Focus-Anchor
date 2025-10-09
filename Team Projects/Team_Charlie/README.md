# Focus Anchor  
*“Distraction isn’t a habit—it’s a design flaw.”*

## 🧠 Project Overview  
In a world filled with digital distractions, people often lose focus without realizing it—especially those with ADHD. **Focus Anchor** is a wearable device that detects subconscious fidgeting using IMU sensors and responds with calming haptic feedback to restore attention.

Built in 24 hours during **NiT Sparkathon 2025**, this prototype blends behavioral insight, embedded ML, and haptic design.

---

## 🔥 Problem Statement  
Modern attention loss often comes from involuntary, subconscious restlessness rather than visible distraction. Existing solutions (apps, timers, smartwatches) add to screen fatigue rather than solve it.

To the best of our knowledge, there are currently **no products specifically designed to counter attention drift in ADHD or fidget-prone users using physical intervention**.

**Focus Anchor** addresses this through real-time motion sensing and haptic redirection, without screens, sound, or alerts.

---

## 🎯 What We Built  
A wearable prototype that:

- Uses an **ESP32 (Seeed Studio) + MPU6050 IMU**  
- Learns a user’s stillness baseline through short calibration  
- Detects fidgeting or restless micro-movements  
- Generates soft vibration feedback via a micro haptic motor  
- Classifies motion with a lightweight ML model trained on:  
  - Public IMU datasets  
  - A custom synthetic fidgeting dataset

---

## 🛠️ Tech Stack  

**Hardware**  
- ESP32 (Seeed Studio)  
- MPU6050 Inertial Measurement Unit  
- Vibration Motor  

**Software & ML**  
- TensorFlow / TinyML / Edge Impulse  
- Python (data simulation & preprocessing)  
- Arduino-compatible firmware  
- TFLite model for embedded inference

**Tools**  
- IMU data logging  
- Serial monitoring  
- Pandas/NumPy for preprocessing

---

## 👥 Team & Contact  

**Hackathon Team — Focus Anchor (NiT Sparkathon 2025):**  
- Sucheth Shenoy  
- Vaibhav Tiwari
- Parvesh Ramesh  
- Deekshith I S  
- Suchitra Jayanna

For collaboration or inquiries, feel free to connect on GitHub or LinkedIn.

---

## 📄 License  

This project is released under the **MIT License**.  
See the `LICENSE` file for full details.

