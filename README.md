# J-Letter Animated LED Sequencer V2.0

![photo_2025-09-18_19-12-50](https://github.com/user-attachments/assets/b5aa1a4c-1264-46a3-9ae8-ce1652db7f47)


A custom-designed PCB that creates a visually appealing animated light sequence in the shape of the letter 'J'. This project documents the complete journey from initial concept and schematic capture to a final, manufactured, and assembled electronic device, built on my path to becoming an embedded engineer.

---

## ✨ Sponsorship

This project was brought to life thanks to the generous sponsorship of PCBway.
As someone who works in the industrial sector at a car service center, I have personally seen and handled thousands of PCBs—from Engine Control Modules and transmission units to airbag and ABS controllers in high-end vehicles like Mercedes. I can honestly say that the manufacturing quality of the board I received from PCBway is in a class of its own. The finish, the precision, and the overall feel are superior to many of the automotive-grade electronics I see every day. This board isn't just a prototype; it's a testament to their commitment to exceptional quality.
<a href="https://www.pcbway.com/" target="_blank"><img src="https://www.pcbway.com/template/shared/images/pcbway-logo-300.png" width="300"></a>
Their support in providing high-quality, professional PCBs was essential to the success of this project.

---

## 📖 Table of Contents

- [About The Project](#about-the-project)
- [Features](#features)
- [Hardware & Bill of Materials](#hardware--bill-of-materials)
- [How to Build](#how-to-build)
- [Gallery](#gallery)
- [👤 Author](#-author)
- [License](#license)

---

## 📝 About The Project

This project is a classic electronics learning exercise brought to life on a custom-designed Printed Circuit Board (PCB). The circuit is driven by a timeless NE555 timer, configured in astable mode to generate a stable clock pulse. This clock signal is then fed into a pair of daisy-chained CD4017 decade counters, which sequentially activate 20 individual LEDs to trace the shape of the letter 'J'.

The board is a two-layer design created in CircuitMaker, meticulously routed to ensure both functionality and a clean aesthetic.

![photo_2025-09-18_19-12-54](https://github.com/user-attachments/assets/dab561d5-59f5-468e-b6c1-2d97c29963ff)


---

## 🚀 Features

- Custom PCB designed in CircuitMaker.
- 20-LED animated sequence in the shape of a 'J'.
- Classic NE555 timer for clock pulse generation.
- Daisy-chained CD4017 decade counters for sequential logic.
- Two-layer design with full ground pours for stability and noise reduction.
- Custom "BAVREX" logo and branding on the bottom silkscreen.
- M3 mounting holes for easy integration into an enclosure or stand.

---

## 🛠️ Hardware & Bill of Materials

To build this project, you will need the following components:

| Reference | Component          | Quantity |
|-----------|--------------------|----------|
| IC1       | NE555 Timer        | 1        |
| C1, C4    | CD4017BE Decade Co | 2        |
| LED1-LED20| 5mm Blue LEDs      | 20       |
| R1-R22    | Resistors(Assorted)| 22       |
| C2, C3, C5, C6 | Capacitors (Assorted)| 4        |
| CN1       | 2-Pin Screw Terminal| 1        |
| SW1       | SPDT Slide Switch  | 1        |

*(Note: Please refer to the schematic for exact resistor and capacitor values.)*


<img width="1085" height="634" alt="Screenshot 2025-09-18 192449" src="https://github.com/user-attachments/assets/3ad6c9d8-1f1a-4a82-895f-83c21f211990" />

link to my circuitMaker

https://workspace.circuitmaker.com/Projects/Details/bavinhamaali/J-letter-sequence


---

## 🔧 How to Build

1.  **Get the Design Files:** Clone this repository or download the Gerber files from the `/Gerber` directory which i provided the link of the circuit maker you can fork it and do customazation of your choice.
2.  **Order the PCBs:** The PCBs for this project were professionally manufactured by **PCBway**. You can upload the provided Gerber files directly to their website to order your own boards. Their online Gerber viewer is also a great tool to double-check the files before paying.
3.  **Solder the Components:** Once your boards arrive, gather the components listed in the Bill of Materials and begin soldering. I recommend starting with the smallest components like resistors first and finishing with the larger ones like the IC sockets and capacitors.

---

## 🖼️ Gallery

Here are some images from the build process.

**The custom BAVREX branding on the bottom of the board:**

![photo_2025-09-18_19-12-52](https://github.com/user-attachments/assets/12ad0b9b-16c9-485e-8760-5cf17413b130)


**The moment of truth - it works!**

![photo_2025-09-18_19-12-50](https://github.com/user-attachments/assets/38357f40-3c03-4f61-b406-ec06308de5c6)


---

## 👤 Author

**Bavin Kawa. (BAVREX)**


- This project is a milestone on my journey to becoming a Full Stack Embedded Engineer, Inshallah.

---

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for details.
