# IoT Based LED Notice Board

## Overview
This project is an IoT-based LED Notice Board system designed to display messages wirelessly in real time. It uses an Arduino Uno, ESP8266 Wi-Fi module, and P10 LED display to receive and show messages sent from a mobile application.

The system also supports solar-powered operation, making it suitable for remote and energy-efficient applications.

## Features
- Real-time wireless message updates
- Remote control using Wi-Fi
- Bright P10 LED display for clear visibility
- Solar-powered backup support
- EEPROM message storage
- Mobile Telnet app interface

## Components Used
- Arduino Uno
- ESP8266 Wi-Fi Module
- P10 LED Display (3 modules)
- 16x2 LCD Display
- Solar Panel
- 12V Lead Acid Battery
- LM7805 Voltage Regulator
- LM2596 Buck Converter
- Jumper Wires

## Technologies Used
- Arduino IDE
- Embedded C / C++
- UART Serial Communication
- Wi-Fi Communication
- EEPROM Storage

## Working Principle
1. User sends message from Telnet mobile app.
2. ESP8266 receives message through Wi-Fi.
3. Arduino processes the message.
4. Message is stored in EEPROM.
5. P10 LED display scrolls and shows the message.
6. Solar panel and battery provide backup power.

## Applications
- College and school notice boards
- Bus stands and railway stations
- Public announcement systems
- Offices and industries

## Future Scope
- Cloud integration
- Voice control
- Multi-language support
- Better mobile app UI
- Enhanced security

## Author
D. Naga Bhushan
