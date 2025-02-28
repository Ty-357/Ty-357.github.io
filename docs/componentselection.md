---
title: Component Selection
---

Table 1

### **voltage regulator**

| Options | Pros | Cons |
| ------------------------- | ------------------------ | ------------------------ |
| <img src="docs/buck.jpg" width="150"> <br> NCV2575D2T-ADJ <br> Cost: 1.05 <br> [Link](https://www.digikey.com/en/products/detail/rochester-electronics-llc/NCV2575D2T-ADJ/12131096)| \* converts 40V-4.75V <br>\* low power standby <br> \* High Efficiency <br> used before| Increased shipping cost <br> low availability | 
|<img src="docs/lmr.jpg" width="150"> <br> LMR43610MSC3RPERQ1 <br> Cost 3.05 <br> [Link](https://www.digikey.com/en/products/detail/texas-instruments/LMR43610MSC3RPERQ1/17878345) | High efficiency <br> ships immediately | Higher cost <br> difficult mount |
| <img src="docs/TPS.jpg" width="150"> <br> TPS562201DDCR <br> Cost $0.35 <br> [Link](https://www.digikey.com/en/products/detail/texas-instruments/TPS562201DDCR/5808210) | Low Cost <br> overcurrent protection <br> allows variable output 0.76V to 7V | 

**Pick** Solution 1: the NCV2575D2T-ADJ is the surface mount version of the regulator we used in class its high efficiency and fixed output voltage are the main reasons to choose this option. the variable voltage input is also a nice feature.

Table 2

### **Microcontroller**

| Options | Pros | Cons |
| ------------------------- | ------------------------ | ------------------------ |
| <img src="PIC40.jpg" width="150"> <br> PIC18F47Q10-I/PT <br> Cost $1.65 <br> [Link](https://ww1.microchip.com/downloads/en/DeviceDoc/PIC18F27-47Q10-Data-Sheet-40002043E.pdf)| Two USTART <br> I2C comunication <br>  | Slow comunication <br> excess amount of pins
| <img src="PIC.png" width="150"> <br> PIC18F27Q10-I/PT <br> Cost $1.65 <br> [Link](https://ww1.microchip.com/downloads/en/DeviceDoc/PIC18F27-47Q10-Data-Sheet-40002043E.pdf)| Two USTART <br> I2C comunication <br> reasonable amount of pins | Slow comunication

**Pick** Solution 2: Between the two pic devices i choose the 27 pin package due to not needing as many pins as the 40 pin package offers. Another reason for choosing this package is that it what we used in class and doesnt have wifi.

Table 3

### **Sensor**

| Options | Pros | Cons |
| ------------------------- | ------------------------ | ------------------------ |
| <img src="docs/SHT.jpg" width="150"> <br> SHT40-AD1B-R2 <br> Cost $1.80 <br> [Link](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/6223/SHT4x.pdf) | Humidty and temperature sensor <br> supply voltage 1.08V to 3.6V <br> I2C communication <br> accurate up to .2 degrees C and 1.8% RH| Difficult to solder <br> increased coding dificulty
| <img src="docs/HDC.jpg" width="150">  <br> HDC2080DMBR <br> Cost $2.22 <br> [Link](https://www.digikey.com/en/products/detail/texas-instruments/HDC2080DMBR/9692560) | I2C comunitation <br> supply voltage 1.62V to 3.6V <br> accurate upto 2% RH | only humidity <br> difficult to solder
| <img src="docs/max.jpg" width="150">  <br> MAX6682MUA+T <br> Cost $5.67 <br> [Link](https://www.digikey.com/en/products/detail/analog-devices-inc-maxim-integrated/MAX6682MUA-T/1521564) | Easy to Solder <br> supply voltage 0.3V to 6V | High Cost <br> only temperature

**Pick** Solution 1: the SHT40-AD1B-R2 offers both temperature and humidity sensing data allowing for a more interactive display. Those who interact with our display will have two sets of information to adjust instead of one.
