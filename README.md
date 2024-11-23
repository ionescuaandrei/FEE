
# Electrical Circuit Concepts: Questions and Answers

This README contains a comprehensive set of questions and answers for various topics related to electrical circuits. 

---

## **1. Topology of Electrical Circuits**

1. **For a circuit with \( N \) nodes and \( B \) branches, how many sections (cut-sets) are in the system of independent sections?**  
   \( N - 1 \).

2. **For a circuit with \( N \) nodes and \( B \) branches, how many loops are in the system of independent loops?**  
   \( B - (N - 1) \).

3. **What exactly generates a twig?**  
   A branch that belongs to a tree.

4. **What exactly generates a chord?**  
   A branch not included in a tree.

5. **For a circuit with \( N \) nodes and \( B \) branches, how many twigs are there?**  
   \( N - 1 \).

6. **For a circuit with \( N \) nodes and \( B \) branches, how many chords are there?**  
   \( B - (N - 1) \).

---

## **2. Kirchhoff's Theorems**

1. **For a circuit with \( N \) nodes and \( B \) branches, how many independent first Kirchhoff’s equations (TKI) are there?**  
   \( N - 1 \).

2. **For a circuit with \( N \) nodes and \( B \) branches, how many independent second Kirchhoff’s equations (TKII) are there?**  
   \( B - (N - 1) \).

3. **First Kirchhoff’s theorem involves the sum of currents or voltages?**  
   Sum of currents at a node.

4. **Second Kirchhoff’s theorem involves the sum of currents or voltages?**  
   Sum of voltages in a loop.

5. **Are branch currents determined by twig or chord currents?**  
   Twig currents.

6. **Are branch voltages determined by twig or chord voltages?**  
   Twig voltages.

7. **Is the electrical voltage between two nodes a sum or difference of potentials?**  
   Difference.

---

## **3. Electric Power and Tellegen’s Theorem**

1. **In receivers' convention, do voltage and current have the same or opposite orientation?**  
   Same.

2. **In generators' convention, do voltage and current have the same or opposite orientation?**  
   Opposite.

3. **If the power of a receiver is positive, is it a consumer or producer?**  
   Consumer.

4. **If the power of a generator is negative, is it a consumer or producer?**  
   Consumer.

5. **What is the algebraic sum of powers transferred in a circuit?**  
   Zero.

---

## **4. Ideal Circuit Elements**

1. **What is the parameter of the ideal resistor?**  
   Resistance (\( R \)); unit: Ohm (\( \Omega \)).

2. **What is the equation defining an ideal resistor?**  
   \( U = R \cdot I \).

3. **What is the parameter of the ideal voltage source?**  
   Voltage (\( E \)); unit: Volt (\( V \)).

4. **What is the parameter of the ideal current source?**  
   Current (\( I \)); unit: Ampere (\( A \)).

5. **Does the short circuit have zero voltage or zero current?**  
   Zero voltage.

6. **Does the open circuit have zero voltage or zero current?**  
   Zero current.

---

## **5. Dependent and Independent Sources**

1. **What is the parameter of an ideal voltage source, and its unit of measurement?**  
   Voltage (\( E \)); unit: Volt (\( V \)).

2. **What is the parameter of an ideal current source, and its unit of measurement?**  
   Current (\( I \)); unit: Ampere (\( A \)).

3. **Does an ideal voltage source have constant voltage or current?**  
   Constant voltage.

4. **Does an ideal current source have constant voltage or current?**  
   Constant current.

---

## **6. Capacitors and Inductors**

1. **What is the parameter of an ideal capacitor?**  
   Capacitance (\( C \)); unit: Farad (\( F \)).

2. **What is the parameter of an ideal inductor?**  
   Inductance (\( L \)); unit: Henry (\( H \)).

3. **Relationship between current and voltage for a capacitor?**  
   \( i(t) = C \frac{du(t)}{dt} \).

4. **Relationship between current and voltage for an inductor?**  
   \( u(t) = L \frac{di(t)}{dt} \).

---

## **7. Thévenin’s and Norton’s Theorems**

1. **What does Thévenin’s theorem state?**  
   A linear circuit can be replaced by a single voltage source in series with a resistance.

2. **What does Norton’s theorem state?**  
   A linear circuit can be replaced by a single current source in parallel with a resistance.

3. **How to find Thévenin voltage?**  
   Open-circuit voltage at the terminals.

4. **How to find Norton current?**  
   Short-circuit current at the terminals.

5. **Relation between \( V_{Th} \) and \( I_{No} \)?**  
   \( V_{Th} = R_{eq} \cdot I_{No} \).

---

## **8. Superposition Theorem**

1. **What does the superposition theorem state?**  
   The total response in a linear circuit is the sum of responses from individual sources.

2. **How to turn off a voltage source?**  
   Replace with a short circuit.

3. **How to turn off a current source?**  
   Replace with an open circuit.

---

This document provides concise explanations for foundational circuit analysis topics. Expand sections as needed for further study!

## 5. Real Voltage and Current Sources

### Does the real voltage source represent an ideal voltage source connected in series or in parallel with an ideal resistor?
- A real voltage source represents an ideal voltage source connected in series with an ideal resistor.

### What are the parameters of the real voltage source?
- Electromotive force (E) and internal resistance (R).

