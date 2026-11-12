# A10 – Lead Screw Translating System

<section id="assignment10" class="page">
            <h2>Assignment 10</h2>
            <div class="section-box">
               
<h3>1. Leadscrew Design (Liam DiProfio)</h3>

<p>
    To begin designing the tensile tester, I performed the necessary
    calculations to determine the minimum leadscrew diameter and
    required rotational speed. The calculations account for the
    2 kN maximum tensile load and the required factor of safety.
</p>

![Work for Step 2 Part 1](Scanned_20261110-1916-01.jpg)

<p>
    Next, I calculated the required rotational speed range to achieve
    the specified crosshead linear speed.
</p>

![Work for Step 2 Part 1](Scanned_20261110-1916-02.jpg)

<p>
    After completing the calculations, I selected the leadscrew
    specifications based on the required loading and operating
    conditions. Both leadscrews will use identical components.
</p>

![Work for Step 2 Part 1](Scanned_20261110-1916-03.jpg)

<h3>2. Nut and Flange Selection (Liam DiProfio)</h3>

<p>
    After selecting the leadscrews, I analyzed the internal threads
    of the nut to verify that they could safely support the applied
    load. The following calculations were used to evaluate the
    thread strength and determine a suitable nut and flange.
</p>

![Work for Step 2 Part 1](Scanned_20261110-1916-04.jpg)

![Work for Step 2 Part 1](mcm1.jpg)

![Work for Step 2 Part 1](mcm2.jpg)

<h3>3. Crosshead Design (Jordi Melendez Salgado)</h3>

<p>
    After selecting the leadscrews and flange assembly, I moved on
    to designing the crosshead. I performed a beam stress analysis
    to determine the required dimensions and material needed to
    safely withstand the applied 2 kN tensile load while maintaining
    the required factor of safety.
</p>

![Work for Step 2 Part 1](IMG_9911.jpeg)

<p>
    I then performed a deflection analysis to verify that the
    crosshead would remain within the maximum allowable deflection
    of 0.1 mm. The following image also includes the preliminary
    crosshead sketch and its dimensions.
</p>

![Work for Step 2 Part 1](IMG_9912.jpeg)

    <h3>4. Tabulating Costs (Jordi Melendez Salgado)</h3>

<p>
    The following table summarizes the purchased components required
    for the tensile tester, including their quantities and costs.
</p>

<table>
    <thead>
        <tr>
            <th>Item Number</th>
            <th>Quantity</th>
            <th>Name</th>
            <th>Cost/Item</th>
            <th>Cost</th>
            <th>Purchase Link</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>97790A110</td>
            <td>2</td>
            <td>Precision Acme Flange Nut</td>
            <td>$178.60</td>
            <td>$357.20</td>
            <td><a href="https://www.mcmaster.com/97790A110/" target="_blank">McMaster-Carr</a></td>
        </tr>
        <tr>
            <td>98940A625</td>
            <td>2</td>
            <td>4140 Steel Precision Acme Leadscrew</td>
            <td>$52.97</td>
            <td>$105.94</td>
            <td><a href="https://www.mcmaster.com/98940A625/" target="_blank">McMaster-Carr</a></td>
        </tr>
        <tr>
            <td>40-4040</td>
            <td>2</td>
            <td>Metric T-Slot Framing (3 m)</td>
            <td>$107.33</td>
            <td>$214.66</td>
            <td><a href="https://www.grainger.com/category/material-handling/structural-framing-systems/t-slot-framing-systems/profiles-for-t-slot-framing/metric-profiles-for-t-slot-framing" target="_blank">Grainger</a></td>
        </tr>
        <tr>
            <td colspan="4">Total Cost</td>
            <td>$677.80</td>
            <td></td>
        </tr>
    </tbody>
</table>
                <h3>5. Parametric Modeling (Jordi Melendez Salgado)</h3>
