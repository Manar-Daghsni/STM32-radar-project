## 1. Components Used

| Component | Model | Role |
|----------|--------|------|
| STM32 Nucleo-64 F401RE | MCU | Controls servo, reads sensor, drives LCD |
| HC-SR04 | Ultrasonic sensor | Measures distance |
| SG90 / MG90 | Servo motor | Rotates radar platform |
| LCD 16x2 | Display | Shows angle + distance |
| Breadboard + wires | — | Connections |

---

## 2. Pinout Connections

### 🟦 STM32 → Ultrasonic (HC-SR04)
| STM32 Pin | HC-SR04 |
|-----------|---------|
| PA0 | Trigger |
| PA1 | Echo |
| 5V | Vcc |
| GND | GND |

### 🟧 STM32 → Servo
| STM32 Pin | Servo |
|-----------|--------|
| PB6 (TIM4_CH1) | Signal (PWM) |
| 5V | Vcc |
| GND | GND |

### 🟩 STM32 → LCD (4-bit mode)
| STM32 Pin | LCD Pin |
|-----------|----------|
| PB0 | RS |
| PB1 | EN |
| PA4 | D4 |
| PA5 | D5 |
| PA6 | D6 |
| PA7 | D7 |
| 5V | Vcc |
| GND | GND |

---
