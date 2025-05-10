**I2C Scanner for ESP32** 📡

This project scans and lists the I2C devices connected to the ESP32 microcontroller. The ESP32 communicates using the I2C protocol and identifies any connected devices by scanning all possible I2C addresses (from 1 to 127). The addresses of detected devices are printed to the Serial Monitor.

**Features** ✨

-Detects connected I2C devices 🔍

-Displays device addresses in hexadecimal format 💻

-Configurable SDA and SCL pins (**default: GPIO21 for SDA and GPIO22 for SCL**) 🔌

-Simple setup and easy to use ⚡

**Requirements 📝**

-ESP32 microcontroller 🌐

-Arduino IDE with ESP32 support 💻

**Connected I2C devices 🔗**

**Instructions 🚀**

-Connect the ESP32 to your computer via USB. 🔌

-Install the ESP32 board in the Arduino IDE if you haven't already. 🛠️

-**Upload the code to your ESP32 board. 📤**

-Open the Serial Monitor (set baud rate to 115200). 🖥️

-The connected I2C devices will be listed by their I2C address in the Serial Monitor. 📜

**Code Description 📝**

-The code scans I2C addresses from 1 to 127. 🔍

-If a device responds, its I2C address is printed in the Serial Monitor. 💬

-The default SDA and SCL pins are GPIO21 and GPIO22, but you can change them as needed. ⚙️

**Example Output 💡**

I2C device found at address 0x3C
I2C device found at address 0x68
No I2C devices found

**License 📜**
-This project is open-source and available for personal and educational use. 🆓
