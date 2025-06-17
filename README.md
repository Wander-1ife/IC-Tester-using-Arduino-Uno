# 🔌 IC Tester using Arduino Uno

## 🧠 Project Overview

This project is designed to **test digital logic ICs** (Integrated Circuits) like:
- AND (7408)
- NAND (7400)
- OR (7432)
- XOR (7486)
- XNOR (7466)

The goal is to verify if these ICs are functioning correctly by checking their **truth tables** using an **Arduino Uno**, LEDs, and an LCD display. The Arduino is programmed to apply all possible logic inputs and observe the outputs for validation.

---

> **Software Used:** Arduino IDE

---

## 🛠️ Working Principle

- The Arduino applies logic inputs to the IC and reads the outputs.
- Based on the results, it identifies the logic gate type and displays the gate name and IC number on the LCD.
- Truth table outputs are indicated using **red LEDs**.
- If the inserted IC is valid and working, the **green LED turns off**.
- If no IC or an unsupported IC is inserted, the green LED remains **on**, and an error is displayed on the LCD.
