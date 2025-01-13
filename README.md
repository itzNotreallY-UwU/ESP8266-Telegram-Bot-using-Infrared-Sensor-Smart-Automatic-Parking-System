Introduction
This project, named IR_Telebot2.0, aims to monitor and manage car parking slots using an ESP8266 WiFi module and infrared sensors. It provides real-time updates on parking slot availability via a Telegram bot and includes automatic notifications for slot occupancy and vacancy.

Features
-Real-time monitoring of car parking slots using infrared sensors.
-WiFi connectivity and Telegram integration for remote notifications.
-Notifications for slot occupancy and vacancy.
-Periodic summary of parking slot status sent to Telegram.

Hardware Components
-ESP8266 WiFi module
-Infrared sensors (IR) for four parking slots
-Connecting wires and a breadboard

Software Requirements
-Arduino IDE
-ESP8266WiFi library
-UniversalTelegramBot library
-NTPClient library
-TimeLib library

Setup and Configuration

Hardware Setup:
Connect infrared sensors to ESP8266 as follows:
~IR1 to D0
~IR2 to D3
~IR3 to D6
~IR4 to D7

Software Setup:

Configure WiFi and Telegram Bot: Define your SSID, password, and Telegram bot token in the code C++:
const char* ssid = "Your_SSID";
const char* password = "Your_PASSWORD";
const char* telegramToken = "Your_TELEGRAM_TOKEN";
const char* chat_id = "Your_CHAT_ID";

Install Libraries: Ensure the required libraries are installed in the Arduino IDE:
-ESP8266WiFi
-UniversalTelegramBot
-NTPClient
-TimeLib

Acknowledgments
-ESP8266
-Telegram
-Arduino
