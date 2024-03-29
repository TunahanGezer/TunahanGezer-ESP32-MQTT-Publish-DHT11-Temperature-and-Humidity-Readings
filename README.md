# IoT Project: Temperature and Humidity

This project utilizes an ESP32 microcontroller board to collect temperature and humidity data from a DHT11 sensor and send it to Adafruit IO. This enables accessing this data from anywhere via any device with an internet connection.

## Hardware and Libraries Used

- ESP32 microcontroller board
- DHT11 temperature and humidity sensor
- `WiFi.h` for WiFi connection
- `Adafruit_MQTT` and `Adafruit_MQTT_Client` for MQTT communication
- Adafruit IO is used to send temperature and humidity data.

## Setup

1. Open Arduino IDE and install the necessary libraries (WiFi, Adafruit MQTT, SimpleDHT).
2. Open the `main.ino` file in Arduino IDE.
3. Update your WiFi connection details (`WLAN_SSID` and `WLAN_PASS`) and Adafruit IO credentials (`IO_USERNAME` and `IO_KEY`).
4. You can track your temperature and humidity data in real-time by clicking [this link](https://io.adafruit.com/tunahangezer/dashboards/temp-and-humu) on the Adafruit IO web interface.

## How It Works

1. Connect your ESP32 device to your computer via USB.
2. Upload the code via Arduino IDE and start the ESP32.
3. Monitor your temperature and humidity data on the Adafruit IO web interface.

## Notes

- To link this project to your personal Adafruit IO account, you need to create an account on the Adafruit IO website.
