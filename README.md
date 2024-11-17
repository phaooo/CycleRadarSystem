# Radar Display and Control System

## Project Overview
This project implements a radar display and control system based on Arduino, primarily used for the LD-2451 radar module and SPRESENSE development board. The system provides a user interface to display radar information, configure parameters, and view device information.

## Main Features
- Radar target detection and display
- Parameter setting interface
- Device information display
- Firmware version view
- Button navigation control
- Animated transition effects

## Hardware Requirements
- SPRESENSE development board
- LD-2451 radar module
- OLED display
- 4 buttons (BTN0-BTN3)
- LED indicator

## Software Dependencies
- Arduino IDE
- U8g2 library (for OLED display)

## Usage Instructions
- After system startup, the welcome screen and version information are displayed.
- Press any button to enter the main menu.
- Use the up and down buttons (BTN0/BTN1) to navigate.
- Use the confirm button (BTN2) to select a menu item.
- In the settings menu, you can configure:
  - Maximum detection range
  - Minimum detection speed
  - Delay time
  - Signal-to-noise ratio level
  - Apply settings
  - Return

## Interface Description
- **Information Screen**: Displays version information.
- **Settings Screen**: Configures radar parameters.
- **Radar Display**: Real-time target information display.
- **About Screen**: Displays device information.

## Code Structure
### Communication Protocol
- **Serial Port 1 (Serial)**: 115200 baud rate, used for debugging.
- **Serial Port 2 (Serial2)**: 115200 baud rate, used for communication with the radar module.

## Author
Hao.P

## License
MIT License
