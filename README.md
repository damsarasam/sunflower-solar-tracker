# Solar Tracking System using Arduino

**Description:**
This project implements a solar tracking system using Arduino and Light Dependent Resistors (LDRs). The system continuously monitors the light intensity from different directions using two LDRs and adjusts the position of a servo motor to maximize solar energy capture. 

**Components:**
- Arduino board
- Servo motor
- Two Light Dependent Resistors (LDRs)
- Connecting wires

**Operation:**
1. The LDRs detect the intensity of light from different directions.
2. The Arduino reads the analog values from the LDRs.
3. The program calculates the difference in light intensity between the two sensors.
4. Based on the difference, the program adjusts the position of the servo motor to align the solar panel towards the direction with maximum sunlight.
5. The servo motor continuously adjusts its position to track the sun's movement throughout the day.

**Setup:**
- Connect one LDR to pin A0 and the other LDR to pin A1 of the Arduino board.
- Attach the servo motor to pin 11 of the Arduino board.
- Ensure proper power supply to the Arduino and servo motor.

**Instructions:**
1. Upload the provided Arduino code to the Arduino board.
2. Power on the system and place the LDRs in an open area where they can detect sunlight.
3. The servo motor will automatically adjust its position to track the sun's movement and maximize solar energy capture.

**Notes:**
- Adjust the error value in the code to fine-tune the sensitivity of the system.
- Ensure proper calibration and testing before deploying the system in a real-world environment.
- Take necessary precautions to protect the electronics from environmental factors such as moisture and dust.
