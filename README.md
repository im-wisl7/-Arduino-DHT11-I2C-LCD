# -Arduino-DHT11-I2C-LCD
🌡 A simple Arduino project that reads temperature and humidity using a DHT11 sensor and displays the values on a 16x2 I2C LCD.

This project is beginner-friendly and perfect for learning:

Sensor integration

I2C communication

Embedded systems basics

Real-time data display

🧰 Components Used

Arduino Uno

DHT11 Temperature & Humidity Sensor

16x2 LCD with I2C module

Jumper wires

🔌 Wiring
🌡 DHT11 Connections
DHT11 Pin	Arduino Uno
VCC	5V
GND	GND
DATA	D2

📟 I2C LCD Connections
LCD Pin	Arduino Uno
VCC	5V
GND	GND
SDA	A4
SCL	A5
📚 Required Libraries:

Adafruit DHT Sensor Library

Adafruit Unified Sensor

LiquidCrystal_I2C


🚀 Features

Reads temperature in Celsius

Reads humidity percentage

Displays values on 16x2 LCD

Error detection if sensor fails

🖥 How It Works

The DHT11 reads temperature and humidity.

Arduino processes the sensor data.

Values are displayed on the LCD using I2C communication.

The screen updates every 2 seconds.

🎯 Learning Outcomes

Through this project, I practiced:

Reading digital sensors

Using external libraries

Working with I2C communication

Debugging hardware issues

Building clean embedded system structure

👩🏻‍💻 Author

wissal (High School Mechatronics Enthusiast)
Aspiring Robotics & Engineering Student 🚀
