# 555-Touch-Alarm-Kicad
555 Timer based Touch Alarm PCB design created in Kicad 8.0

## 555 Timer Touch Alarm PCB Design
This repository contains the KiCad design files for a Touch Sensitive Alarm Circuit based on the versatile NE555P Timer IC. The circuit is designed to trigger an audible alarm (buzzer) when a human touch is detected on the sensing pad.

## 🛠 Features
* Mode of Operation: Monostable multivibrator.
* Trigger Mechanism: High-sensitivity touch detection via Pin 2.
* Output: Driven by Pin 3 with a 100µF coupling capacitor for DC blocking.
* Power Management: Includes PWR_FLAG for error-free Electrical Rules Check (ERC) in KiCad.
  

## 📁 Project Structure

* / : Contains .kicad_pro, .kicad_sch, and .kicad_pcb files.

## ⚡ Technical Specifications

| Component | Value/Part |
| IC1 | NE555P Precision Timer |
| C1 | 1nF (Trigger filtering) |
| C2 | 100µF (Buzzer coupling) |
| R1 | 1k Ohm |
| Input | 9V DC Battery Connector |


## 📸 Screenshots
<img width="1364" height="709" alt="image" src="https://github.com/user-attachments/assets/460ef7db-3ffe-4f91-b02d-18278b0caf3f" />
<img width="1365" height="717" alt="image" src="https://github.com/user-attachments/assets/c84dbf74-4f59-4faa-b87e-da21f0301f95" />


------------------------------
Credits: Tutorial inspired by the KARTIS YouTube Channel.
------------------------------

