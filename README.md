# 8 Bit Adder/Subtractor

## Abstract  
This project presents the design and implementation of an **8-bit Arithmetic Logic Unit** using **74LS283 4-bit binary adders** and **74LS86 XOR gates**. The ALU performs **addition and subtraction** on two 8-bit binary numbers, selected through DIP switches, and displays results via LEDs. Subtraction is implemented using the **two’s complement method**, where the B input is inverted through XOR gates and a carry in is introduced.  


## Components Used
- **74LS283** – Two 4-bit full adders (to build 8-bit adder/subtractor).  
- **74LS86** – XOR gates (to invert B input during subtraction).  
- **DIP Switches** – User inputs for binary values.  
- **LEDs** – Result output display.  

---

## Circuit Overview
- **Addition Mode**: `Result = A + B`  
- **Subtraction Mode**: `Result = A + (~B) + 1`  

---

## Schematic & Layout  
  

- **8-bit ALU Schematic**  
<img width="1099" height="721" alt="image" src="https://github.com/user-attachments/assets/256f0179-3e47-4b49-8619-bd37e90a4314" />
 

  

---

## Truth Tables  
### Addition  
<img width="1031" height="357" alt="image" src="https://github.com/user-attachments/assets/a3454c7c-b400-4bed-ace9-416237f42087" />
 

### Subtraction  
<img width="994" height="649" alt="image" src="https://github.com/user-attachments/assets/3aa258b0-f2a2-44da-aec6-b188ce11affd" />

---  
Date: *21/09/2025*  
