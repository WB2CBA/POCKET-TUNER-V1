# POCKET-TUNER-V1

![POCKET TUNER V1 Compraison](https://github.com/WB2CBA/POCKET-TUNER-V1/assets/59450739/de6cd134-43d4-48f4-8289-9c5c8aabd542)

POCKET TUNER V1.1 UPDATE – 08/2024
I updated POCKET TUNER SCHEMATIC and PCB LAYOUT. The new layout gerber file in POCKET TUNER github page: https://github.com/WB2CBA/POCKET-TUNER-V1
 The reason for this update was a difference in using the rotary encoders. Although I posted a linear increment Excell sheet for capacitor selection my method was a random selection. I chose this to get to the capacitor value faster than going through all capacitance values. It is like hit and miss. This created a confusion with fellow hams who built this tuner. I came to the conclusion that linear increment is a more intuitive method to get used with.
Also lowering 51 ohm / 2W resistors to 47 ohm 2 W resistors gave a better correlation between tune and actual SWR values.
Anyone who is just ordering the pcb will be covered by these changes if they download the gerber file from github page. They don’t need to make those changes listed below,
For users that are already built this pocket tuner here are changes listed to upgrade to this new scheme:
-	Replace  R1 -R2-R4 51 ohm/2Watt resistors with 47 ohm 2 Watt resistors.
-	Swap C4 and C5 capacitors.
-	Swap C8 and C9 capacitors.
-	Swap C10 and C11 capacitors.
-	Swap C14 and C15 capacitors.
The value of those capacitors are same. We are just changing the location of those capacitors by swapping them with eachother.
Now you will have a easier tuning experience with POCKET TUNER.


A Credit Card sized HF T-MATCH ANTENNA TUNER for QRPp and QRP Portable Operations

Lately I am fascinated with miniscule RF power HF rigs and their performance on Digital Modes such as FT-8 and FT4. 
Almost a year now I work QRPp on HF Digital Modes with a highly portable QRPp HF Transceiver with Sub 500 mW RF output from Parks, backpack hikes and from my car. I work mostly on 10m to 17m with my rig. All my QRPp QSOs can be checked on my QRZ log performed with my tiny rig.
All working great except with one minor issue, lacking a highly portable antenna Tuner to accompany my setup in my backpack. ATU type tuners such as ATU-10 or so fail to tune below 500 mW! 
My go to Tuner is a 4State QRP tuner which I grabbed from a hamfest as a second hand. This tuner designed by David Cripe, NM0S and works like a charm! The only issue I have is it’s size! 
I wanted something the size of a credit card as a Tuner! So I took this challenge upon me and designed a T-Match tuner similar to David Cripe’s excellent 4State QRP Tuner with a twist and way smaller than that.

Some specs and aspects of this pocket tuner:

-	Works on HF Bands from 10m to 40m.

-	I can tune up to 5 watts with this tuner though my aim was more in QRPp zone which is sub 1 watt! Though I successfully used it with my ADX,QDX and QMX without any issues by keeping tuning TX times under 10
 seconds at a time not to heat up excessively. Then it works like a champ! 😊

-	It has a resistive tuning process indicator which is similar to any resistive tuner meaning does not stress your TRX in tuning mode by lowering SWR in tuning to 2 or lower. This is great not to expose RF PA
output stage to excessive SWR conditions while tuning as this is the case in Automatic Antenna Tuners.


Acknowledgement: I would like to thank David Cripe, NM0S for letting me use his Resistive tuning led indicator design in this tuner project. 
