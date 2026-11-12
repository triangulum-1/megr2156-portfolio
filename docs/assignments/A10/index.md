# A10 – Lead Screw Translating System

## Objective
Design a lead-screw-driven tensile tester capable of applying a maximum tensile load of 2 kN while maintaining the required factor of safety and a maximum crosshead deflection of 0.1 mm. The design includes lead screws, flange nuts, a crosshead, structural framing, and a complete parametric SolidWorks assembly.

## Analyze
Leadscrew Design (Liam DiProfio)
!Minimum leadscrew diameter calculations

Figure 1: Calculations for the minimum required leadscrew diameter.

!Leadscrew rotational speed calculations

Figure 2: Calculations for the required leadscrew rotational speed.

Nut and Flange Selection (Liam DiProfio)
!Nut and flange thread calculations

Figure 3: Calculations used to verify the nut's internal thread strength.

!Selected flange specifications

Figure 4: Selected flange and its mounting dimensions.

!Flange mounting bolt specifications

Figure 5: Selected mounting bolt specifications.

Crosshead Design (Jordi Melendez Salgado)
!Crosshead beam stress calculations

Figure 6: Crosshead beam stress and strength calculations.

!Crosshead deflection calculations and design sketch

Figure 7: Crosshead deflection calculations and preliminary design sketch.

Component Cost Analysis (Jordi Melendez Salgado)

Item Number	Qty.	Component	Cost/Item	Total
97790A110	2	Precision Acme Flange Nut	$178.60	$357.20
98940A625	2	4140 Steel Precision Acme Leadscrew	$52.97	$105.94
40-4040	2	Metric T-Slot Framing (3 m)	$107.33	$214.66
Total Cost		$677.80
Purchase Links:

McMaster-Carr – Flange Nut
McMaster-Carr – Leadscrew
Grainger – Metric T-Slot Framing
## Decide
Parametric SolidWorks Assembly (Jordi Melendez Salgado)
!Completed SolidWorks tensile tester assembly

Figure 8: Completed parametric SolidWorks assembly of the tensile tester.

Download SolidWorks Assembly

Crosshead Finite Element Analysis (Jordi Melendez Salgado)
The crosshead was assigned A36 structural steel with an approximate yield strength of 250 MPa. An initial SolidWorks simulation was performed to evaluate the von Mises stress, displacement, and strain under the applied loading conditions.

!Initial crosshead von Mises stress results

Figure 9: Initial FEA stress results. Maximum stress: 1.177 × 10⁶ Pa.

!Initial crosshead displacement results

Figure 10: Initial FEA displacement results. Maximum displacement: 6.641 × 10⁻⁵ m.

!Initial crosshead strain results

Figure 11: Initial FEA strain results. Maximum strain: 4.685 × 10⁻⁶.

Using the maximum von Mises stress of 1.177 MPa and the A36 steel yield strength of 250 MPa, the calculated factor of safety was approximately 212.4.

Second Mesh Test (Jordi Melendez Salgado)
A second simulation was performed using a refined mesh to evaluate the effect of mesh refinement on the crosshead results.

!Second mesh test stress results

Figure 12: Second mesh test stress results. Maximum stress: 1.409 MPa.

!Second mesh test displacement results

Figure 13: Second mesh test displacement results. Maximum displacement: 6.653 × 10⁻⁵ m.

!Second mesh test strain results

Figure 14: Second mesh test strain results. Maximum strain: 5.543 × 10⁻⁶.

Using the A36 steel yield strength of 250 MPa, the calculated factor of safety for the second simulation was approximately 177.4. Both simulations indicate that the crosshead remains well below the material's yield strength.

Detailed Crosshead Engineering Drawing (Jordi Melendez Salgado)
!Final crosshead engineering drawing

Figure 15: Final dimensioned crosshead engineering drawing.

## Communicate
The tensile tester was designed around a maximum tensile load of 2 kN. I first determined the required leadscrew diameter and rotational speed based on the loading conditions, factor of safety, and specified crosshead speed. After selecting the leadscrews, I evaluated the internal threads of the flange nuts to ensure they could safely withstand the applied load. Both leadscrews use identical components to maintain consistency throughout the assembly.

For the crosshead, I performed beam stress and deflection calculations to determine the required dimensions and material. The design was required to maintain a maximum deflection of 0.1 mm. SolidWorks finite element analysis was then used to verify the design. The initial simulation produced a maximum von Mises stress of 1.177 MPa and a factor of safety of approximately 212.4. A second mesh test produced a maximum stress of 1.409 MPa and a factor of safety of approximately 177.4. Both results indicate that the crosshead can safely withstand the applied loading conditions.

The final SolidWorks assembly combines the crosshead, leadscrews, flange nuts, and metric T-slot structural framing. The total cost of the purchased components was $677.80. Throughout this assignment, I gained experience applying mechanical design calculations, selecting commercial components, performing finite element analysis, and developing parametric CAD models. The project required approximately 15 hours of design work, including calculations, component selection, and SolidWorks modeling.

