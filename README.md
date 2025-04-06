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
| Component                                               | Datasheet                                                | Purchase Link                                 |
|---------------------------------------------------------|----------------------------------------------------------|-----------------------------------------------|
| ADAFRUIT_LEDCHIP-LED0603                                  | [Datasheet](https://www.adafruit.com/product/XYZ)        | [Mouser](https://www.mouser.com/adafruit-ledchip) |
| SJ (SMD solder JUMPER)                                    | N/A                                                      | [Mouser](https://www.mouser.com/search/sj-jumper)   |
| ESP32_WROVER_EAGLE-LTSPICE_CC0402 (0.1uF/50V Capacitor)    | [Datasheet](https://example.com/datasheet_cap)           | [Comet](https://www.comet.com/product/ESP32_cap)      |
| ESP32_WROVER_EAGLE-LTSPICE_RR0402 (0.47 Resistor)           | [Datasheet](https://example.com/datasheet_res)           | [Mouser](https://www.mouser.com/search/esp32_resistor)|