### Is the (internal) resistance of the ideal voltage source zero or infinite?
- Zero.

### What is the equation which define a real voltage source?
- \( V = E - IR \), where \( E \) is the electromotive force and \( R \) is the internal resistance.

### What is the characteristic (U-I characteristic) of the real voltage source?
- A linear decreasing function: \( V = E - IR \).

### What is the intersection of the characteristic of the real voltage source with the voltage axis?
- \( V = E \) (when \( I = 0 \)).

### What is the intersection of the characteristic of the real voltage source with the current axis?
- \( I = rac{E}{R} \) (when \( V = 0 \)).

### Does the real current source represent an ideal current source connected in series or in parallel with an ideal resistor?
- A real current source represents an ideal current source connected in parallel with an ideal resistor.

### What are the parameters of the real current source?
- Current \( J \) and internal conductance \( G \).

### Is the (internal) conductance of the ideal current source zero or infinite?
- Infinite.

### What is the equation which define a real current source?
- \( I = J - GV \), where \( J \) is the current and \( G \) is the internal conductance.

### What is the characteristic (U-I characteristic) of the real current source?
- A linear decreasing function: \( I = J - GV \).

### What is the intersection of the characteristic of the real current source with the voltage axis?
- \( V = rac{J}{G} \) (when \( I = 0 \)).

### What is the intersection of the characteristic of the real current source with the current axis?
- \( I = J \) (when \( V = 0 \)).

## 6. Equivalence Theorem of Real Voltage and Current Sources

### What are the conditions for which a real voltage source with parameters E and R is equivalent to a real current source with parameters J and G?
- \( J = rac{E}{R} \) and \( G = rac{1}{R} \).

### What is the equivalent resistance of two resistors connected in series?
- \( R_{	ext{eq}} = R_1 + R_2 \).

### What is the equivalent resistance of two resistors connected in parallel?
- \( rac{1}{R_{	ext{eq}}} = rac{1}{R_1} + rac{1}{R_2} \).

### What is the equivalent electromotive force of two ideal voltage sources connected in series?
- \( E_{	ext{eq}} = E_1 + E_2 \).

### What is the equivalent electromotive force of two ideal voltage sources connected in parallel?
- Voltage sources cannot be directly connected in parallel unless their electromotive forces are equal.

### What is the equivalent current of two ideal current sources connected in series?
- Current sources cannot be directly connected in series unless their currents are equal.

### What is the equivalent current of two ideal current sources connected in parallel?
- \( J_{	ext{eq}} = J_1 + J_2 \).

### What is the equivalent element of an ideal voltage source connected in parallel with a real voltage source?
- A real voltage source with modified parameters.

### What is the equivalent element of an ideal current source connected in series with a real current source?
- A real current source with modified parameters.

## 7. Equivalence Star-Triangle Connection of Passive Branches. Current and Voltage Dividers Theorems.

### If three resistors, with equal resistances Rs, are connected in the star, what is the resistance Rt of the equivalent triangle scheme?
- \( R_t = 3R_s \).

### If three resistors, with equal resistances Rt, are connected in the triangle, what is the resistance Rs of the equivalent star scheme?
- \( R_s = rac{R_t}{3} \).

### If two resistors, with equal resistances, are connected in parallel, having known the total current I, what are the currents through the resistors (function on I)?
- \( I_1 = I_2 = rac{I}{2} \).

### If two resistors, with equal resistances, are connected in series, having known the total voltage U, what are the voltages along the resistors (function on U)?
- \( U_1 = U_2 = rac{U}{2} \).

## 8. Controlled Ideal Sources (VCVS, CCVS, CCCS, VCCS)

### What is the input port of the voltage-controlled voltage source (VCVS)?
- Voltage port.

### What is the input current of the voltage-controlled voltage source (VCVS)?
- Zero (ideal condition).

### What is the proportionality (transfer) coefficient between output and input ports of the voltage-controlled voltage source (VCVS)?
- Voltage gain (\( A_v \)).

### On which does the electromotive force of the voltage-controlled voltage source (VCVS) depend?
- Input voltage.

### What is the input port of the current-controlled voltage source (CCVS)?
- Current port.

### What is the input voltage of the current-controlled voltage source (CCVS)?
- Zero (ideal condition).

### What is the proportionality (transfer) coefficient between output and input ports of the current-controlled voltage source (CCVS)?
- Transresistance (\( R_m \)).

### On which does the electromotive force of the current-controlled voltage source (CCVS) depend?
- Input current.

### What is the input port of the current-controlled current source (CCCS)?
- Current port.

### What is the input voltage of the current-controlled current source (CCCS)?
- Zero (ideal condition).

### What is the proportionality (transfer) coefficient between output and input ports of the current-controlled current source (CCCS)?
- Current gain (\( A_i \)).

### On which does the (output) current of the current-controlled current source (CCCS) depend?
- Input current.

### What is the input port of the voltage-controlled current source (VCCS)?
- Voltage port.

### What is the input current of the voltage-controlled current source (VCCS)?
- Zero (ideal condition).

### What is the proportionality (transfer) coefficient between output and input ports of the voltage-controlled current source (VCCS)?
- Transconductance (\( G_m \)).

### On which does the (output) current of the voltage-controlled current source (VCCS) depend?
- Input voltage.
