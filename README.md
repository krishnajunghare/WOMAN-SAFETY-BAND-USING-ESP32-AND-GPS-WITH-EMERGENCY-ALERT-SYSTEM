Woman Safety Band Using ESP32 and GPS

📌 Project Overview

The Woman Safety Band Using ESP32 and GPS with Emergency Alert System is an IoT-based safety device designed to provide emergency assistance and location tracking.

The system uses an ESP32 microcontroller, GPS module, Blynk IoT platform, and an emergency push button. When the emergency button is pressed, the system activates the buzzer and LED and sends an emergency event through Blynk. The GPS coordinates can be monitored through the Blynk platform.

✨ Features

* 📍 Real-time GPS location tracking
* 🚨 Emergency push-button alert
* 🔊 Buzzer notification during an emergency
* 💡 LED emergency indication
* 📱 Blynk IoT integration
* 🖥️ LCD display for GPS coordinates and system status
* 📡 ESP32-based wireless connectivity

🧩 Components Used

* ESP32 Development Board
* NEO-6M GPS Module
* 16×2 LCD Display
* Push Button
* Buzzer
* LED
* Connecting Wires
* Breadboard
* Power Supply
* Blynk IoT Platform

⚙️ Working Principle

1. The ESP32 connects to the configured Wi-Fi network and Blynk IoT platform.
2. The GPS module receives satellite data and provides the current latitude and longitude.
3. The GPS coordinates are displayed on the 16×2 LCD.
4. The coordinates are also sent to Blynk using virtual pins.
5. When the emergency push button is pressed, the ESP32 detects the button state.
6. The buzzer and LED are activated to indicate an emergency.
7. An emergency event is sent through Blynk.
8. The user can check the available location information through the Blynk platform.

🔌 Pin Configuration

Component	ESP32 Pin
Push Button	GPIO 18
Buzzer	GPIO 19
LED	GPIO 21
GPS RX/TX	GPIO 26 / GPIO 27
LCD RS	GPIO 15
LCD E	GPIO 2
LCD D4	GPIO 4
LCD D5	GPIO 16
LCD D6	GPIO 17
LCD D7	GPIO 5

📱 Blynk Configuration

The project uses Blynk virtual pins:

Virtual Pin	Function
V0	Latitude
V1	Longitude
V2	Emergency Button Status

The Blynk event used for emergency notification is:

emergency_alert

Security Note: Do not upload your real Wi-Fi password or Blynk authentication token to GitHub. Use placeholders in the public source code.

🛠️ Software and Libraries

* Arduino IDE
* ESP32 Board Package
* Blynk Library
* TinyGPS++ Library
* LiquidCrystal Library

📂 Project Structure

WOMAN-SAFETY-BAND-ESP32-GPS/
│
├── Arduino-Code/
│   └── Woman_Safety_Band.ino
│
├── Circuit-Diagram/
│
├── Components-Details/
│
├── Project-Images/
│
├── Project-Presentation/
│
├── Project-Report/
│
├── LICENSE
└── README.md

🚀 Future Scope

* GSM-based emergency SMS and calling
* Automatic emergency contact notification
* Mobile application integration
* Live location sharing through a map
* Fall detection using an accelerometer
* Longer battery life and compact wearable design
* Cloud-based emergency monitoring

🎓 Project Type

Academic / IoT / Embedded Systems Project

📄 License

This project is released under the MIT License.
