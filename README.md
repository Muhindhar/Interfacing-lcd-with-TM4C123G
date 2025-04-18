# 📟 16x2 LCD Interfacing with TM4C123G (4-bit Mode)

This project demonstrates how to interface a 16x2 LCD display with the TM4C123G (Tiva C Series) microcontroller using 4-bit communication mode. The LCD displays two lines of text: **"Hello"** on the first line and **"Hii"** on the second.

> ✅ Ideal for beginners and embedded systems learners using Keil IDE and TM4C123G.

---

## 🧰 Hardware Used
- Tiva C Series TM4C123GXL LaunchPad
- 16x2 Alphanumeric LCD
- Breadboard & Jumper Wires
- Power Supply (via USB)
- Optional: Potentiometer for LCD contrast

---

## 🔌 Pin Configuration

| LCD Pin | Function      | Connected To      |
|---------|---------------|-------------------|
| RS      | Register Select | PA2              |
| RW      | Read/Write      | PA3 (tied LOW = write only) |
| EN      | Enable          | PA4              |
| D4–D7   | Data Lines      | PB4–PB7          |

---

## ⚙️ Software Details

- **IDE:** Keil uVision
- **Language:** C
- **Target MCU:** TM4C123GH6PM
- **Clock:** Internal 16 MHz

---

## 📂 File Overview

| File | Description |
|------|-------------|
| `main.c` | Main source code for LCD initialization and display |
| `tm4c123gh6pm.h` | Header file for TM4C123 register definitions (provided by TI or Keil) |

---

## 📋 Features

- ✅ 4-bit LCD communication
- ✅ Displays static text on both LCD lines
- ✅ GPIO configuration using direct register programming
- ✅ Delay-based LCD control
- ✅ Clean and readable embedded C structure

---

## 🖥️ Output
Can be viewed in your LCD display

🧑‍💻 Author
Muhindhar
KIOT - Department of ECE
