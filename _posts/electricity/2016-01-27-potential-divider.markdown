---
layout: post
title:  I0. Potential Divider

categories: electricity
---
**What is it?**

* A circuit with a voltage source (battery) and resistors in series
* The p.d across the voltage source is split across the resistance in the resistances ratio
* Can use potential dividers to supply p.d between 0 and the p.d across power supply
* Useful if need a varying p.d or a p.d less than is provided by the power supply
* By the time the time the voltage reaches point Z, it has dropped by V1, remaining voltage which can be supplied to another component is Vout
* Vout is the same as voltage across R2 
![]({{ site.baseurl }}/image/posts/potentialdivider.gif)
*Potential Divider set-up* 

* Rearraning V=IR to get the formula
	* Total resistance R = R1 + R2 as resistors in series
	* Total voltage is Vs and current is I1
	* So Vs = I(R1+R2)
	* The potential divider equation itself is:

\\[ V_{out} = \dfrac {R_2}{R_1+R_2}V_s\\]

	Q: For the diagram above Vs=9V, Vout=6v. Suggest R1 and R2 values
	A: Vout/Vs --> 6/9 = 2/3
	R2/R1+R2 =2/3 so R1=100Ω, R2=200Ω

---
**Variable Resistors:**

* Replacing one of the resistors (i.e. R1) with a variable resistor would mean that Vout can be varied

**Light and Temperature sensors**

* Light-dependant resistor (LDR) has very high resistance in dark but lower in light
* An NTC thermistor has a high resistance at low temperatures but much lower at high temperatures 
* Both can be used in a potential divider varying output voltage with light or temperature

**Potentiometers**

* Variable resistor to replace both R1 and R2 of the divider
* Moving a slider adjusts the relative size of R1 and R2
* Useful when need to change voltage continuously (i.e. in stereos)

