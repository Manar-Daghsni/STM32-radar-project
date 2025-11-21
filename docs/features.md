# ✨ Features Documentation

## 1. Radar Scanning (0° → 180°)
- Servo rotates controlled via PWM  
- Adjustable scan resolution  

## 2. Real-Time Ultrasonic Measurement
- HC-SR04 triggered at each angle  
- Distance measured using Echo pulse width  
- Reliable readings up to ~4m  

## 3. LCD Live Display
Shows:
- Current angle  
- Distance measured  
- Status messages (Scanning...)  

## 4. Modular Firmware
- HAL-based drivers  
- Clean separation of modules:
  - servo.c / servo.h  
  - ultrasonic.c / ultrasonic.h  
  - lcd.c / lcd.h  
  - main.c  

## 5. Expandability
Project can be extended with:
- UART serial plotting  
- Bluetooth / WiFi IoT data logging  
- Full radar visualization on PC  
