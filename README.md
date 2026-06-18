# DC-Motor-Speed-Controller
A PWM speed controller made for the 775 DC Motor, but can be used with other motors as well. 

I made this as Version 2 of my motor controller for my V8 Engine project, as that board failed to work entirely because of bad design.

# Bill of Materials (BOM)

| **Item Name/Purpose** | **Product Number** | **URL** | **Price** | **Quantity** | **Designator** | **Note** |
| --------------------- | ------------------ | ------- | --------: | -----------: | -------------- | -------- |
| PCB | | https://jlcpcb.com/ | $3.50 | 5 | | |
| P Channel MOSFET | SI2323CDS-T1-BE3 | https://www.digikey.com/en/products/detail/vishay-siliconix/SI2323CDS-T1-BE3/16397482 | $1.21 | 1 | Q4 | |
| Zener Diode | MMSZ5V6T1G | https://www.digikey.ca/en/products/detail/onsemi/MMSZ5V6T1G/1749053 | $0.17 | 1 | D1 | |
| NPN Transistor | MMBT2222A-TP | https://www.digikey.ca/en/products/detail/mcc-micro-commercial-components/MMBT2222A-TP/717279 | $0.24 | 2 | Q3, Q6 | |
| 6A 2920 PTC Fuse | 2920L600/16MR | https://www.digikey.ca/en/products/detail/littelfuse-inc/2920L600-16MR/14320022 | $2.20 | 2 | F1 | |
| Flywheeling Diode | MBR2045CT | https://www.digikey.ca/en/products/detail/taiwan-semiconductor-corporation/MBR2045CT/7357796 | $1.72 | 1 | D3 | |
| N Channel MOSFET | IRF3205STRLPBF | https://www.digikey.ca/en/products/detail/infineon-technologies/IRF3205STRLPBF/856540 | $3.00 | 1 | Q5 | |
| Diode | 1N4148W-13-F | https://www.digikey.ca/en/products/detail/diodes-incorporated/1N4148W-13-F/1933928 | $0.36 | 2 | D5, D6 | |
| 0.01uF 0603 Capacitor | 06035C103MAZ2A | https://www.digikey.ca/en/products/detail/kyocera-avx/06035C103MAZ2A/11250083 | $0.12 | 1 | C2 | |
| 0.1uF 0704 C0G/NP0 Capacitor | GRMJN65C1H104JE01D | https://www.digikey.ca/en/products/detail/murata-electronics/GRMJN65C1H104JE01D/19115560 | $0.37 | 1 | C1 | |
| 555 Timer | LMC555 | https://www.digikey.ca/en/products/detail/texas-instruments/LMC555CMX-NOPB/334874 | $1.15 | 1 | U1 | |
| 10k 0603 Resistor | RC0603FR-0710KL | https://www.digikey.ca/en/products/detail/yageo/RC0603FR-0710KL/726880 | $0.25 | 10 | R1, R5, R6, R8, R11 | Cheaper to get 10 resistors than only 5 |
| 4.7K 0603 Resistor | RMCF0603FT4K70 | https://www.digikey.ca/en/products/detail/stackpole-electronics-inc/RMCF0603FT4K70/1760998 | $0.10 | 1 | R2 | |
| 1K 0603 Resistor | RMCF0603FT1K00 | https://www.digikey.ca/en/products/detail/stackpole-electronics-inc/RMCF0603FT1K00/1761077 | $0.21 | 10 | R3, R4, R7, R9, R10 | Cheaper to get 10 resistors than only 5 |


#### <ins>Totals (not including taxes or shipping)</ins>

**Total (CAD):** $14.60

**Total (USD):** $10.36

### Images
Schematic
<img width="2025" height="1234" alt="image" src="https://github.com/user-attachments/assets/b4dad5b0-0be9-47f4-9a93-75fb06731581" />

PCB
<img width="853" height="1031" alt="image" src="https://github.com/user-attachments/assets/f80a14df-a59f-4644-93f2-8985402ab49f" />


<img width="543" height="737" alt="image" src="https://github.com/user-attachments/assets/a3e34517-1d1d-4c0f-ac05-9107e7f78e08" />
