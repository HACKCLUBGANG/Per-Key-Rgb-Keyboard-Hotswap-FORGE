# Per-Key-Led-Keyboard-Hotswap-FORGE

Source Link Onshape -  https://cad.onshape.com/documents/a3706bff300e93766397b60f/w/be6071b581e0c225a171638b/e/79bd546bad59e5e5cdb5a4cd?renderMode=0&uiState=6af5ff969d34894ea51fd6a4
---------------------------------------
Render
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/123c2b3e-eac4-48fb-a2dd-afef2c7c913b" />
Onshape
<img width="1064" height="549" alt="image" src="https://github.com/user-attachments/assets/b15656f8-b5b0-4ac5-99cc-47476d6dfa89" />

This is the Per-Key-Led-Keyboard-Hotswap which says in its name that it has per key ice blue led
It also has kailh hotswap attachment so u can also switch keys without worrying about opening the keyboard
Each key has a south facing smd ice blue led under the switch.
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/7d8acd5a-e994-424d-9756-1e7454170751" />

Heres A Render Of The Whole Build

https://github.com/user-attachments/assets/ba00d72b-443f-43d3-ab56-3a87e9c14a67

# Features 
- Per Key Rgb Customizable
- Hotswappable
- Compact  60%  10.1cm X 29.2 cm
- Usb C Powered
- 3d Printed Case
- Rp Pi Pico Fitted Into A Compact Keyboard
- 2 Layer Pcb
- Custom Made Led Circuitry
 Cool Looking :>

# Schematics 
Files in /PcbandSchem

<img width="965" height="404" alt="image" src="https://github.com/user-attachments/assets/837b016a-5d6b-4de2-ae50-0404e83b98fd" />
<img width="404" height="328" alt="image" src="https://github.com/user-attachments/assets/306b7ed5-6ca3-48ef-976e-88693d8ab7a3" />
<img width="258" height="401" alt="image" src="https://github.com/user-attachments/assets/2819442a-401a-4da7-9c5e-eec5b5dd7ae3" />
<img width="718" height="758" alt="image" src="https://github.com/user-attachments/assets/30442711-04e2-4a3a-8e7c-7c19159b3275" />

#  Printed Circuit Board PCB
Files in /PcbandSchem

Front  Copper 
<img width="1263" height="431" alt="image" src="https://github.com/user-attachments/assets/206bdc17-92d8-4a80-a05a-bf3142ae4fef" />
Back Copper
<img width="1265" height="432" alt="image" src="https://github.com/user-attachments/assets/39bb0acc-39a2-47f8-8896-bf9756fdb1d2" />
Both Layers
<img width="1267" height="436" alt="image" src="https://github.com/user-attachments/assets/96a11863-6f81-4a63-95ee-19ff5f6b64a2" />

# Cad
Files in /CAD
Bottom   Plate
<img width="1444" height="674" alt="image" src="https://github.com/user-attachments/assets/2c94e45b-949a-4cf4-9d88-dd55e143aa0c" />
Top Plate
<img width="1243" height="541" alt="image" src="https://github.com/user-attachments/assets/b3d6a979-a677-49fb-9596-afe2942cb91b" />
Both
<img width="1231" height="691" alt="image" src="https://github.com/user-attachments/assets/8365d5c3-0bac-4b84-9de8-3a8462a8df9f" />


# BOM
| # | Component | Part Number / Model | Qty Needed | Qty Purchased | Price (INR) | Product Link |
|---:|---|---|---:|---:|---:|---|
| 1 | Custom PCB + Shipping | JLCPCB FR-4 | 1 | 1 | ~2665 | [JLCPCB](https://jlcpcb.com/) |
| 2 | Microcontroller | Raspberry Pi Pico (RP2040) | 1 | 1 | 422 | [Robu](https://robu.in/) |
| 3 | USB-C Female Connector | Hroparts TYPE-C-31-M-13A (R250302) | 1 | 1 | 27 | [Robu](https://robu.in/product/type-c-31-m-13a-hroparts-5a-1-recessed-mount-16p-female-30%e2%84%8380-type-c-smd-usb-connectors-rohs/) |
| 4 | USB-A to Micro-USB Cable | 80cm | 1 | 1 | 59 | [Robu](https://robu.in/) |
| 5 | Micro-USB Male Connector | YT2153Y | 1 | 1 | 79 | [Robu](https://robu.in/) |
| 6 | LED Driver IC | TLC5948APWPR | 4 | 4 | 1144 | [Robu](https://robu.in/) |
| 7 | Ice-Blue LEDs | XINGLIGHT XL-2835BGWC-05 | 61 | 85 | 102 | [Robu](https://robu.in/) |
| 8 | Switching Diodes | Slkor 1N4148W SOD-123 | 61 | 70 | 72.80 | [Robu](https://robu.in/) |
| 9 | Ceramic Capacitors | 100nF, 1206, 50V | 4 | 4 | 32 | [Robu](https://robu.in/) |
| 10 | Bulk Capacitor | Taiyo Yuden EMK325ABJ107MM-T, 100µF 16V | 1 | 1 | 292.19* | [Taiyo Yuden](https://www.yuden.co.jp/) |
| 11 | Resistors | 10kΩ, 1206 | 4 | 12 | 10.56 | [Robu](https://robu.in/) |
| 12 | Resistors | 5.1kΩ, 1206 | 2 | 48 | 10.08 | [Robu](https://robu.in/) |
| 13 | Resistors | Yageo AC1206FR-07200RL, 200Ω | 0 required for IREF | 25 | 10.25 | [Robu](https://robu.in/) |
| 14 | Mechanical Switches | Gateron G Pro 3.0 Yellow | 61 | 70 (7 packs) | 1253.70 | [Meckeys](https://meckeys.com/) |
| 15 | Hot-Swap Sockets | Kailh MX Hot-Swap Socket, White | 61 | 7 listings | 504 | [Meckeys](https://meckeys.com/) |
| 16 | Stabilizers | DesignerStudio Plate Stabilizers | 4 × 2U + 1 × 6.25U | 1 kit | 550 | [Keyora](https://keyora.store/products/designerstudio-100-plate-mount-stabilizers-adaptive-wire-pom) |
| 17 | Keycaps | Selected keycap set | 1 set | 1 set | 799 | — |

## Notes
- Robu has a minimum order value of ₹10 per item.
- PCB + shipping is approximately $29 (₹2,665).
