Contactless Temperature Detector
Overview
This project is a non-contact temperature detection system using an MLX90614 infrared sensor and an Arduino Uno. It measures the temperature of a person entering through a door and triggers a buzzer if the detected temperature exceeds 38°C (fever threshold).

Hardware Requirements
Arduino Uno
MLX90614 Infrared Temperature Sensor
Buzzer (Piezo)
Jumper Wires
Breadboard

Software Requirements
Arduino IDE
Adafruit MLX90614 Library (Install via Library Manager)

Installation & Setup
Download & Install the Arduino IDE.
Install Adafruit MLX90614 Library:
Open Arduino IDE → Go to Sketch → Include Library → Manage Libraries.
Search for "Adafruit MLX90614" and click Install.
Connect the Components as per the wiring diagram:
MLX90614 Sensor Connections:
VCC → 3.3V or 5V
GND → GND
SDA → A4
SCL → A5
Buzzer Connection:
Positive → Digital Pin 7
Negative → GND
Upload the code to the Arduino.
