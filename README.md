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
| Component                                               | Link             |
|---------------------------------------------------------|------------------|
| ADAFRUIT_LEDCHIP-LED0603                                  | [Click here]()   |
| SJ                                                      | [Click here]()   |
| ESP32_WROVER_EAGLE-LTSPICE_CC0402                         | [Click here]()   |
| ESP32_WROVER_EAGLE-LTSPICE_RR0402                         | [Click here]()   |
| EAGLE-LTSPICE_CC0402                                      | [Click here]()   |
| 112A-TAAR-R03_ATTEND                                     | [Click here]()   |
| RCL_CPOL-EUCT3528                                       | [Click here]()   |
| BUTTON_CUSYOMV1                                         | [Click here]()   |
| DS3231SN#                                              | [Click here]()   |
| ESP32-C6-WROOM-1-N8                                     | [Click here]()   |
| ESP32C6_VARISTORCN1812                                  | [Click here]()   |
| ESP32_WROVER_AVX---SD0805S020S1R0_AVX_SD0805S020S1R0_0_0  | [Click here]()   |
| CPH3225A                                               | [Click here]()   |
| MAX17048G+T10                                          | [Click here]()   |
| MBR0530                                               | [Click here]()   |
| PGB1010603MR                                           | [Click here]()   |
| QWIIC_RIGHT_ANGLE (QWIIC_CONNECTORJS-1MM)               | [Click here]()   |
| SAMACSYS_PARTS_USB4110-GF-A                              | [Click here]()   |
| USBLC6-2SC6Y                                           | [Click here]()   |
| W25Q512JVEIQ                                           | [Click here]()   |
| XC6220A331MR-G                                         | [Click here]()   |