<p>
    Below is the completed SolidWorks assembly of the tensile tester.
    The assembly combines the designed crosshead with the selected
    leadscrews, flange nuts, and structural framing.
</p>
<figure>
    <img src="images/a10.ss.1.png"
         alt="Completed SolidWorks tensile tester assembly"
         width="650">
    <figcaption>
        Figure 9: Completed parametric SolidWorks assembly of the tensile tester.
    </figcaption>
    <p>
    <a href="files/a10.SLDASM" download>
        Download SolidWorks Assembly
    </a>
</p>
</figure>
<h3>6. Lessons Learned (Liam DiProfio)</h3>
<p>
    Throughout this project, I learned how to apply mechanical design
    principles to develop a lead-screw-driven tensile tester. One of
    the most important lessons was understanding how rotational torque
    is converted into linear force through a lead screw. I also gained
    experience selecting components based on strength, safety factors,
    and dimensional requirements while considering crosshead deflection.
</p>
<p>
    This project took approximately 15 hours of design work, including
    calculations, component selection, and SolidWorks modeling.
</p>


    <h3>7. Crosshead Finite Element Analysis (Jordi Melendez Salgado)</h3>

<p>
    I performed an initial SolidWorks simulation to evaluate the
    crosshead under the applied loading conditions. The following
    results show the von Mises stress, displacement, and strain
    throughout the crosshead.
</p>

<figure>
    <img src="images/a10.ss2.png" alt="Initial crosshead von Mises stress results" width="650">
    <figcaption>Figure 10: Initial FEA stress results. Maximum stress: 1.177 × 10⁶ Pa.</figcaption>
</figure>

<figure>
    <img src="images/a10.ss3.png" alt="Initial crosshead displacement results" width="650">
    <figcaption>Figure 11: Initial FEA displacement results. Maximum displacement: 6.641 × 10⁻⁵ m.</figcaption>
</figure>

<figure>
    <img src="images/a10.ss4.png" alt="Initial crosshead strain results" width="650">
    <figcaption>Figure 12: Initial FEA strain results. Maximum strain: 4.685 × 10⁻⁶.</figcaption>
</figure>


<p>
    The crosshead was assigned A36 structural steel, which has a
    yield strength of approximately 250 MPa. Using the maximum
    von Mises stress of 1.177 MPa, the calculated factor of safety
    is approximately 212.4. This indicates that the crosshead
    remains well below the material's yield strength under the
    simulated loading conditions.
</p>

    <h3>Second Mesh Test (Jordi Melendez Salgado)</h3>
<p>
    I performed a second simulation using a refined mesh to evaluate
    how the mesh affected the crosshead results.
</p>

<figure>
    <img src="images/a10.ss5.png" alt="Second mesh test stress results" width="650">
    <figcaption>Figure 13: Second test von Mises stress. Maximum stress: 1.409 MPa.</figcaption>
</figure>

<figure>
    <img src="images/a10.ss6.png" alt="Second mesh test displacement results" width="650">
    <figcaption>Figure 14: Second test displacement. Maximum displacement: 6.653 × 10⁻⁵ m.</figcaption>
</figure>

<figure>
    <img src="images/a10.ss7.png" alt="Second mesh test strain results" width="650">
    <figcaption>Figure 15: Second test strain. Maximum strain: 5.543 × 10⁻⁶.</figcaption>
</figure>

<p>
    Using the A36 steel yield strength of 250 MPa, the calculated
    factor of safety for this test is approximately 177.4.
</p>

<h3>8. Detailed Crosshead Engineering Drawing (Jordi Melendez Salgado)</h3>
<p>
    The following drawing shows the final crosshead design,
    including its overall dimensions and mounting features.
</p>

<figure>
    <img src="images/a10.ss8.png"
         alt="Final crosshead engineering drawing"
         width="650">
    <figcaption>
        Figure 16: Final dimensioned crosshead engineering drawing.
    </figcaption>
</figure>
