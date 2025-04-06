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
<table>
  <tr>
    <th style="min-width: 300px;">Component</th>
    <th style="min-width: 250px;">Datasheet</th>
    <th style="min-width: 250px;">Purchase Link</th>
  </tr>
  <tr>
    <td>ADAFRUIT_LEDCHIP-LED0603</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>SJ</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>ESP32_WROVER_EAGLE-LTSPICE_CC0402</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>ESP32_WROVER_EAGLE-LTSPICE_RR0402</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>EAGLE-LTSPICE_CC0402</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>112A-TAAR-R03_ATTEND</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>RCL_CPOL-EUCT3528</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>BUTTON_CUSYOMV1</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>DS3231SN#</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>ESP32-C6-WROOM-1-N8</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>ESP32C6_VARISTORCN1812</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>ESP32_WROVER_AVX---SD0805S020S1R0_AVX_SD0805S020S1R0_0_0</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>CPH3225A</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>MAX17048G+T10</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>MBR0530</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>PGB1010603MR</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>QWIIC_RIGHT_ANGLE (QWIIC_CONNECTORJS-1MM)</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>SAMACSYS_PARTS_USB4110-GF-A</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>USBLC6-2SC6Y</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>W25Q512JVEIQ</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
  <tr>
    <td>XC6220A331MR-G</td>
    <td><a href="#">Click here</a></td>
    <td><a href="#">Click here</a></td>
  </tr>
</table>


