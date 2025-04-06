Dascalu Stefan-Nicolae 331 CA
# Proiect-TSC
## Implementare:

- **Implementarea Schemei Electrice:**
  - Am implementat schema electrica exact conform modelului primit.
  - Am efectuat o **verificare a regulilor electrice (ERC)**; desi am intampinat cateva avertismente, le-am revizuit si considerat necritice.

- **Designul PCB:**
  - Dupa finalizarea schemei, am incarcat designul in mediul PCB.
  - Toate componentele au fost amplasate pe **TOP layer** conform ghidurilor de layout.
  - Pentru a asigura **proper grounding** si **signal integrity**, am creat un **GND plane** atat pe TOP layer, cat si pe BOTTOM layer.
  - Am verificat toate constrangerile de design, iar rutarea a fost finalizata cu o rata de succes de 99,6%.
  - In timpul designului PCB, am intampinat si rezolvat erori de tip "airwire unrouted".

- **Fisiere de Productie:**
  - Am generat fisierele **Gerber**, **Pick and Place** si **BOM**.

- **Modelul 3D:**
  - Modelul 3D al dispozitivului nu a fost implementat.

## BOM:
| Component                                               | Datasheet | Purchase Link |
|---------------------------------------------------------|-----------|---------------|
| ADAFRUIT_LEDCHIP-LED0603                                  |           |               |
| SJ                                                      |           |               |
| ESP32_WROVER_EAGLE-LTSPICE_CC0402                         |           |               |
| ESP32_WROVER_EAGLE-LTSPICE_RR0402                         |           |               |
| EAGLE-LTSPICE_CC0402                                      |           |               |
| 112A-TAAR-R03_ATTEND                                     |           |               |
| RCL_CPOL-EUCT3528                                       |           |               |
| BUTTON_CUSYOMV1                                         |           |               |
| DS3231SN#                                              |           |               |
| ESP32-C6-WROOM-1-N8                                     |           |               |
| ESP32C6_VARISTORCN1812                                  |           |               |
| ESP32_WROVER_AVX---SD0805S020S1R0_AVX_SD0805S020S1R0_0_0  |           |               |
| CPH3225A                                               |           |               |
| MAX17048G+T10                                          |           |               |
| MBR0530                                               |           |               |
| PGB1010603MR                                           |           |               |
| QWIIC_RIGHT_ANGLE (QWIIC_CONNECTORJS-1MM)               |           |               |
| SAMACSYS_PARTS_USB4110-GF-A                              |           |               |
| USBLC6-2SC6Y                                           |           |               |
| W25Q512JVEIQ                                           |           |               |
| XC6220A331MR-G                                         |           |               |

