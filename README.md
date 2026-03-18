 ESP8266 Blynk LED Control

  This project allows you to control multiple LEDs using an ESP8266 (NodeMCU) and the Blynk IoT platform via a mobile app.

 Features

* Control 4 LEDs remotely using Blynk app
* Real-time ON/OFF switching
* WiFi-based IoT control
* Sends device uptime to Blynk dashboard

 Tech Stack

 *ESP8266 (NodeMCU)
* Arduino IDE
* Blynk IoT Platform
*Embedded C++

 Setup Instructions

Install Arduino IDE and ESP8266 board support
Install Blynk library

Replace:

BLYNK_TEMPLATE_ID
BLYNK_AUTH_TOKEN
ssid and password
Upload code to ESP8266

Create buttons in Blynk app for:


V0 → LED1
V1 → LED2
V2 → LED3
V3 → LED4

 Pin Configuration

LED	GPIO Pin
LED1	D0
LED2	D1
LED3	D2
LED4	D3

Functionality

Virtual pins control LEDs via Blynk app

Timer sends uptime every second

Device connects automatically to WiFi and Blynk Cloud

Note
 
Avoid using delay() in the loop to ensure smooth Blynk operation.
