# Secure-Smart-Collar-for-Animals

The Secure Smart Collar for Animals is an IoT-based safety and health-monitoring system designed for livestock. 
It ensures protection from theft, provides real-time tracking, and monitors the animal’s vital parameters such as 
heart rate, temperature, and movement. The system sends alerts to the owner whenever abnormal activity or health risks 
are detected, ensuring the safety and well-being of farm animals.

---

## Project Demonstration Video

[![Smart Collar Demo](https://raw.githubusercontent.com/Shashank452/Secure-Smart-Collar-for-Animals/main/Images/Secure_collar_On.jpg)](https://github.com/Shashank452/Secure-Smart-Collar-for-Animals/raw/main/Secure_Collar.mp4)

---

## ThingSpeak Dashboard (Live Data Monitoring)

![ThingSpeak Dashboard](https://raw.githubusercontent.com/Shashank452/Secure-Smart-Collar-for-Animals/main/Images/Secure_Collar_ThinkSpeak.png)

---

## Technologies & Components Used

- **ESP32** – Central microcontroller for IoT connectivity  
- **GPS Module** – Real-time animal location tracking  
- **MAX30100 Sensor** – Heartbeat & SpO2 monitoring  
- **DHT11 Sensor** – Temperature and humidity measurement  
- **Vibration/Movement Tracking** – Detects unusual inactivity or fast movement  
- **Tamper Detection System** – Alerts when collar is forced open, cut, or removed  
- **ThingSpeak** – Cloud-based IoT platform for visualization  
- **SMS / Call / App Alerts** – Real-time notifications to the owner  

---

## Key Features

### Anti-Theft Security
- Sends immediate alert if the animal **leaves the farm boundary** (Geofencing).
- Triggers alert/call if the collar is **removed, cut, or tampered with**.

### Health Monitoring
- Tracks **heart rate**, **body temperature**, and **movement**.
- Detects abnormal patterns such as fever, stress, low activity, or sudden movement.
- Sends alerts to the owner for early intervention.

### Real-Time GPS Tracking
- Continuous location monitoring of livestock.
- Helps locate lost or stolen animals quickly.

### IoT Cloud Integration
- Live sensor data upload to **ThingSpeak** for analysis.
- Historical graph view for heartbeat, temperature, and movement data.

---

## Project Structure
```bash
Secure-Smart-Collar-for-Animals/
│── Images/
│── Secure_Collar.mp4
│── README.md
```

---

## 🚀 How It Works

1. ESP32 continuously monitors heartbeat, temperature, movement, and GPS.  
2. If abnormalities such as high temperature, unusual movement, or tampering are detected →  
   **Real-time alert is sent to the owner.**  
3. GPS data updates help track animal location in real time.  
4. All sensor readings are uploaded to **ThingSpeak** for visualization.  
