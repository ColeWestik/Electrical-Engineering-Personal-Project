# Parallel LED Circuit and Forward Voltage
This experiment explores **forward voltage**, **frequency**, and the functionality of **parallel circuits**.

## Setup
* 4 small LEDS rated at 20 mA
* 9V Battery
* 4 x 1000 Ω resistors
* Multimeter

## The Circuit
![Parallel-Circuit](https://github.com/user-attachments/assets/1f92e7cd-8548-4d49-bce9-434f5014572d)
<img width="736" height="336" alt="image" src="https://github.com/user-attachments/assets/ce25fedc-557d-4670-989f-73ed31cced24" />

## Forward Voltage
**Forward voltage** is the minimum voltage required to begin the flow of current.

* It can be determined by measuring the voltage drop over an LED.

--- 

#### Higher-frequency light (blue, green) requires a higher forward voltage
![GreenLED](https://github.com/user-attachments/assets/da359e6f-9024-4d2a-9afc-1f5160e758df)

#### Lower-frequency light (red, yellow) requires a lower forward voltage
![YellowLED](https://github.com/user-attachments/assets/1448bc86-52fc-4c75-b27c-1d8c9f4d04dc)

## Measured Forward Voltages by Color
* Red ≈ 1.8V
* Yellow ≈ 2V
* Green ≈ 2.5V
* Blue ≈ 2.8V
  
<img width="600" height="371" alt="Forward Voltage by Color" src="https://github.com/user-attachments/assets/437ac982-f67c-4861-b200-5c3477f35673" />

## Frequency and Forward Voltage Correlation
* With the use of average frequencies based on color, a correlation between the frequency of the color and the forward voltage of the LED can be made.
* Red ≈ 460 THz
* Yellow ≈ 510 THz
* Green ≈ 600 THz
* Blue ≈ 650 THz
  
<img width="600" height="371" alt="Forward Voltage by Frequency" src="https://github.com/user-attachments/assets/38c8121e-2cbf-44c4-afe7-3bf5a251eb04" />

* Forward Voltage is directly proportional to the frequency of light.
* 
* Higher-frequency light corresponds to higher-energy photons. 
A larger forward voltage is needed to emit these higher-energy photons.

* Lower-frequency light corresponds to lower-energy photons. 
A smaller forward voltage is needed to emit these lower-energy photons.

## Amperage
In **Parallel Circuits**, each branch recieves voltage equal to the power source. Since the power source is a 9V battery, each branch recieves 9V minus the forward voltage of the LED.

Using the voltage of each branch and resistance of each branch (1000 Ω), the current can be determined using **Ohms Law (I = V/R).**

#### Measured Current of each branch
* Red = 7.2 mA
* Yellow = 7 mA
* Green = 6.5 mA
* Blue = 6.2 mA

Each LED is rated at 20 mA, so all the measured currents are within a safe range.



## Conclusion
This experiment demonstrated that as the LED's color frequency increased, the forward voltage increased. It also demostrated that in parallel wiring, each branch recieves the same source voltage with differing current based on voltage drops and resistance.


