
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
