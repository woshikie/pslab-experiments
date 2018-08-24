
  

# Finding the Forward-Voltage of an LED

## Learning Objective
 1.   Measure voltage using the multimeter instrument.
 2.  Change source voltage using the power source instrument.
 3.  Identify the positive and negative pin of an LED
 4.   Light up a light emitting diode (LED).
 5.   Find out the forward-voltage of an LED.

## Required Components
![Picture of Components](https://i.imgur.com/qAMdBFo.jpg)

| | Component | Quantity |
|:-:| ------------ |:--------:|
| 1 | PSLab Device | 1 |
| 2 | USB C/Micro USB On-The-Go Cable| 1 |
| 3 | Micro USB Cable | 1 |
| 4 | 220Ω Resistor | 1 |
| 5 | Light Emitting Diode (Any Colour)| 1 |
| 6 | Breadboard  | 1 |

## Required Instruments
- Multimeter
- Power Source

## Schematics
### Circuit Diagram
![Circuit Diagram](https://i.imgur.com/A3IptFj.jpg)

### Breadboard Diagram
![Breadboard Diagram](https://i.imgur.com/Rxkndei.png)

## Step-By-Step Tutorial
| Step | Instruction | Picture Instruction |
|:--:|--|:--:|
| 1 | Identify the positive and negative leg of the LED | ![Step X](https://i.imgur.com/pi9dHDT.png) |
| 2 | Connect the LED to the breadboard as shown. | ![Step X](https://i.imgur.com/21d3NKW.png) |
| 3 | Connect the 220Ω resistor as shown | ![Step X](https://i.imgur.com/Y5ofE7b.png) |
| 4 | Connect Jumper cables to the breadboard as shown | ![Step X](https://i.imgur.com/omNAAXa.png) |
| 5 | Connect Jumper cables to the PSLab as shown | ![Step X](https://i.imgur.com/ukTM3bM.png) |
| 6 | Open Up PSLab App| ![Step X](https://i.imgur.com/keDIxEO.png) |
| 7 | Scroll down to Power Source, tap to enter | ![Step X](https://i.imgur.com/t9PI55D.png) |
| 8 | Turn up PV1 from -5.00V to 5.00V using the button or the knob | ![Step X](https://i.imgur.com/jogNVHa.png) |
| 9 | Tap on back and scroll up to Multimeter, tap to enter | ![Step X](https://i.imgur.com/l9i5NEk.png) |
| 10 | Spin the knob to CH1| ![Step X](https://i.imgur.com/uuKp7BG.png) |
| 11 | Tap READ to read the forward voltage of the LED| ![Step X](https://i.imgur.com/gSWwSAZ.png) |

## Expected Result
![Expected_Result.gif](https://i.imgur.com/A1vKx4Y.png)
### What to observe
-   LED should light up during step 8.
-   The forward voltage should be around 1.7V.


## Troubleshoot
<div id="troubleshoot">

### Common Problems
-   [LED does not light up](#troubleshoot_1)
-   [Forward Voltage is not as expected](#troubleshoot_2)

</div>
<div id="troubleshoot_1">

#### LED Does not light up
1. Make sure the the positive leg is connected to PV1 and the negative leg is connected to both CH1 and one end of the resistor.
2. Make sure the other end of the resistor is connected to GND.
3. Make sure the PSLab is connected to the Android Phone
######  [Back to troubleshoot](#troubleshoot)
</div>
<div id="troubleshoot_2">

#### Forward Voltage is not as expected
1. Make sure that CH1 is connected to both the negative leg of the LED and one end of the resistor
2. Make sure that the other end of the resistor is connect to GND
######  [Back to troubleshoot](#troubleshoot)
</div>
