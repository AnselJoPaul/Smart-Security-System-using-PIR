# Smart-Security-System-using-PIR
A simple and effective motion detection security system built using an Arduino, a PIR sensor, and a buzzer/LED.
When motion is detected, the system triggers an alert, making it ideal for small security applications at home, offices, or shops.

📋 Project Overview:
The Smart Security System monitors an area for movement using a PIR (Passive Infrared) sensor.
When movement is detected:

It activates a buzzer and/or LED to alert people nearby.
The system can optionally be extended to send SMS alerts or notifications with additional modules.
This project is affordable, easy to build, and a great starting point for anyone interested in electronics and basic IoT systems!

⚙️ Components Required

Component	Quantity
Arduino UNO / Nano -	1
PIR Motion Sensor	- 1
Buzzer / LED	- 1
Resistor (220Ω for LED) -	1
Jumper Wires
Breadboard (optional)	1
USB Cable -	1

🛠️ Circuit Diagram

VCC of PIR → 5V on Arduino
GND of PIR → GND on Arduino
OUT of PIR → Digital Pin (e.g., Pin 2) on Arduino
Buzzer/LED → Another Digital Pin (e.g., Pin 8)

🚀 How It Works

The PIR sensor detects infrared radiation emitted by objects.
When a human body or moving object crosses its field of view:
It sends a HIGH signal to the Arduino.
The Arduino activates the buzzer/LED to signal the detection.
If no motion is detected, the system remains silent/inactive.
