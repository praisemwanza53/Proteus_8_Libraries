# Proteus Library Components Overview

This document provides an overview of various components available in the Proteus library, detailing their functionalities, working principles, and instructions for installation.

---

## How to Add Library Files to Proteus

1. **Locate the Files:**
   - You will typically have two types of files for each library: `.LIB` and `.IDX`, and sometimes `.HEX` or `.DLL`.
   - Also, there may be a `MODELS` folder containing required simulation models.

2. **Navigate to Proteus Library Folder:**
   - Go to the installation directory of Proteus (commonly: `C:\ProgramData\Labcenter Electronics\Proteus 8 Professional\LIBRARY`).

3. **Paste the Library Files:**
   - Copy and paste the `.LIB` and `.IDX` files into the `LIBRARY` folder.
   - If a `MODELS` folder is provided, copy its contents into the same directory or within the `MODELS` sub-folder if it exists.

4. **Restart Proteus:**
   - Close and reopen Proteus for the new components to be loaded.

5. **Use the Component Mode:**
   - Open any schematic and select "P" to search for new components using the keywords (e.g., "IR Sensor", "Arduino UNO", etc.)

---

## Component Library Overview

### AC Dimmer Module
Controls AC loads (e.g., lights, fans) by adjusting the phase angle of the AC waveform. Uses TRIAC and zero-cross detection for phase control.

### Analog Gauge Meter
Simulates analog meters using needle movement. It represents analog values such as voltage or current.

### Arduino Mega2560
ATmega2560-based board with more I/O pins, used in large embedded projects.

### Arduino UNO
Popular development board based on ATmega328P. Processes signals from sensors and controls actuators.

### Current Sensor Modules
Measure current using magnetic field detection. Converts current to voltage output.

### Dice Model
Simulates an electronic dice. Uses a microcontroller to display numbers 1–6 via LEDs.

### ENC28J60 Ethernet Module
Enables Ethernet connectivity in Arduino-based projects. Handles physical and data link layer communications.

### Fan Models
Visual animated models to simulate fan motion in designs.

### Flame Sensor
Detects fire or flame using IR radiation emitted by flames.

### Flex Sensor
Changes resistance when bent. Used for gesture sensing or physical input.

### FSR 406 Sensor
Force Sensing Resistor. Resistance decreases with increasing force or pressure.

### Hall Sensor Module
Detects magnetic fields. Outputs voltage based on magnetic field strength.

### INA219AID
Measures voltage, current, and power via I2C. Monitors shunt resistor voltage drop.

### IR Sensor Module
Detects nearby objects using emitted and reflected IR light.

### LDR Sensor
Light-dependent resistor. Resistance decreases as light intensity increases.

### Low Voltage Detection Sensor
Compares input voltage with threshold to detect undervoltage.

### MC34063 Boost Converter
Steps up input voltage using inductor-based switching and MC34063 IC.

### Modbus RTU Temp Hmd Sensor
Measures temperature and humidity. Uses Modbus RTU protocol for communication.

### MQ2 Gas Sensor
Detects combustible gases like LPG and methane. Outputs analog value based on concentration.

### New PIR Sensor
Detects motion via changes in IR radiation.

### NodeMCU
ESP8266-based development board with built-in Wi-Fi. Used for IoT applications.

### Optical Fiber
Simulates light transmission via optical fiber. Demonstrates optical communication.

### Rain Sensor
Detects presence of rain using conductive grid.

### Reed Switch
Magnetic switch that opens/closes when exposed to magnetic field.

### Relay Modules
Electromechanical switches that allow microcontrollers to control high voltage.

### Rotary BCD Switch
Manual selector that outputs BCD value based on switch position.

### Rotary Encoder
Detects direction and amount of rotation.

### Soil Moisture Sensor
Detects soil water content by measuring conductivity.

### TDS Module
Measures Total Dissolved Solids by electrical conductivity in water.

### Tilt Switch Model
Detects orientation changes using a metallic ball or contact inside.

### Touch Sensor
Capacitive sensor detecting human touch.

### Turbidity Sensor
Measures clarity of water by detecting suspended particles.

### Voltage Sensor Module
Monitors voltage levels, often using a voltage divider circuit.

### WS2812 LED Matrix
Simulates RGB LED matrix controlled by a single digital line.

### Sound Sensor
Detects sound levels through a microphone. Outputs analog or digital signal.

### Stepper Driver Board
Controls stepper motors. Converts logic signals into step pulses.

### Raspberry Pi 3 & 4 Modules
Simulates RPi boards. Used for prototyping embedded Linux-based systems in Proteus.

---

> This library has been tested with Proteus version 8.17 and later. If using an older version, some modules may not function correctly.

---

## End of Document

