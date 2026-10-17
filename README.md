# ESP32 RFID Attendance System

## Project Overview

This project is an RFID-based attendance system developed
using an ESP32 microcontroller.

The system identifies registered RFID cards and records
attendance using Google Sheets. It also sends Telegram
notifications when a registered card is tapped.

## Objectives

- Identify users using RFID cards.
- Record attendance electronically.
- Integrate the system with Google Sheets.
- Send notifications through Telegram.

## Hardware Components

- ESP32 development board
- RFID reader
- RFID cards or tags
- Power supply

## Technologies Used

- Arduino IDE
- ESP32
- RFID
- Wi-Fi
- Google Sheets integration
- Telegram notifications

## Working Principle

1. The RFID reader scans a card.
2. The controller reads the card identifier.
3. The system checks whether the card is registered.
4. Attendance is recorded through the online integration.
5. Telegram notifications are sent according to the
   configured notification logic.
    
## Future Improvements

- Reconstruct and document the firmware.
- Improve error handling.
- Add clearer feedback for registered and unregistered cards.
- Document the circuit connections.
