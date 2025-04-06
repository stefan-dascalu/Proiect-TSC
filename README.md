Dascalu Stefan-Nicolae 331 CA
# Proiect-TSC

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

