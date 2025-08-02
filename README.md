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
Push Button -Acts as a person detection sensor in simulation. When pressed, it tells the Arduino that someone is approaching the slipper.
10kΩ Resistor -Used as a pull-down resistor for the push button. Keeps the input pin at LOW when the button is not pressed, avoiding false triggers.
Piezo Buzzer -Simulates the voice alert. When a person is detected (button pressed), the buzzer makes a beeping sound like saying “Don’t touch me!”.
DC Motor (or LED)[4-8] -Controls mechanical legs for movement (2 servos/leg recommended)
Jumper Wires -Used to connect everything together — from the Arduino to the breadboard, and between components.
#Spec	Value / Description:
Controller	-ESP32 Dev Board (with BLE support)
Motor Type-	SG90 Servo Motors (~180° rotation, 1.8–2.5 kg/cm torque)
Detection Range	-2–15 cm (Ultrasonic Sensor)
Battery Life	-~1–2 hours continuous movement (7.4V 2200mAh battery)
Bluetooth Range	-~10–15 meters (BLE)
Max Walking Speed	-~0.1–0.3 m/s (varies with leg configuration)
Slipper Base Material	-PLA, MDF, Acrylic or lightweight aluminum
Total Weight per Slipper-	~250–400 grams (depending on material & number of servos)
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

🔁 Calibrated servo gait to achieve smooth walking (not perfect — but hilarious!)

