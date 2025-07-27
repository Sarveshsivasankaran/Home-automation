# 🏠 Home Automation System using Arduino IoT Cloud 🌐

This project enables you to control multiple home appliances (like lights, fans, etc.) from **anywhere in the world** using the **Arduino IoT Cloud** platform and a **relay module** connected to an ESP-based microcontroller.

---

## 🔧 Tech Stack

- **Microcontroller:** ESP8266 (e.g., NodeMCU)
- **Platform:** Arduino IoT Cloud
- **Programming Language:** C++ (Arduino IDE)
- **Relays:** 5-Channel Relay Module
- **Connectivity:** Wi-Fi

---

## ⚙️ Features

- 🌍 **Global Access**: Control your home devices from anywhere via the internet  
- 📲 **Web Dashboard**: Interactive switches on the Arduino IoT Cloud dashboard  
- 🔌 **Device Control**: Supports 5 appliances (lights, fans, etc.)  
- 📡 **Real-Time Sync**: Updates device states in real-time  
- 🧩 **Modular Design**: Easily add more relays if needed

---

## 🖥️ Dashboard Preview

> Access your relays using toggles in the Arduino IoT Cloud Dashboard.

![Dashboard Example](https://user-images.githubusercontent.com/your-image-url) <!-- Optional: Replace with your screenshot -->

---

## 📁 Folder Structure

├── ArduinoCode/
│ └── HomeAutomation.ino
├── README.md


---

## 🧠 How It Works

Each appliance is connected to a relay, which is controlled by the ESP8266 via digital pins. These are then linked to `CloudSwitch` variables on the Arduino IoT Cloud. You can toggle these switches from the online dashboard, and the microcontroller will update the relay states accordingly.

---

## 🪛 Circuit Setup

| Relay | GPIO Pin |
|-------|----------|
| Relay 1 | D1 (GPIO5) |
| Relay 2 | D2 (GPIO4) |
| Relay 3 | D5 (GPIO14) |
| Relay 4 | D6 (GPIO12) |
| Relay 5 | D7 (GPIO13) |

Make sure to connect the **relay module's INx pins** to the respective **GPIOs**, and the **VCC and GND** properly.

---

## 🚀 Getting Started

1. Clone this repository
2. Open `HomeAutomation.ino` in the Arduino IDE
3. Install required libraries (via Library Manager or Arduino Cloud setup)
4. Configure the Thing on [Arduino IoT Cloud](https://create.arduino.cc/iot)
5. Flash the code to your ESP8266
6. Open the Cloud Dashboard and start controlling your devices! 🔥

---

## ✅ Requirements

- Arduino IDE
- Arduino IoT Cloud account
- ESP8266 or compatible Wi-Fi microcontroller
- 5V Relay module
- Internet connection

---

## 🌟 Future Improvements

- Add scheduling or timer features ⏱️  
- Include sensor-based automation (e.g., motion/light sensors)  
- Voice assistant integration (Alexa/Google Assistant) 🔊  
- Mobile-friendly UI via custom dashboard

---

## 🛡️ Disclaimer

Ensure proper insulation and electrical safety precautions while dealing with AC appliances. This project is for **educational purposes**.

---

## 🙌 Acknowledgments

- [Arduino IoT Cloud](https://create.arduino.cc/iot)
- Community resources and tutorials

---

## 📬 Contact

Feel free to connect via [LinkedIn](https://www.linkedin.com/in/sarvesh-sivasankaran/) or raise an issue for doubts/suggestions.

---

⭐ If you liked this project, don’t forget to **star** the repo!
