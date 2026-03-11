# Arduino UNO Board – Detailed Explanation

The Arduino Uno is one of the most popular microcontroller boards used for learning electronics, embedded systems, and robotics. It is based on the ATmega328P and is widely used by beginners and professionals to build interactive electronic projects.

---

## 1. Microcontroller (Brain of the Board)

The **ATmega328P microcontroller** is the main component of the Arduino Uno.

### Functions
- Executes the uploaded program
- Processes input signals from sensors
- Controls output devices like LEDs, motors, and displays

### Important Specifications
- Clock Speed: **16 MHz**
- Flash Memory: **32 KB**
- SRAM: **2 KB**
- EEPROM: **1 KB**

**Example:**  
If you write a program to blink an LED, the ATmega328P reads the code and sends signals to the output pin.

---

## 2. Digital Input / Output Pins

Arduino Uno has **14 digital pins (0–13).**

### Uses
- Turn LEDs ON/OFF
- Read button input
- Control relays, motors, and buzzers

### Example Code

```cpp
pinMode(2, OUTPUT);
digitalWrite(2, HIGH);
