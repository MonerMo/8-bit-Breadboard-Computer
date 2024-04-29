# 8-bit-Breadboard-Computer
This repository will be a documentation for my journey bulding 8-bit breadboard computer.

:rotating_light: :rotating_light: I finished the following 
- :white_check_mark: [Source Clock Module](#source-clock-based-on-555-timer-ic)
- :white_check_mark: [Processor Registers](#processor-registersregister-a--b)
- :white_check_mark: [ALU with Registers](#alu)
- :white_check_mark: [RAM Module](#ram-module) 
- :white_check_mark: ROM
- :white_check_mark: Seven Segment for data representation
- :white_check_mark: Auxilary Register for Reading Data Bus

## Merging the Clock with Registers and ALU.
# Source Clock based on 555 Timer IC
In this clock module I used the same hardware as ben mentioned it in his videos , Also I implemented the circuit with the same way/technique as ben.

Specifications : 
- Pulsating Clock Mode.
- Step by Step Clock Mode.
- Halt Mode.

**Module Photos**
![clock1:](https://i.imgur.com/BZQZCNP.jpg)
![clock2:](https://i.imgur.com/8KJAW20.jpg)



**Link to youtube video demonstration :** :film_strip:
[![IMAGE ALT TEXT HERE](https://i.imgur.com/cQbpVxn.png)](https://www.youtube.com/watch?v=XBoaQCD_zWA)

---

# Processor Registers(Register A & B) 
In this module I used [74LS173N](https://www.jameco.com/z/74LS173-Major-Brands-IC-74LS173-4-BIT-D-TYPE-REGISTER-3-STATE-OUTPUT_46922.html) IC for the 8-bit register.
![IC's Package:](https://i.imgur.com/ziqLQek.jpg)

The Implementation and the remaining IC's is same as what ben used in his videos.

**Module Photos**
![Register module:](https://i.imgur.com/WnOKqrx.jpg)

**Link to youtube video demonstration :** :film_strip:
[![IMAGE ALT TEXT HERE](https://i.imgur.com/cQbpVxn.png)](https://www.youtube.com/watch?v=XBoaQCD_zWA)

---

# ALU 
In this module I used : 
- SN54/74LS83A 4-BIT BINARY FULL ADDER WITH FAST CARRY.
- M74HCT245 OCTAL BUS TRANSCEIVER WITH 3 STATE OUTPUTS.
- SN54/74LS86 QUAD 2-INPUT EXLUSIVE OR GATE.

**Module Photos**
![ALU moudle:](https://i.imgur.com/t1yiO32.jpeg)
![ALU moudle:](https://i.imgur.com/JxEyBlY.jpeg)
![ALU module:](https://i.imgur.com/ASesUQI.jpeg)
![ALU module:](https://i.imgur.com/6WMfTsS.jpg)
![ALU module:](https://i.imgur.com/9XWqc8b.jpg)
![ALU module:](https://i.imgur.com/Ll7SI1Y.jpg)

---
# RAM Module
**Module Photos**
![RAM module:](https://i.imgur.com/hZh622w.jpeg)
![RAM module:](https://i.imgur.com/RNc7V8f.jpeg)
![RAM module:](https://i.imgur.com/50xHLHR.jpeg)

---
# ROM Module
**Module Photos**
![ROM Module:](https://i.imgur.com/ip8IT5f.jpeg)

---
# ROM Module & 7 Segment
![Integrating](https://i.imgur.com/Nm9iW7k.jpeg)
![Integrating](https://i.imgur.com/ImdbJq4.jpeg)

---
# Auxilary Register for Reading Data Bus
![Auxilary](https://i.imgur.com/S2lPZmY.jpeg)

