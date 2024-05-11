Temperature Control System using 8086 Microprocessor

Overview:
    This project demonstrates a simple temperature control system using the 8086 microprocessor. The system monitors the temperature and activates a fan motor based on predefined temperature thresholds.

Features
    - Monitors the ambient temperature.
    - Controls the fan motor based on temperature conditions.
    - Provides visual feedback through LEDs.


Components Used:
    - 8086 Microprocessor: The heart of the system, responsible for processing instructions.
    - LM35 Temperature Sensor: Measures the ambient temperature.
    - Fan Motor: Controlled by the microprocessor based on temperature conditions.
    - LEDs: Indicate system status (e.g., fan on/off).


Implementation
  1- Assembly Code (temperature.asm):
      - Reads temperature data from the LM35 sensor.
      - Compares the temperature with predefined thresholds (e.g., 23°C and 33°C).
      - Activates the fan motor if the temperature exceeds the upper threshold or falls below the lower threshold.
      - Updates the LED status accordingly.
  2- Circuit Diagram (temperature control.pdsprj):
      - Designed using Proteus.
      - Includes the 8086 microprocessor, LM35 sensor, fan motor, and LEDs.
      - Connects the components as per the - project requirements.


Usage:
  1- Setting Up the Emulator:
    - Install emu8086 and open the temperature.asm file.
    - Assemble the code and save it in .com format.
  2- Simulating the Circuit:
    -  Open Proteus and import the project file.
    - Configure the 8086 component to use the previously saved .com file.
    - Run the simulation to observe the fan motor behavior based on temperature changes.


Notes:
    - Adjust the temperature thresholds in the assembly code as needed.
    - Ensure proper connections between components in the Proteus circuit.
    - Experiment with different temperature values to observe the system’s behavior.


Credits
This project was created by:
  - Our team:
    - خالد احمد احمد عوض خضر
    - حسين محسن عبدالرحمن سليم
    - احمد اسامة حسن
    - مازن اسامة محمد محمد
    - حازم محمد محي الدين
    - محمد جمال محمود علي
    - احمد محمد محمود حبيب
    - احمد محمود فهيم بكري
    - سلمى محمد السيد عوض
    - زياد تامر محمود محمد
    - عبدالرحمن ياسر علي
    - احمد عصام سمير محمد