# 🔥 Arduino-Based Fire & Smoke Detection System

This project presents a smart fire safety solution built using the Arduino UNO, designed and simulated in Proteus. The system is capable of responding at two critical levels—initial smoke detection and confirmed fire condition—by analyzing sensor inputs and activating appropriate safety mechanisms.

## 🚨 Key Features

### ✅ Level 1: Smoke Detected (Early Warning)

**Sensor Used:** MQ-2 Gas Sensor
**Response:**

* LED begins blinking to indicate potential danger
* DC motor activates a fan to help disperse smoke

### 🔥 Level 2: Smoke + Elevated Temperature (Confirmed Fire)

**Sensors Used:** MQ-2 Gas Sensor + LM34 Temperature Sensor
**Response:**

* Blinking LED continues
* Buzzer sounds an alarm
* Servo motor rotates to simulate activating a water tap

## 🧠 System Logic

* **Temperature Threshold:** Approximately 134°F (≈56°C)
* **Servo Positions:**

  * **90°:** Normal/safe condition (fan active for smoke dispersion)
  * **0°:** Fire condition (simulates opening a water tap)
* **Auto-Reset:** System resets and all components return to default when no danger is detected

## 🛠 Components

* MQ-2 Gas Sensor
* LM34 Temperature Sensor
* Arduino UNO
* Servo Motor
* DC Motor (controlled via L293D Motor Driver)
* Buzzer
* LED
* Breadboard & jumper wires

## 🧪 Simulation Details

The entire system was simulated and verified using Proteus. Ensure all sensor libraries and modules are correctly installed within the simulation environment to achieve accurate results.

## 🛡 Potential Enhancements

* Integration of a flame sensor to increase detection accuracy
* IoT capabilities for sending real-time alerts to mobile devices
* Replacement of servo with a relay module to control an actual water pump
* 
## 👥 Project Contributors

Developed by:

* **Tanusha**
* **Md Adnan Khan**


## 🙌 Get Involved

We welcome suggestions, improvements, and collaboration. Feel free to fork the repository, make enhancements, or submit pull requests!
