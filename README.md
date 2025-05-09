# embedded-sensor-node
 “Firmware for a temperature monitoring embedded system using ESP32 and DHT11 sensor.”
# 🌡️ Embedded Temperature Monitor with ESP32 and DHT11

A basic embedded firmware project for reading temperature and humidity data from a DHT11 sensor using ESP32, and displaying it over serial.

## 📦 Features

- Read temperature and humidity data via DHT11 sensor
- Print readings to UART serial terminal
- Periodic reading every 2 seconds using timer interrupt or delay
- Written in Embedded C using ESP-IDF or Arduino C

## 🧰 Tech Stack

- Language: C / Arduino C
- Microcontroller: ESP32
- Sensor: DHT11
- Interface: GPIO, UART
- IDE: VS Code + PlatformIO / Arduino IDE
- Build System: Make / CMake / PlatformIO

## 🧪 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/embedded-temperature-monitor.git
    ```
2. Open in PlatformIO or Arduino IDE
3. Flash to your ESP32 board
4. Open Serial Monitor to view data

## ⚙️ Hardware Required

- ESP32 Dev Board
- DHT11 Temperature & Humidity Sensor
- 10kΩ resistor (for pull-up)
- Breadboard & Jumper wires

## 🔌 Wiring Diagram

| DHT11 Pin | Connects to ESP32 |
|----------|-------------------|
| VCC      | 3.3V              |
| DATA     | GPIO 4            |
| GND      | GND               |

## 📸 Screenshots
*(Add images or GIFs of the serial output or hardware setup here)*

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
