---
layout: post
title:  9. Energy Conservation

categories: electricity
---
**Charge Conservation**

* As charge flows through a circuit it isn't used up
* Any charge which enters a junction must leave it too
* As current is rate of flow of charge, current flowing into a junction same as current flowing out
* Energy transfrred to a charge is e.m.f and energy transferred from a charge is p.d
* Laws of conservation developed by Gustav Kirchoff

**First Law:**
Total current entering junction = total current leaving junction

**Second Law:**
Total e.m.f around series circuit = sum of p.d.s across each of the components
\\[ \varepsilon = \Sigma IR\\]

---
**Applying Kirchoff's Laws in series:**

![]({{ site.baseurl }}/image/posts/kirchoffseries.png)
*Series Circuit*

* Same current at all points in the circuit (no junctions)
* e.m.f split equally between all components (Kirchoff's 2nd)
\\[ \varepsilon = V_1+V_2+V_3\\]

* Voltage split proportionally to resistance, as V=IR
\\[ IR_T = IR_1+IR_2+IR_3\\]
* Cancel I to give:
\\[R_T=R_1+R_2+R_2\\]
*(T=total)*

		Q: If 1Ω and 3Ω resistor, what would the split be between the two?
		A: 1/4 across 1Ω resistor, 3/4 across 3Ω resistor

---
**Applying Kirchoff's Laws in parallel:**

![]({{ site.baseurl }}/image/posts/kirchoffparallel.png)
*Parallel Circuit*

* Current split equally across all components
\\[I=I_1+I_2+I_3\\]
* Three separate loops, within each loop EMF is equal to sum of individual p.d.s
\\[ \dfrac {V}{R_T} = \dfrac {V}{R_1}+\dfrac{V}{R_2}+\dfrac {V}{R_3}\\]
* Cancel V to give 
\\[\dfrac{1}{R_1} = \dfrac{1}{R_1} + \dfrac{1}{R_2} + \dfrac {1}{R_3}\\]

--- 
**Cells**

* To calculate total e.m.f of cells in series and parallel add their e.m.f.s
* As each charge goes through each cell so gains electrical energy from each of them
* For identical cells in series and parallel the total e.m.f of the combination is equal to the e.m.f of individual cells
* The amount of charge flowing doesn't increase by adding cells in parallel but number of paths does
	* Current is split equally between identical cells
	* Charge only increases e.m.f from cell it travels through so overall e.m.f doesn't increase

--- 

![]({{ site.baseurl }}/image/posts/2cellsparallel1series.png)![]({{ site.baseurl }}/image/posts/5resistors1battery.png)

	
	(Using Fig.1) Q: Three identical cells connected as shown above. 
	Each has 2V e.m.f	and negligible internal resistance. Find total e.m.f.
	A: A = B so 2V + 2V from series --> 4V

	(Using Fig.2) Q: Battery has negligible internal resistance. 
	Total circuit resistance is 10Ω. Find: 
	1). R resistance, 2). p.d across 5Ω resistor, 3). 6Ω resistor current
	
	A: 1). 10 - 5 - 1/(1/3+1/6) --> 1/3 = 1/12 + 1/r --> 1/r = 1/4 --> R=4Ω
	2). I = V/R --> I = 12/10 --> I = 1.2A --> V= 1.2x5 --> 6V
	3). V = IR --> V=1.2x2 --> 2.4V --> I = V/R --> I = 2.4/6 --> I = 0.4  






