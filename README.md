# BlueBot

BlueBot is a two-wheel robot built using an Arduino Uno and controlled wirelessly via Bluetooth. This project was created as part of a student comprehensive examination in the engineering physics course to explore hands-on electronics, microcontroller programming, and Bluetooth communication. The robot can drive in four directions and is operated using simple commands sent from a phone or computer.

It uses an Arduino Uno compatible board, an L298N H-Bridge motor driver to control two DC motors, an HC-05 Bluetooth module for wireless input, and it is all assembled on an MDF laser-cut robot chassis with jumper wires (male-to-female). Power is supplied by a 9V battery to keep the robot mobile and untethered.

Made by:
- Myles Elman
- Justin Ferreira

## ⚙️ How It Works

1. Power the Arduino using a 9V battery via the barrel jack.
2. Connect to the HC-05 module using a Bluetooth terminal on a computer (iPhone not supported).
3. Send the following single-letter commands:
   - `F` – Forward
   - `B` – Backward
   - `L` – Turn Left
   - `R` – Turn Right

## ✅ Project Highlights

- Fully wireless movement via Bluetooth
- No breadboard or resistors needed in final design
- Compact and efficient layout with minimal wiring
- Successfully tested on different indoor surfaces
- Powered entirely by a single 9V battery

## 🔧 To Do

- Add ultrasonic sensor for obstacle detection
- Upgrade to HC-10 or BLE module for full device compatibility
- Add wheel encoders for more precise steering
- Develop a custom mobile app interface

## 📁 Files

- `BlueBot.jpeg` – Final Diagram of BlueBot
- `Arduino Project CE Lab Report (1).docx` – Full project report
- `Demo.mov` - Demo of BlueBot
- `Lab_Report.md` - Full project report (markdown)
- `main_code.ino` - Full Code

## 🙌 Credits

Thank you to Joel Trudeau and Dawson College for organizing and providing us with necessary material! It was very fun to assemble and code.

