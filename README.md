# half-life-week-3
MIDI Keyboard PCB Design inspired by Hack Club's guide: an electronic controller that doesn't make sound on its own but sends the data for a computer/synthesizer to generate that audio. Perhaps it can also be programmed to play audio clips?  

FUNCTION:
One's inherent electrical field interacts with the capacitive keys on the pcb and plays a corresponding sound to the key "pressed." Additionally, the switches above the capacitive keys perform the same function though they havae a more physical response to one's touch.

PCB DESIGN:  
<img width="1187" height="798" alt="Screenshot 2026-10-25 221639" src="https://github.com/user-attachments/assets/b0ef7047-032e-4ebc-9917-b15a285c3a22" />

3D PCB MODEL:  
<img width="770" height="675" alt="Screenshot 2026-10-25 221626" src="https://github.com/user-attachments/assets/5dae2e4d-d4d0-4e51-8231-0420cf4ea080" />

## Bill of Materials (BOM)

| Part | Qty | Unit | Total | Vendor |
| :--- | :---: | :---: | :---: | :--- |
| **Custom PCB**<br><sub>connecting all components via electrical signals (?)</sub> | 5 | $0.80 | $4.00 | [JLCPCB](https://jlcpcb.com) |
| **Waveshare ESP32-S3**<br><sub>microcontroller</sub> | 1 | $5.12 | $5.12 | [AliExpress](https://www.aliexpress.com) |
| **switches**<br><sub>interaction</sub> | 10 | $0.10 | $1.00 | [AliExpress](https://www.aliexpress.com) |
| **SK6812 MINI-E Neopixels**<br><sub>glow</sub> | 10 | $0.30 | $3.00 | [AdaFruit](https://www.adafruit.com) |
| **ec11 rotary encoder**<br><sub>interaction</sub> | 1 | $2.14 | $2.14 | [AliExpress](https://www.aliexpress.com) |
| **Tax & shipping**<br><sub>for the whole order</sub> | - | - | $17.42 | - |
| **TOTAL** | - | - | #32.68 | - |
