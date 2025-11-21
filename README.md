# 🎯 STM32 Radar System — Servo + Ultrasonic + LCD Display

This project implements a **mini radar scanning system** using an **STM32 Nucleo-64**, a **servo motor**, and an **ultrasonic sensor**.  
The system sweeps from 0° to 180°, measures distance in real-time, and displays the results on an **LCD screen**.

This project demonstrates practical embedded engineering skills:

- Real-time peripherals control  
- STM32 HAL development  
- Sensor/actuator integration  
- Display-based data visualization  
- IoT-ready architecture

---

## 🚀 Features

- Continuous sweeping radar motion (0° ↔ 180°)
- Real-time ultrasonic distance measurement
- Instant display on 16×2 LCD
- Modular STM32 HAL project
- Easily expandable (BLE, Wi-Fi, Serial, UART monitoring)

---

## ⚙️ System Modes

### 🔄 Scanning Mode
- Servo rotates step by step across a defined angle range  
- Ultrasonic sensor measures distance at each position  
- LCD shows current angle and detected distance  
- Can detect objects in front of the radar in semi-real time

### 💻 Debug / Extension Mode (Optional)
- Data can also be sent over UART or serial  
- Useful for visualization on PC dashboards

---

## 🧠 Hardware Used

| Component | Model |
|---|---|
| MCU | STM32 Nucleo-64 (e.g., F401RE) |
| Sensor | HC-SR04 Ultrasonic |
| Actuator | SG90 / MG90S Servo Motor |
| Display | 16×2 LCD |
| Misc | Jumper wires, breadboard / custom PCB |

---

## 🖼️ Project Images

### 🛠️ Final Build  
![Final Build](media/radar_final.jpg)

### ⚡ Wiring Diagram  
![Wiring Diagram](media/wiring.png)

### 📟 LCD Output  
![LCD Output](media/lcd_output.jpg)

You can place your real photos or diagrams in `media/` as shown.

---

## 📂 Project Structure

```text
stm32-radar/
│── firmware/
│   ├── Core/
│   ├── Drivers/
│   └── STM32CubeIDE project files
│
│── media/
│   ├── wiring.png
│   ├── pinout.png
│
│── docs/
│   ├── system-architecture.md
│   ├── hardware.md
│   └── features.md
│
│── README.md
```

