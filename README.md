# AIOT Aquaculture

## Project Objective
The primary objective of this project is to regulate water quality parameters. Specifically (TDS, Turbidity, Water level, and Temperature). Each parameter is equipped with sensors and actuators to enable automatic action. Furthermore, the system contains a feeding system.
you can see it from here:
https://www.youtube.com/watch?v=zCe8Re3kF0I

## How Does It Work
- The sensor sends signals to the ESP32, which is the microcontroller used in this project.  
- Then the ESP32 processes this data and decides if it will act or not.  
- The ESP32 sends the data to the database to save it.  

### Operations Without Sensors
- A feeding system that operates at significant times per day  

## Monitoring and Control
- The system also offers easy ways to monitor the data from everywhere using a mobile application ( it is not exactly a mobile app; it is a control panel made by MQTT), which makes the system affordable everywhere.  
- The panel also allows the user to control some actions, like powering the pump and powering the system, or powering it off if any problem occurs.

## Hardware Components
- ESP32  
- Double Face PCB  
- DC Motor (12V - RS360)  
- Mini Boat Fan  
- Ultrasonic Module  
- Ultrasonic Sensor  
- Ultrasonic Sensor Holder  
- Mini Water Pump - DC 3–6V - 120L/H  
- Relay Module 4 Channel  
- Relay Module (5V–10A) 1 Channel  
- DS18B20 Waterproof Temperature Sensor  
- Water Turbidity Sensor  
- TDS Sensor Meter V1.0 Board Module  
- Mini Micro Servo Motor SG90  
- Motor Driver L298N  
- LM2596S DC-DC Adjustable  
- Heater  
- Fish Tank  
- Fish Tank Mini Aerator Oxygen Pump  
- Power Supply  
- Electrical Power Cable  
- Flexible Clear Hose Tube  
- Jumper Wire 20cm Male to Female  
- Jumper Wire 20cm Male to Male  
- Breadboard Solderless 830  
- Logic Level Converters  
- Connectors  
- Resistors (4.7 kΩ)  
- Capacitors (220 µF, 470 µF)  

## Used Tools
- MQTT used for building the panel
  <img width="851" height="478" alt="image" src="https://github.com/user-attachments/assets/8f08b6e8-c0d9-4895-9273-13ca1141424a" />

- Arduino IDE to program the ESP32
  <img width="1366" height="727" alt="Screenshot 2026-04-07 180025" src="https://github.com/user-attachments/assets/682782b1-0857-49c8-ac49-83c60e2d509c" />

- SQL act as the data base for our project  
- KIkad used to make the shematic diagram
  <img width="857" height="587" alt="Screenshot 2026-03-17 161740" src="https://github.com/user-attachments/assets/adef1f64-6edc-4b71-b661-d479277b7fbd" />
- Blender used to make the 3D design for project
  
<img width="1366" height="727" alt="Screenshot 2026-03-21 231026" src="https://github.com/user-attachments/assets/ea343ff7-44d3-479c-9a98-df3c17c38ab8" />
