# ESP32-ARDUINO-MHI-TOUCHSCREEN
SMARTER HMI TOUCHSCREEN &amp; SERIAL CONTROL SYSTEM USING ESP32 AND ARDUINO UNO
🛠️ Hardware Components
ESP32 Dev Module (Master / HMI Controller)
Arduino UNO (Slave / Hardware Controller)
4.0" TFT Touch Screen ($320 \times 480$ resolution, ST7796 Driver, XPT2046 Touch Controller)
Relay Module & Sensors Board (Custom soldered Perfboard)
⚡ Key Features & Protocols
SPI Protocol: High-speed display driving and touch screen data reading using the `LovyanGFX` library.
Hardware PWM: Smooth backlight brightness management.
UART / Serial Communication: Inter-board communication via `SoftwareSerial` to send real-time control commands from ESP32 to Arduino UNO.
📂 Repository Structure
`/src/ESP32_HMI_Display.ino` - Main firmware for display and touch UI.
`/src/Arduino_Relay_Control.ino` - Firmware for command processing and relay control.
`/docs/schematic.png` - Circuit wiring diagram.
💻 Software & Libraries
Arduino IDE 2.x
LovyanGFX
SoftwareSerial Library
