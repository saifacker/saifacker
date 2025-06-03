# 🏠 Home Automation System using ESP8266

A smart, low-cost IoT-based home automation system that allows users to control appliances remotely via Wi-Fi using a smartphone app and the ESP8266 microcontroller.

## 🔧 Features

- Remotely control home appliances (e.g., lights, fans)
- Real-time status monitoring via Blynk app
- Wi-Fi-based communication using ESP8266
- Secure and low-power design
- Easy to set up and modify for additional devices

## 📦 Components Used

- ESP8266 NodeMCU
- Relay Module (1/2/4 Channel)
- AC Appliances (Bulb, Fan, etc.)
- Blynk App (for Android/iOS)
- Jumper wires, breadboard, power supply

## 🔌 Circuit Diagram

> *(Upload a circuit diagram image here if available)*  
You can connect each relay IN pin to a digital GPIO pin on the ESP8266. The relay outputs are wired to control the AC appliances.

## 🖥️ Software & Tools

- Arduino IDE
- Blynk IoT Platform
- Embedded C/C++
- ESP8266WiFi & Blynk libraries

## 🚀 Getting Started

1. **Install Arduino IDE**  
   Download from [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)

2. **Add ESP8266 Board**  
   Go to *Preferences* → Add the following URL to "Additional Board Manager URLs":

http://arduino.esp8266.com/stable/package_esp8266com_index.json


3. **Install Required Libraries**  
- Blynk
- ESP8266WiFi

4. **Upload the Code**  
- Open `home_automation.ino`
- Replace `BLYNK_AUTH_TOKEN`, `WIFI_SSID`, and `WIFI_PASSWORD` with your credentials
- Select the correct board (NodeMCU 1.0) and port
- Upload to ESP8266

## 📱 App Setup (Blynk)

- Install Blynk app from Play Store / App Store
- Create a new project and add buttons linked to digital pins (e.g., D1, D2)
- Copy the **Auth Token** and paste it into the code
- Start the project and control appliances with one tap

## 📸 Demo

> *(Insert images or a short demo video link here if available)*  
Example:  
![App Screenshot](demo/screenshot.png)

## 📜 License

This project is licensed under the MIT License.

---

> Created with ❤️ by [Saif Ahmed Nandyal](https://github.com/saifacker)