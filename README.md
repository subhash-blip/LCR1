# RLC Circuit Simulation

This project demonstrates the simulation of a **series RLC circuit** using CircuitLab.

---

## Components Used

- **Resistor (R1):** 100 Ohms  
- **Inductor (L1):** 10 mH  
- **Capacitor (C1):** 100 uF  
- **DC Voltage Source (V1):** 10 V

---

## Objective

To study the **transient behavior** of a series RLC circuit when a DC voltage source is applied.

---

## Procedure

1. **Circuit Construction** using [CircuitLab](https://www.circuitlab.com/editor/):

   - Placed the DC source, resistor, inductor, and capacitor in a **series configuration**.
   - Attached a **ground connection** to the negative terminal of the voltage source for stable operation.

2. **Component Specifications**:

   - Resistor: 100 Ohms  
   - Inductor: 10 mH  
   - Capacitor: 100 uF  
   - Voltage Source: 10 V DC

3. **Simulation Setup** (Transient Analysis - Time Domain):

   - End Time: 0.1 seconds  
   - Time Step: automatic or manually set to 1 us

4. **Waveforms Observed**:

   - **Voltage across the capacitor (C1.v)**  
   - **Current through the resistor (R1.i)**

---

## Key Observations

- The **voltage across the capacitor** gradually builds up and stabilizes at 10 V.  
- The **current through the inductor** increases smoothly, opposing sudden changes.  
- At **steady state**, the capacitor fully charges and blocks DC current, while the inductor acts as a conductor.

---

## Circuit Diagram

![Circuit Diagram](circuit.png)

---

## Simulation Output

![Simulation Graph](simulation.png)

---

## Key Takeaways

- Learn the **transient response** of RLC circuits to DC input.  
- Observe how capacitors and inductors behave dynamically in circuits.  
- Gain hands-on experience in using CircuitLab for circuit simulation.

---

## Resources

- [CircuitLab Simulator](https://www.circuitlab.com/editor/)  
- [Series RLC Circuit Theory – Electronics Tutorials](https://www.electronics-tutorials.ws/accircuits/series-rlc-circuit.html)

---

cCreated by

Subhash
