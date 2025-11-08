# Bluetooth Controlled Car

## Overview
This project implements a remote-controlled smart car using **Bluetooth communication** between an Android app (MIT App Inventor) and an Arduino board.  
The user can control the car's movement through a simple mobile app interface. 

## Hardware Used
- **MCU:** Arduino UNO 
- **Bluetooth Module:** HC-06 
- **Motor Driver:** L298N (H-Bridge) 
- Motor: V1 gear motor 
- **Battery Pack 8.4V** (power supply for motors & Arduino) 

## Software & Tools
- **Firmware Language:** Arduino C/C++ 
- **IDE:** Arduino IDE 
- **Mobile App:** MIT App Inventor 
- **Communication:** UART over Bluetooth 
- **Motor Control:** PWM + GPIO pins 

## Features 
- Control movement via smartphone: 
  - Forward / Backward 
  - Turn Left / Turn Right 
  - Stop 
- Real-time wireless communication 
- Expandable architecture (can add autonomous modes) 

## Project Structure
```
Control_Car/
├─ xebluetooth.ino # Arduino source code (.ino)
├─ control_app_1.aia/ # MIT App Inventor project (.aia)
├─ Readme.md/ # This files

```

## Getting Started
```bash
git clone https://github.com/MinhQuocNguyenHoang/Control_Car.git
# Open .ino file in Arduino IDE and upload
```
- Install & Connect Mobile App 
- Import .aia file in mobile_app/ into MIT App Inventor 
- Export and install APK on Android 
- Connect to HC-05 Bluetooth 
- Press buttons to control the car

## Future Improvements

- Add speed control (PWM throttle) 
- Add more UI controls & status display 
- Upgrade to ESP32 for IoT control (Wi-Fi / BLE) 

## Author 
Nguyễn Hoàng Minh Quốc<br>
GitHub: @MinhQuocNguyenHoang 