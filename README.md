# PCB Design v1.0 

## Description
This project is my first practical hardware work as a first-year Computer Engineering student. I developed it to learn hardware design processes, how to read schematics, and the standards used in PCB production.

---

## Visuals
For reviewers to quickly see the design, the front and back views of the board are shown below:

### PCB Front View
![PCB Front](Images/Front.png)

### PCB Back View
![PCB Back](Images/Back.png)

---

## Technical Details & Tools
Libraries and design rules (DRC) were used during the design process.

* **Design Tool:** Autodesk Eagle v9.6.2
* **Libraries:** * [SparkFun Electronics](https://github.com/sparkfun/SparkFun-Eagle-Libraries) (Connectors, LED, PowerSymbols, Resistors, Sensors, Switches)
    * [Custom Library](Design_Files/Custom_Library/) (Designed for specific componenets Arduiono Nano and LM 35)
* **Design Rules:** To minimize errors in the schematics, checks were performed using the [SparkFun DRU](Design_Files/DRU%20File/) files.

---

## Project Structure
The project folder is organized as follows:

* **[Design_Files](Design_Files):** Source Autodesk EAGLE schematic (.sch) and board (.brd) files.
* **[Gerber](Gerber):** Output files prepared for manufacturing in RS-274X format.
* **[Images](Images):** High-resolution design images.

---

## How to Use
1. `/Design_Files/Schemas` You can open the files in this folder using EAGLE or any compatible CAD software.
2. If you want to manufacture the board, you can directly send the `.zip` file in the `/Gerber` folder to a PCB manufacturer (such as JLCPCB, PCBWay, etc.).

---
**Author:** Burak Eslem Arık
**Contact:** [burakar1912@gmail.com](burakar1912@gmail.com), [Linkedin](https://www.linkedin.com/in/burak-eslem-arik-481045208/)