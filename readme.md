# Geeky - RP2040 Microcontroller Project

**Geeky** is an RP2040-based microcontroller board. I created this project to dive deeper into microcontroller design. Because of that, the board is slightly larger than typical designs.  

I wanted to solder everything myself, which made assembling the MCU quite a challenge—but also a great learning experience.  

Below you can find the 3D model, schematic, board layout, and the bill of materials (BOM).

---

## Design Overview

- **Board Type:** RP2040 Microcontroller
- **Focus:** Learning low-level MCU operation and manual soldering
- **Size:** Slightly larger than standard microcontroller boards to accommodate manual assembly

### 3D Model, Schematic, and Layout

<img width="590" height="489" alt="Zrzut ekranu z 2026-02-04 08-45-02" src="https://github.com/user-attachments/assets/ac5d1274-194d-46ff-b6bf-8f9d2ba7e388" />
<img width="622" height="696" alt="Zrzut ekranu z 2026-02-04 08-44-50" src="https://github.com/user-attachments/assets/a4c3abd6-d4ed-4369-a285-67a40590a6cc" />

<img width="2000" height="1294" alt="image" src="https://github.com/user-attachments/assets/e08b2ca5-00ec-4222-b51c-df629f70fb45" />


---

## Bill of Materials (BOM)

| Designator         | Footprint                               | Quantity | Item Name                               | Price (USD) | All Cost (USD) |
|-------------------|----------------------------------------|---------|----------------------------------------|------------|----------------|
| C1, C2, C3, C4    | 805                                    | 4       | 1uF Capacitor                           | 1.43       | 28.80          |
| C5, C6, C7, C8    | 805                                    | 8       | 100nF Capacitor                          | 1.63       | 28.80          |
| C13, C14          | 805                                    | 2       | 18pF Capacitor                            | 2.93       | 28.80          |
| C15, C16, C17     | 805                                    | 3       | 10uF Capacitor                            | 1.42       | 28.80          |
| J1                | USB_C_Receptacle_HRO_TYPE-C-31-M-12   | 1       | USB-C Receptacle                          | 1.74       | 28.80          |
| J2                | PinHeader_2x03_P2.54mm_Vertical       | 1       | DEBUG Header                              | 2.08       | 28.80          |
| J3, J4            | PinHeader_1x20_P2.54mm_Vertical       | 2       | 1x20 Connector                            | 1.44       | 28.80          |
| R1, R2, R3, R4, R5| 805                                    | 5       | Resistor (27Ω SMD, best price)           | 3.39       | 28.80          |
| SW1               | SW_Push_SPST_NO_Alps_SKRK             | 1       | Push Button Switch                        | 0.46       | 28.80          |
| SW2               | SW_Push_SPST_NO_Alps_SKRK             | 1       | BOOTSEL Button                            | 0          | 28.80          |
| U1                | QFN-56-1EP_7x7mm_P0.4mm_EP3.2x3.2mm   | 1       | RP2040 Microcontroller                     | 4.28       | 28.80          |
| U2                | SOT-223-3_TabPin2                      | 1       | AMS1117-3.3 Voltage Regulator             | 0.70       | 28.80          |
| U3                | SOIC-8_5.3x5.3mm_P1.27mm               | 1       | W25Q128JVS Flash Memory                    | 5.49       | 28.80          |
| Y1                | Crystal_SMD_5032-4Pin_5.0x3.2mm       | 1       | 12MHz Crystal                              | 1.81       | 28.80          |

**Total Cost (with shipping): $42.50**

---

This project is a perfect example for anyone looking to get hands-on experience with microcontrollers and manual soldering. The RP2040 opens the door to countless learning possibilities, and building it yourself makes the knowledge stick.





