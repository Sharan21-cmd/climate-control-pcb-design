🌡️ Climate Control System – PCB Design

A compact and efficient Climate Control PCB designed for monitoring and regulating temperature and humidity using embedded electronics.
This board integrates multiple sensors, a microcontroller, power regulation circuitry, and output drivers to control cooling/heating units.

🚀 Project Overview

This project focuses on building a complete hardware solution for climate control applications such as:

Greenhouse automation
Home/room temperature control
Industrial environment monitoring
Smart HVAC systems

The PCB is designed using KiCad 6/7/8/9 and follows proper routing, grounding, and noise-reduction guidelines.

🔧 Features
Sensing
🌡️ Temperature Sensor (e.g., DHT22, NTC, or DS18B20)
💧 Humidity Measurement
Real-time environment monitoring
Control
🔥 Heating element control (Relay / MOSFET)
❄️ Cooling fan/motor output
⚡ PWM-based fan speed control
Microcontroller
ESP8266 / ESP32 / STM32 / Arduino-compatible MCU
Supports WiFi (optional)
GPIO protection and filter network
Power
5V → 3.3V LDO/AMS1117 regulator
Reverse polarity protection
Fuse protection
Decoupling capacitors placed near IC pins
🖼️ Project Files

This repository contains:

/project_name.kicad_pro  
/project_name.kicad_sch  
/project_name.kicad_pcb  
/gerber/  
/bom/  
/readme.md  
🧩 PCB Highlights
2-layer compact PCB
Ground plane for noise reduction
Thick traces for relay/fan output
Sensor signals routed with noise isolation
Proper silkscreen labeling
Edge-cuts fully validated with DRC
