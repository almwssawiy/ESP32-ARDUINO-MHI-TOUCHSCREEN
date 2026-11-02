Smart HMI Touchscreen & Serial Control System
An advanced, high-performance embedded control system built around the ESP32 and Arduino UNO microcontrollers. This project demonstrates real-time Human-Machine Interface (HMI) touch control, inter-board serial communication, and modular C/C++ firmware design.
________________________________________
🛠️ Hardware Components
ESP32 Dev Module: Master / HMI Controller.
Arduino UNO: Slave / Hardware Controller.
4.0" TFT Touch Screen: 320 × 480 resolution, ST7796 Driver, XPT2046 Touch Controller.
Relay Module & Sensors Board: Custom soldered Perfboard assembly.
________________________________________
⚡ Key Features & Communication Protocols
SPI Protocol: High-speed display driving and touch screen data reading using the `LovyanGFX` library.
Hardware PWM: Smooth backlight brightness management and pulse control.
UART / Serial Communication: Inter-board communication via `SoftwareSerial` for real-time control command transmission between ESP32 and Arduino UNO.
________________________________________
📁 Repository Structure
```text
├── src/
│ ├── ESP32_HMI_Display.ino # Main firmware for display and touch UI
│ └── Arduino_Relay_Control.ino # Firmware for command processing and relay control
└── docs/
└── schematic.png # Circuit wiring diagram


👤 Author & Contact
Younes Almwssawiy
Embedded Systems / Firmware Engineer
Email: [younesaliabed1@gmail.com](mailto:younesaliabed1@gmail.com)
LinkedIn: linkedin.com/in/younes-almwssawiy-163b2a447
GitHub: github.com/almwssawiy
Location: Bruges, Belgium
