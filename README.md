# Solar & AC Powered Torchlight 

A multi-source powered torchlight circuit designed in KiCad.
Supports three power inputs: solar cell, AC mains, and battery.

## Features
- Three power source inputs (Solar, AC, Battery)
- SPDT switch for power source selection
- AC to DC rectification using 1N4007 diodes
- Smoothing capacitor for stable DC output
- 8mm main LED torch light
- 3mm indicator LED
- Current limiting resistors for LED protection

## Hardware Components
- Battery cell (BT1)
- Solar cell (SC1)
- AC input
- 1N4007 Diodes x4 (D1, D3, D4, D5)
- SPDT Switch (SW1)
- 8mm LED (D7) — main torch
- 3mm LED (D6) — power indicator
- Smoothing Capacitor C1 (1D4J/4DDV)
- Resistors: R1 (1K), R2 (1K), R3 (22Ω), R4 (5.1Ω)

## How It Works
AC mains or solar input is rectified using 1N4007 diodes
and smoothed by capacitor C1. The SPDT switch selects 
between power sources. Current flows through limiting 
resistors to the main 8mm LED torch and 3mm indicator LED.
The battery cell provides backup power when other sources
are unavailable.

## Tools Used
- KiCad (schematic design & PCB layout)

## Project Files
- Schematic (.kicad_sch)
- PCB Layout (.kicad_pcb)

## Designer
Ezekiel Ekwam-Bentsil Dadze
Electrical Engineering Student | KNUST, Ghana
