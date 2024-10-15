# Engineering License Exam Study Guide: Basic Electrical and Electronics Engineering (AExE01)

## Table of Contents

1. [Basic Concepts](#1-basic-concepts)
   - 1.1 [Ohm's Law](#11-ohms-law)
   - 1.2 [Electric Voltage, Current, Power, and Energy](#12-electric-voltage-current-power-and-energy)
   - 1.3 [Conducting and Insulating Materials](#13-conducting-and-insulating-materials)
   - 1.4 [Series and Parallel Electric Circuits](#14-series-and-parallel-electric-circuits)
   - 1.5 [Star-Delta and Delta-Star Conversion](#15-star-delta-and-delta-star-conversion)
   - 1.6 [Kirchhoff’s Laws](#16-kirchhoffs-laws)
   - 1.7 [Types of Circuits](#17-types-of-circuits)
2. [Network Theorems](#2-network-theorems)
   - 2.1 [Superposition Theorem](#21-superposition-theorem)
   - 2.2 [Thevenin’s Theorem](#22-thevenins-theorem)
   - 2.3 [Norton’s Theorem](#23-nortons-theorem)
   - 2.4 [Maximum Power Transfer Theorem](#24-maximum-power-transfer-theorem)
3. [R-L, R-C, and R-L-C Circuits](#3-r-l-r-c-and-r-l-c-circuits)
   - 3.1 [Resonance in AC Circuits](#31-resonance-in-ac-circuits)
   - 3.2 [Active and Reactive Power](#32-active-and-reactive-power)
4. [Alternating Current Fundamentals](#4-alternating-current-fundamentals)
   - 4.1 [Generation of AC Voltages and Currents](#41-generation-of-ac-voltages-and-currents)
   - 4.2 [AC Waveforms and Equations](#42-ac-waveforms-and-equations)
   - 4.3 [Average, Peak, and RMS Values](#43-average-peak-and-rms-values)
   - 4.4 [Three-Phase Systems](#44-three-phase-systems)
5. [Semiconductor Devices](#5-semiconductor-devices)
   - 5.1 [Semiconductor Diodes](#51-semiconductor-diodes)
   - 5.2 [BJT Configurations and Biasing](#52-bjt-configurations-and-biasing)
   - 5.3 [MOSFET and CMOS Principles](#53-mosfet-and-cmos-principles)
6. [Signal Generators](#6-signal-generators)
   - 6.1 [Principles of Oscillators](#61-principles-of-oscillators)
   - 6.2 [RC, LC, and Crystal Oscillator Circuits](#62-rc-lc-and-crystal-oscillator-circuits)
   - 6.3 [Waveform Generators](#63-waveform-generators)
7. [Amplifiers](#7-amplifiers)
   - 7.1 [Classification of Output Stages](#71-classification-of-output-stages)
   - 7.2 [Class A, B, and AB Output Stages](#72-class-a-b-and-ab-output-stages)
   - 7.3 [Biasing Techniques](#73-biasing-techniques)
   - 7.4 [Power BJTs and Transformer-Coupled Push-Pull Stages](#74-power-bjts-and-transformer-coupled-push-pull-stages)
   - 7.5 [Tuned Amplifiers and Op-Amps](#75-tuned-amplifiers-and-op-amps)
8. [Practice Questions and Solutions](#8-practice-questions-and-solutions)

---

## 1. Basic Concepts

### 1.1 Ohm's Law

**Definition:**
Ohm's Law states that the current flowing through a conductor between two points is directly proportional to the voltage across the two points.

**Formula:**
\[ V = I \times R \]
Where:

- \( V \) = Voltage (Volts)
- \( I \) = Current (Amperes)
- \( R \) = Resistance (Ohms)

**Explanation:**

- **Voltage (V):** The potential difference that drives current through a circuit.
- **Current (I):** The flow of electric charge.
- **Resistance (R):** The opposition to current flow.

**Example Problem:**
*Given a resistor with a resistance of 10 Ω and a voltage of 5 V across it, calculate the current flowing through the resistor.*

**Solution:**
\[ I = \frac{V}{R} = \frac{5\, \text{V}}{10\, \Omega} = 0.5\, \text{A} \]

---

### 1.2 Electric Voltage, Current, Power, and Energy

**Voltage (V):**

- The potential difference between two points.
- Unit: Volt (V)

**Current (I):**

- The rate of flow of electric charge.
- Unit: Ampere (A)

**Power (P):**

- The rate at which electrical energy is transferred by an electric circuit.
- **Formula:**
  \[ P = V \times I \]
- Unit: Watt (W)

**Energy (E):**

- The capacity to do work.
- **Formula:**
  \[ E = P \times t \]
- Unit: Joule (J) or Watt-hour (Wh)

---

### 1.3 Conducting and Insulating Materials

**Conductors:**

- Materials that allow easy flow of electric current.
- **Examples:** Copper, Aluminum, Silver

**Insulators:**

- Materials that resist the flow of electric current.
- **Examples:** Rubber, Glass, Plastic

---

### 1.4 Series and Parallel Electric Circuits

**Series Circuits:**

- Components connected end-to-end.
- **Total Resistance (R_total):**
  \[ R_{\text{total}} = R_1 + R_2 + R_3 + \dots \]
- **Current (I):** Same through all components.

**Parallel Circuits:**

- Components connected across the same two points.
- **Total Resistance (R_total):**
  \[ \frac{1}{R_{\text{total}}} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} + \dots \]
- **Voltage (V):** Same across all components.

---

### 1.5 Star-Delta and Delta-Star Conversion

**Star (Y) to Delta (Δ) Conversion:**

- **Formulae:**
  \[ R_{AB} = \frac{R_1 R_2 + R_2 R_3 + R_3 R_1}{R_3} \]
  \[ R_{BC} = \frac{R_1 R_2 + R_2 R_3 + R_3 R_1}{R_1} \]
  \[ R_{CA} = \frac{R_1 R_2 + R_2 R_3 + R_3 R_1}{R_2} \]

**Delta (Δ) to Star (Y) Conversion:**

- **Formulae:**
  \[ R_1 = \frac{R_{AB} R_{CA}}{R_{AB} + R_{BC} + R_{CA}} \]
  \[ R_2 = \frac{R_{AB} R_{BC}}{R_{AB} + R_{BC} + R_{CA}} \]
  \[ R_3 = \frac{R_{BC} R_{CA}}{R_{AB} + R_{BC} + R_{CA}} \]

---

### 1.6 Kirchhoff’s Laws

**Kirchhoff’s Current Law (KCL):**

- The algebraic sum of currents entering a node is zero.
- **Formula:**
  \[ \sum I_{\text{entering}} = \sum I_{\text{leaving}} \]

**Kirchhoff’s Voltage Law (KVL):**

- The algebraic sum of all voltages around any closed loop in a circuit is zero.
- **Formula:**
  \[ \sum V = 0 \]

---

### 1.7 Types of Circuits

**Linear vs. Non-Linear Circuits:**

- **Linear Circuits:** Parameters (resistance, inductance, capacitance) are constant with respect to voltage and current.
- **Non-Linear Circuits:** Parameters change with voltage and current.

**Bilateral vs. Unilateral Circuits:**

- **Bilateral Circuits:** Circuit properties are the same in either direction.
- **Unilateral Circuits:** Circuit properties change with the direction of current.

**Active vs. Passive Circuits:**

- **Active Circuits:** Contain active components (can supply energy), e.g., transistors.
- **Passive Circuits:** Contain passive components (cannot supply energy), e.g., resistors, capacitors.

---

## 2. Network Theorems

### 2.1 Superposition Theorem

**Statement:**
In a linear circuit with multiple independent sources, the response (voltage or current) in any element is the algebraic sum of the responses caused by each independent source acting alone.

**Procedure:**

1. Select one independent source; replace all other independent voltage sources with short circuits and current sources with open circuits.
2. Calculate the response due to the selected source.
3. Repeat steps 1 and 2 for each independent source.
4. Sum all individual responses.

---

### 2.2 Thevenin’s Theorem

**Statement:**
Any linear bilateral circuit can be replaced by an equivalent circuit consisting of a single voltage source (V_TH) in series with a resistance (R_TH).

**Procedure:**

1. Remove the load resistor from the original circuit.
2. Calculate the open-circuit voltage across the load terminals (V_TH).
3. Calculate the equivalent resistance seen from the load terminals with all independent sources turned off (R_TH).
4. Draw the Thevenin equivalent circuit.

---

### 2.3 Norton’s Theorem

**Statement:**
Any linear bilateral circuit can be replaced by an equivalent circuit consisting of a single current source (I_N) in parallel with a resistance (R_N).

**Procedure:**

1. Remove the load resistor.
2. Calculate the short-circuit current across the load terminals (I_N).
3. Calculate the equivalent resistance (R_N) same as R_TH in Thevenin’s theorem.
4. Draw the Norton equivalent circuit.

---

### 2.4 Maximum Power Transfer Theorem

**Statement:**
Maximum power is transferred to the load when the load resistance (R_L) equals the Thevenin resistance (R_TH) of the source network.

**Formula:**
\[ R_L = R_{TH} \]

**Maximum Power:**
\[ P_{\text{max}} = \frac{V_{TH}^2}{4 R_{TH}} \]

---

## 3. R-L, R-C, and R-L-C Circuits

### 3.1 Resonance in AC Circuits

**Series Resonance:**

- Occurs in R-L-C series circuits when the inductive reactance equals the capacitive reactance.
- **Resonant Frequency (f_r):**
  \[ f_r = \frac{1}{2\pi\sqrt{LC}} \]

**Parallel Resonance:**

- Occurs in R-L-C parallel circuits under similar conditions.

---

### 3.2 Active and Reactive Power

**Active Power (P):**

- The real power consumed by resistive components.
- **Formula:**
  \[ P = V_{\text{rms}} I_{\text{rms}} \cos\phi \]
- Unit: Watt (W)

**Reactive Power (Q):**

- The power stored and released by inductive and capacitive components.
- **Formula:**
  \[ Q = V_{\text{rms}} I_{\text{rms}} \sin\phi \]
- Unit: Volt-Ampere Reactive (VAR)

**Apparent Power (S):**

- Combination of active and reactive power.
- **Formula:**
  \[ S = V_{\text{rms}} I_{\text{rms}} \]
- Unit: Volt-Ampere (VA)

**Power Factor (PF):**

- The ratio of active power to apparent power.
- **Formula:**
  \[ \text{PF} = \cos\phi = \frac{P}{S} \]

---

## 4. Alternating Current Fundamentals

### 4.1 Generation of AC Voltages and Currents

**Principle:**

- AC voltages are generated by rotating a coil within a magnetic field, inducing an electromotive force (EMF).

---

### 4.2 AC Waveforms and Equations

**Sinusoidal Waveform:**

- **Voltage Equation:**
  \[ v(t) = V_{\text{max}} \sin(\omega t + \phi) \]
- **Current Equation:**
  \[ i(t) = I_{\text{max}} \sin(\omega t + \phi) \]
Where:
- \( V_{\text{max}} \) = Peak voltage
- \( I_{\text{max}} \) = Peak current
- \( \omega \) = Angular frequency (\( \omega = 2\pi f \))
- \( \phi \) = Phase angle
- \( f \) = Frequency in Hz

---

### 4.3 Average, Peak, and RMS Values

**Peak Value (V_max or I_max):**

- Maximum value of voltage or current.

**Root Mean Square (RMS) Value:**

- Effective value of AC voltage or current.
- **Formula:**
  \[ V_{\text{rms}} = \frac{V_{\text{max}}}{\sqrt{2}} \]
  \[ I_{\text{rms}} = \frac{I_{\text{max}}}{\sqrt{2}} \]

**Average Value:**

- Average over half a cycle.
- **Formula:**
  \[ V_{\text{avg}} = \frac{2 V_{\text{max}}}{\pi} \]
  \[ I_{\text{avg}} = \frac{2 I_{\text{max}}}{\pi} \]

---

### 4.4 Three-Phase Systems

**Characteristics:**

- Consists of three sinusoidal voltages of equal magnitude and frequency but displaced by 120 degrees.

**Advantages:**

- Constant power delivery.
- More efficient than single-phase systems.

---

## 5. Semiconductor Devices

### 5.1 Semiconductor Diodes

**Characteristics:**

- Allows current flow in one direction.
- **Forward Bias:** Conducts current.
- **Reverse Bias:** Blocks current.

**I-V Characteristics:**

- Exponential relationship in forward bias.

---

### 5.2 BJT Configurations and Biasing

**Configurations:**

- **Common Emitter (CE):** Amplifies voltage and current.
- **Common Base (CB):** High voltage gain.
- **Common Collector (CC):** Voltage follower.

**Biasing:**

- **Purpose:** To set the transistor’s operating point.
- **Methods:**
  - Fixed Bias
  - Voltage Divider Bias
  - Emitter Bias

---

### 5.3 MOSFET and CMOS Principles

**MOSFET:**

- Voltage-controlled device.
- **Types:** Enhancement and Depletion mode.

**CMOS:**

- Complementary MOSFET (combines n-MOS and p-MOS).
- **Advantages:** Low power consumption.

---

## 6. Signal Generators

### 6.1 Principles of Oscillators

**Oscillator:**

- Generates periodic waveforms without external input.

**Requirements:**

- **Amplifier with Gain (A)**
- **Feedback Network (β)**
- **Barkhausen Criterion:**
  \[ A \beta = 1 \]
  \[ \text{Total phase shift} = 0^\circ \text{ or } 360^\circ \]

---

### 6.2 RC, LC, and Crystal Oscillator Circuits

**RC Oscillators:**

- Use resistors and capacitors.
- **Example:** Phase Shift Oscillator.

**LC Oscillators:**

- Use inductors and capacitors.
- **Example:** Hartley and Colpitts Oscillators.

**Crystal Oscillators:**

- Use quartz crystals for stable frequency.

---

### 6.3 Waveform Generators

**Types:**

- **Sine Wave Generators**
- **Square Wave Generators**
- **Triangle Wave Generators**

**Applications:**

- Testing and calibration of electronic circuits.

---

## 7. Amplifiers

### 7.1 Classification of Output Stages

**Classes:**

- **Class A:** Conduction angle = 360°
- **Class B:** Conduction angle = 180°
- **Class AB:** Conduction angle between 180° and 360°
- **Class C:** Conduction angle < 180°

---

### 7.2 Class A, B, and AB Output Stages

**Class A Amplifiers:**

- Operate over the entire input cycle.
- **Advantages:** Low distortion.
- **Disadvantages:** Low efficiency (~30%).

**Class B Amplifiers:**

- Operate over half the input cycle.
- **Advantages:** Higher efficiency (~78.5%).
- **Disadvantages:** Crossover distortion.

**Class AB Amplifiers:**

- Operate over more than half but less than full cycle.
- **Advantages:** Compromise between Class A and B.

---

### 7.3 Biasing Techniques

**Class AB Biasing:**

- Eliminates crossover distortion.
- **Methods:**
  - Diode Biasing
  - VBE Multiplier

---

### 7.4 Power BJTs and Transformer-Coupled Push-Pull Stages

**Power BJTs:**

- Designed to handle high currents and voltages.

**Transformer-Coupled Push-Pull Amplifiers:**

- Use transformers to combine outputs.
- **Advantages:** Efficient power transfer.

---

### 7.5 Tuned Amplifiers and Op-Amps

**Tuned Amplifiers:**

- Amplify a specific frequency or band.
- **Applications:** Radio frequency amplification.

**Operational Amplifiers (Op-Amps):**

- High-gain voltage amplifiers.
- **Characteristics:**
  - High input impedance.
  - Low output impedance.
- **Configurations:**
  - Inverting
  - Non-inverting
  - Differential

---

## 8. Practice Questions and Solutions

### Question 1

**Problem:**
Calculate the total resistance in a series circuit with three resistors of values 5 Ω, 10 Ω, and 15 Ω.

**Solution:**
\[ R_{\text{total}} = R_1 + R_2 + R_3 = 5\, \Omega + 10\, \Omega + 15\, \Omega = 30\, \Omega \]

---

### Question 2

**Problem:**
Using Thevenin's theorem, find the equivalent circuit across terminals A and B for the following circuit: A voltage source of 20 V in series with a resistor of 4 Ω is connected to terminals A and B, which are connected across a load resistor of 6 Ω.

**Solution:**

1. **Remove the Load Resistor (6 Ω).**
2. **Find V_TH (Open-Circuit Voltage):**
   - Since there's only one voltage source and one resistor, \( V_{TH} = 20\, \text{V} \).
3. **Find R_TH (Thevenin Resistance):**
   - With voltage source shorted, \( R_{TH} = 4\, \Omega \).
4. **Thevenin Equivalent Circuit:**
   - Voltage source of 20 V in series with a 4 Ω resistor across terminals A and B.

---

### Question 3

**Problem:**
Determine the resonant frequency of an R-L-C series circuit with L = 50 mH and C = 0.1 μF.

**Solution:**
\[ f_r = \frac{1}{2\pi\sqrt{LC}} \]
\[ f_r = \frac{1}{2\pi\sqrt{50 \times 10^{-3}\, \text{H} \times 0.1 \times 10^{-6}\, \text{F}}} \]
\[ f_r = \frac{1}{2\pi\sqrt{5 \times 10^{-9}}} \]
\[ f_r = \frac{1}{2\pi \times 7.07 \times 10^{-5}} \]
\[ f_r \approx \frac{1}{0.000444} \]
\[ f_r \approx 2257\, \text{Hz} \]

---

### Question 4

**Problem:**
A pure resistive AC circuit has an RMS voltage of 230 V and consumes 10 A of current. Calculate the active power consumed.

**Solution:**
\[ P = V_{\text{rms}} I_{\text{rms}} \cos\phi \]
For a pure resistive circuit, \( \cos\phi = 1 \).
\[ P = 230\, \text{V} \times 10\, \text{A} \times 1 = 2300\, \text{W} \]

---

### Question 5

**Problem:**
In a common-emitter BJT amplifier, if the base current is 20 μA and the current gain (\( \beta \)) is 100, find the collector current.

**Solution:**
\[ I_C = \beta I_B \]
\[ I_C = 100 \times 20 \times 10^{-6}\, \text{A} = 2\, \text{mA} \]

---

### Question 6

**Problem:**
An op-amp is configured in an inverting amplifier setup with a feedback resistor \( R_f = 100\, \text{k}\Omega \) and an input resistor \( R_{in} = 10\, \text{k}\Omega \). Calculate the voltage gain.

**Solution:**
\[ A_v = -\frac{R_f}{R_{in}} \]
\[ A_v = -\frac{100\, \text{k}\Omega}{10\, \text{k}\Omega} = -10 \]

---

### Question 7

**Problem:**
A Class B push-pull amplifier has a supply voltage of \( V_{CC} = 15\, \text{V} \). Determine the maximum output power.

**Solution:**
For Class B amplifier:
\[ P_{\text{max}} = \frac{V_{CC}^2}{2 R_L} \]
Assuming \( R_L = 8\, \Omega \),
\[ P_{\text{max}} = \frac{15^2}{2 \times 8} = \frac{225}{16} \approx 14.06\, \text{W} \]

---

## Conclusion

This study guide provides a comprehensive overview of the key concepts in Basic Electrical and Electronics Engineering as per your syllabus. Practice the provided problems and understand the underlying principles to prepare effectively for your engineering license exam. Good luck!
