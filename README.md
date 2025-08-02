

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/0e6f22e7-b9ed-418b-8cf5-567690fffac7" />
# Feet-me-not
"because not every slipper wants to be stepped on."


#Team name:
Nutella


#Team members: 
Shreyaa SB-GECT
Gouri Kalyani S-GECT


#Project description:
Ever caught someone trying on your slippers? Meet the Stranger-Repellent Slippers, a quirky yet smart innovation designed to detect intruders and roll away in protest!


#The Problem (that doesn't exist):
Solving the world's most unnecessary problem- strangers trying on your slippers.


#The Solution (that nobody asked for):
#Move-away slippers with legs-
Finally, a solution to the age-old problem of strangers stealing your slippers — that no one actually has.
They detect intruders and walk away… because your slippers have trust issues now.Using Bluetooth Low Energy (BLE), the slippers pair with the owner’s smartphone and stay put only when the owner's device is nearby. If another person approaches — they run away.


#Technical Details:
#Technologies/Components Used:
Arduino Uno -The brain of your project. It reads input from the push button and controls output to the motor and buzzer based on code you upload.
Breadboard -A platform to connect all components easily without soldering. It allows temporary circuit building and easy changes.
potentiometer -Acts bluetooth to detect owner's presence.
10kΩ Resistor -Used as a pull-down resistor for the push button. Keeps the input pin at LOW when the button is not pressed, avoiding false triggers.
Piezo Buzzer -Simulates the voice alert. When a person is detected (button pressed), the buzzer makes a beeping sound like saying “Don’t touch me!”.
DC Motor (or LED)[4-8] -Controls mechanical legs for movement (2 servos/leg recommended)
Jumper Wires -Used to connect everything together — from the Arduino to the breadboard, and between components.


#Spec	Value / Description:
Arduino Uno 1-Main microcontroller
Ultrasonic Sensor (HC-SR04) 1-Detect approaching person
Piezo Buzzer 1-Sound alert
LED 1
Visual alert 220Ω Resistor 2-1 for LED, 1 for transistor base
DC Motor 1-Motion when stranger is detected
NPN Transistor (e.g., 2N2222 or TIP120) 1
Switch motor safely
Flyback Diode (e.g., 1N4007) 1
Protect from motor back EMF
Potentiometer 1
Simulate Bluetooth signal (owner presence)
Breadboard 1 Component layout
Jumper Wires 15–20 Wiring connections


#Implementation
#Phase 1: Planning & Design
✅ Identified key idea: slippers that walk away from strangers using Bluetooth + sensors + robotic legs

✏️ Sketched rough layouts in paper and modeled leg mechanism in Creo CAD for clarity

💡 Finalized features: proximity sensing, owner-only behavior, servo-leg motion

#Phase 2: Electronics Setup
👣 Used an Ultrasonic sensor (HC-SR04) to detect approaching feet

📱 Paired the slipper with the owner’s phone via ESP32 BLE

🤖 If owner not detected → activates movement using servo motors

🔋 Powered by a 7.4V Li-ion battery for portability
Phase 3: Coding & Integration
👨‍💻 Wrote Arduino code to:

Continuously scan for owner’s Bluetooth MAC

Trigger leg motion when stranger detected

Stop movement if owner is near


For Hardware:

# Schematic & Circuit
![WhatsApp Image 2025-08-02 at 08 43 25_243a64cb](https://github.com/user-attachments/assets/5b43cd40-bf97-4b9b-a370-33d776203ca4)
![WhatsApp Image 2025-08-02 at 08 52 44_ea979617](https://github.com/user-attachments/assets/ee57be91-4b62-4eeb-8e1d-c80ae073b764)

![WhatsApp Image 2025-08-02 at 08 49 08_3b632d64](https://github.com/user-attachments/assets/52ee2cb7-db0b-4a96-aec5-ee94458e1c0b)

# Build Photos

<img width="802" height="445" alt="image" src="https://github.com/user-attachments/assets/53df0516-9c9d-4b48-b3a2-07494a9c0259" />  - Design of slipper

<img width="1920" height="1080" alt="Screenshot (143)" src="https://github.com/user-attachments/assets/a332477f-4c00-407b-ab6f-261ca31a46ab" />  -  design of thigh of leg.
           

<img width="507" height="480" alt="image" src="https://github.com/user-attachments/assets/5735dcce-11ea-49ab-a0b7-d6979204bc6e" />  -design of leg.


### Project Demo
# Video
https://go.screenpal.com/watch/cTjnnCnIpQO
design and simulation of working of leg.



## Team Contributions
- Shreyaa SB: Ideator,Designing and simulation of leg ,slipper in creo software
- Gouri Kalyani S: Tinkercad simulation


---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--25-25?link=https%3A%2F%2Fwww.tinkerhub.org%2Fevents%2FQ2Q1TQKX6Q%2FUseless%2520Projects)


