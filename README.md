# IC-Based-Line-Following-Robot
Purely hardware-driven approach using digital logic gates and sequential logic to achieve autonomous navigation without using microcontroller 

## 📌 Project Overview
A line-following robot detects and follows a predefined path using sensors. While many modern implementations use microcontrollers and software-based control algorithms, this project takes a hardware-only approach.The robot processes the sensor signals using digital logic gates and generates real-time motor control signals directly from the hardware circuit.
A key feature of the project is the use of SR latches implemented using NAND gates to provide hardware memory. This allows the robot to remember the previous direction when the sensors temporarily lose the line, particularly when navigating dashed lines and sharp turns.

---

## 🎯 Objectives
- Design a line-following robot without a microcontroller.
- Implement navigation using digital logic gates.
- Investigate combinational and sequential logic for autonomous control.
- Implement hardware memory using SR latches.
- Interface digital logic with an H-bridge motor driver.
- Simulate and verify the design using Proteus 8 Professional.
- Develop and test a physical prototype.
- Improve reliability through power management and noise suppression.

---


## 🔧 Hardware Components

- TCRT5000 / IR Tracking Sensors--Line detection
- 74HC00 NAND Gate IC--Digital logic and SR latch implementation
- L293D Motor Driver IC--Motor direction and drive control
- DC Geared Motors--Robot movement
- LM2596 Buck Converter--Voltage regulation
- 18650 Li-ion Batteries--Power source
- Capacitors--Power stabilization and noise suppression
- Breadboard--Prototype implementation

The final design uses NAND gates as the fundamental logic element, including the implementation of the SR-latch memory.

---

## ⚙️ Motor Control

The L293D H-bridge motor driver interfaces the digital logic circuit with the DC motors.
Independent control of the left and right motors enables the robot to:

- Move forward
- Turn left
- Turn right
- Reverse direction
- Perform corrective movements

The logic outputs are connected to the L293D motor-control inputs to control the direction and operation of the motors.

---

## 📸 Project Images

### Final Robot
<img width="1030" height="766" alt="Screenshot 2026-09-21 123742" src="https://github.com/user-attachments/assets/7e1ee359-a9c5-4dcb-bc31-985f4795e078" />

---

## 🎥Demonstration Video

[Click here to watch the final demonstration](https://drive.google.com/file/d/1FZNAohmewppWNfGO5bwc0B_BDJ6VQ7H4/view?usp=sharing)

---

## 📄 Project Portfolio

The complete project report is available in the `report` folder


