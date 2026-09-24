# PWM-WITH-LED
Configure an FTM channel in edge-aligned PWM mode to flash an LED at exactly 1 Hz with 50% duty cycle. 
---

## Apparatus Required

| S. No. | Apparatus / Software | Specification |
|:---:|---|---|
| 1 | Microcontroller Development Board | **NXP S32K144 Development Board** |
| 2 | IDE | **S32 Design Studio** |
| 3 | Programming Language | **Embedded C** |
| 4 | SDK | **S32K144 SDK** |
| 5 | LED | On-board LED / External LED |
| 6 | Programmer / Debugger | On-board Debugger / OpenSDA |
| 7 | USB Cable | For programming and power supply |

---
## Procedure

1. Connect the **S32K144 Development Board** to the computer.
2. Open **S32 Design Studio** and create/open the S32K144 project.
3. Configure the required **FTM channel** for **Edge-Aligned PWM mode**.
4. Set the PWM frequency to **1 Hz**.
5. Set the PWM duty cycle to **50%**.
6. Configure the LED pin as the PWM output.
7. Generate the required FTM and GPIO configuration.
8. Build the project and check for errors.
9. Download the program to the **S32K144** board.
10. Run the program and observe the LED.
11. Verify that the LED remains **ON for 0.5 seconds** and **OFF for 0.5 seconds**.
12. Use an oscilloscope or logic analyzer, if available, to verify the **1 Hz frequency and 50% duty cycle**.

---

## OUTPUT


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/69543aef-acbc-46b6-ad67-6517f62b9e8a" />



---

## Result

The **FTM channel was successfully configured in Edge-Aligned PWM mode**. The LED flashed at **1 Hz with a 50% duty cycle**, with approximately **0.5 seconds ON and 0.5 seconds OFF**, and the PWM output was successfully verified.
