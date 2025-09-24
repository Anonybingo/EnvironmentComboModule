# Group 7 - Environment Combo Module

## Project Description
Plug-in PCB module for ESP32 monitoring pressure/temp (BMP280) and light (LDR). Yellow LED (D1) lights if low light (LDR >2000 ADC); red LED (D2) lights if high pressure (>1013 hPa). Connects via 2x19 female headers.

## Components (LCSC IDs)
- BMP280: C83291
- LDR: C125631
- Yellow LED: C88602 (w/ 220Ω C172985)
- Red LED: C87271 (w/ 220Ω C172985)
- 10kΩ (LDR): C21190
- 0.1µF (BMP280): C14663
- Female Headers (2x1x19): C124395

## ESP32 Pin Mapping (Via Headers)
- BMP280: VCC=FH1-1 (3V), GND=FH1-19, SDA=FH2-4 (D4/GPIO21), SCL=FH2-3 (D5/GPIO22)
- LDR: Analog=FH1-5 (A1/GPIO34)
- Yellow LED: D1=FH1-16 (GPIO2)
- Red LED: D2=FH1-18 (GPIO4)
