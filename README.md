# Power Delivery Board for UBC Rocket
This power board consists of a Battery Management System (BMS) Frontend and dual buck converters (3.3V/5V). 

# Specifications
The BMS Frontend allows up to 6-Series LiPo Batteries with an adjustable current setting enabled by a hall-effect current sensor. 
All BMS processing is done by an STM32F0 Microcontroller and a TI BMS Analog Frontend (AFE) chip via I2C. 
The dual buck converters are specified to have a hardware-set current limit of 3A for both 3.3V and 5V outputs. 
Use USB-C to provide power to the 3.3V rails for the BMS Frontend such that there is no need to use an external power supply to program the MCU.

# Design Files
Root Structure: <img width="1036" height="736" alt="{155447C0-0820-4391-AAB2-6B3763590504}" src="https://github.com/user-attachments/assets/2dc2beec-778c-4b28-8883-210677683afd" />

BMS Frontend: <img width="1341" height="806" alt="{1EE3DDAC-29B2-4BAC-B923-AB9F0D0CFEAA}" src="https://github.com/user-attachments/assets/8bec7de5-a261-44a7-8058-092f302ef204" />

Dual Buck Converter: <img width="1072" height="709" alt="{ABAC095D-5F63-4ABF-9F45-E9AFDE819EA1}" src="https://github.com/user-attachments/assets/700a6a70-0e28-41be-9b7a-2d5050d208aa" />

Ribbon Cable Connector to the Main Flight Controller: <img width="1092" height="717" alt="{28660C4A-EDFF-454F-AC33-40041DD38D10}" src="https://github.com/user-attachments/assets/eeb0457f-f901-4b24-b0a5-3e8a9145a1a6" />

USB Power: <img width="1133" height="748" alt="{15533186-4DB6-471F-81C5-5AA45E17D572}" src="https://github.com/user-attachments/assets/04b82325-a8c4-41e3-bbfd-5689e2fce1aa" />

PCB View Front Side: <img width="791" height="648" alt="{26CF4550-2026-4056-A79E-0FD538C095F3}" src="https://github.com/user-attachments/assets/1599a866-6a32-4888-9d20-b298df4d04c2" />

PCB View Back Side: <img width="746" height="606" alt="{2FE8043B-3F82-4424-9F34-492FAC51A5C5}" src="https://github.com/user-attachments/assets/8906f228-9517-4b08-87bf-40ac1f85a765" />
