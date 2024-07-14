## 🔥 LPG Gas Detector 🚨


A simple and effective LPG gas detector using Arduino to keep your environment safe by alerting you when LPG gas levels exceed a safe threshold. This project uses an MQ-2 gas sensor, an LCD for real-time monitoring, LEDs for visual alerts, and a buzzer for sound alerts.

# 🚀 Features
Real-time Gas Monitoring: Continuously measures LPG gas levels.
Visual Alerts: Red LED lights up when gas levels are high; Green LED when levels are safe.
Auditory Alerts: Buzzer sounds when gas levels exceed the threshold.
User-Friendly Interface: LCD displays gas levels and status messages.

# 🛠 Components Required
Arduino Uno
MQ-2 Gas Sensor
16x2 LCD Display
Buzzer
Green LED
Red LED
Resistors
Breadboard and Jumper Wires

⚡ Circuit Diagram
 ![LPG_gas](https://github.com/user-attachments/assets/bb4354f0-b4ab-4de4-bcef-431a9c35c311)

# 📝 Setup Instructions
Connect the Components:
Follow the circuit diagram to connect the MQ-2 gas sensor, LCD, buzzer, and LEDs to the Arduino.

Upload the Code:
Upload the provided lpg_gas_detector.ino code to your Arduino using the Arduino IDE.

Power the System:
Once the code is uploaded, power your Arduino. The LCD will display a welcome message, and then it will start monitoring the gas levels.

Gas Detection:
If the gas level exceeds the threshold, the buzzer will sound, the red LED will light up, and the LCD will display an alert message. If the gas level is normal, the green LED will remain on, and the LCD will display a normal message.

# 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

# 🙏 Acknowledgements
Special thanks to all the open-source contributors and the Arduino community for their resources and support.
