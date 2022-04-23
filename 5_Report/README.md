# INTRODUCTION
* Door plays an important role in home security.
* Door Sensor Security System implemented by using atemga328p.
* In This system we use switch to close or open the door.
* We can also use sensors instead of switch.
* Power Supply is given to the circuit i.e 5v.
* Here we use LED as an indicator, whether the door is opened or closed.
* If the switch is closed the LED will blink, else the LED will not blink
 
## OBJECTIVE
* For security purpose, to check whether the door is open or close.

## Approach:
* The first step is to implement a structure for taking the input in the form of voltage. 
* Check whether the switch is open or close.
* If the switch(door) is close the given power supply will pass to atmega and the connected LED will glow.
* If the switch (door) is open the power supply is not get into the atemega there is no blinking od LED.
* Then we can easily find that door is open or close based on LED ,after that we can take actions on that. 

## 4W’s AND 1’H
### WHO:
* Anyone can implement it and use it.

### WHAT:
* Security is most important, in that the door plays an important role so that door security system is very important.

### WHEN:
* At any time when the security is required.

### WHERE:
* We can use it in house, company, bank, mall etc,,.
 
### HOW:
* Place switch or sensor near the door we can implement it.


## SWOT ANALYSIS

### STRENGTH:
* The given system is handy and portable, and thus easily carried.
* The circuitry is not that much complicated and thus can be easily troubleshooted.
* A good security system.

### WEAKNESS:
* This system is only capable to determine whether the door is open or close, and does not determine how many persons are there actually.

### OPPORTUNITIES:
* By usage of CC camera, we can implement high alert security system.

### THREAT:
* Due to component issue system may inactive sometimes. 

# Architecture
![Screenshot (35)](https://user-images.githubusercontent.com/101825270/164878229-0fbbe17c-2713-4578-94db-f75de5eac375.png)



# ATMEGA 328

* ATmega328 is an 8-bit, 28-Pin AVR Microcontroller, manufactured by Microchip, follows RISC Architecture and has a flash-type program memory of 32KB.
Atmega328 is the microcontroller, used in basic Arduino boards i.e Arduino UNO, Arduino Pro Mini and Arduino Nano.
* It has an EEPROM memory of 1KB and its SRAM memory is 2KB.
* It has 8 Pins for ADC operations, which all combine to form PortA ( PA0 – PA7 ).
* It also has 3 built-in Timers, two of them are 8 Bit timers while the third one is 16-Bit Timer.
* You must have heard of Arduino UNO, UNO is based on atmega328 Microcontroller. It’s UNO’s heart.
* It operates ranging from 3.3V to 5.5V but normally we use 5V as a standard.
* Its excellent features include cost-efficiency, low power dissipation, programming lock for security purposes, real timer counter with separate oscillator.

![ATmega328-Pinout-768x571](https://user-images.githubusercontent.com/101825270/164878166-ef090162-62b1-42d5-be79-4c97d5d34d82.png)

## High Level Test Plan

| Test ID | Description | Expected Input |  Expected Output | Actual Output | Type Of Test |
| ------- | ----------- | -------------- | ---------------- | ------------- | ------------ |
| H_01 |  Checking weather the led is blinking or not | 0v |  SUCCESS | SUCCESS  | Requirement based |
| H_02 | Cheking that the LED blinking | 5v | SUCCESS | SUCCESS | Requirement based |
| H_03  | By inserted input  | code itself | PASS |  SUCCESS | Technical |


## Low Level Test Plan

| Test ID | Description | Expected Input |  Expected Output | Actual Output | Type Of Test |
| ------- | ----------- | -------------- | ---------------- | ------------- | ------------ |
| L_01  | Whether the door close |  LED will not blink |SUCCESS | SUCCESS  | Scenario based |
| L_02  | is the door open  | clicking on switch | SUCCESS | SUCCESS | Scenario based |


# OUTPUT
![Screenshot (30)](https://user-images.githubusercontent.com/101825270/164890706-c759ae06-e104-4c4a-a1ee-730d38790b39.png)
