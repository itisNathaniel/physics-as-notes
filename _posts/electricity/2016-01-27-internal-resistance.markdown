---
layout: post
title:  8. Internal Resistance (and Required Practical 6)

categories: electricity practical
---
**Internal Resistance**

* Resistance comes from electrons colliding with atoms and losing energy 
* In batteries, chemical energy is used to move electrons, and atoms collide inside the battery as this happens, creating internal resistance
* Makes batteries and cells warm up when they're used
* *Load resistance* is the total resistance of all components in the circuit, also called *external resistance*

---
**E.m.f (electromotive force)**

* Is the amount of energy battery produces and transfers to each coloumb of charge
* It isn't actually a force as it's measured in volts
\\[ \varepsilon =\dfrac {E}{Q} \\]
*Where ε = electromotive force (V), E = Electrical Energy (J), Q = Charge (C)*
* The p.d across the load resistance (R) is the energy which is transferred when one coulomb of charge flows through the load resistance
* The potential difference is called the *terminal p.d* and is the same as the EMF if the load resistance is zero
* In power supplies there's always some energy lost overcoming the internal resistance
* The energy lost per coulomb overcoming the internal resistance are called the *lost volts (V)*
* The conservation of energy states that the energy supplied per coulomb = energy per coulomb transferred in load resistance + energy wasted overcoming load resistance.

---
**Calculating e.m.f and Internal Resistance**

In formula booklet:
\\[ \varepsilon = I(R+r) \\]
*where ε = e.m.f (V), R = load resistance (Ω), internal resistance (Ω)*

Not in formula booklet:

* Expand brackets to get ε=IR+Ir, use V=IR to sub in V for both terminal and lost volts
\\[ \varepsilon = V+v \\]

* Rearrange to give equation for terminal p.d
\\[ V = \varepsilon-v \\]

* Substitute back in Ir for the lost volts
\\[ V = \varepsilon-Ir \\]

* To calculate power lost as heat overcoming internal resistance
\\[ P = I^2R \\]

.

	Q: Battery e.m.f 0.15V, internal resistance 0.50Ω. Calculate terminal
	p.d	when current is 6mA
	A: V = ε - Ir --> V = 0.015 - 6x10^-3x0.5 --> 0.15-(0.006x0.5) --> 0.15V
	
	Q: Cell has internal resistance 0.35Ω and 0.6A current flowing through 
	it. Calculate energy dissipated due to internal resistance per second. 
	A: P=(0.6)^2x0.35 --> P=0.13W --> E=0.13J
	
---
**Measuring internal resistance and e.m.f (Required Practical 6)**
![]({{ site.baseurl }}/image/posts/internalresistance.gif)
*The circuit needed to find internal resistance, and resulting graph*

1. Set variable resistor to highest resistance (the load resistance) and then close switch and record the current and potential difference. Open and close the switch again to take results again and get an average for current and p.d. 
2. Decrease the resistance slightly and then repeat step 1, ensure all other factors such as temperature kept the same.
3. Repeat step 2 until have 8 different results over a large range
4. Draw a graph of V-I for the results recieved and draw a line of best fit
5. Rearrange *V = ε - Ir* to get *V = -rI + ε* which is in form *y=mx+c* (a line)
6. Can reading ε from the graph (the y intercept) and -R (the gradient).


