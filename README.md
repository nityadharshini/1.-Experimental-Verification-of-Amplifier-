#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
![WhatsApp Image 2025-12-01 at 08 20 13_35abb0d5](https://github.com/user-attachments/assets/6b759046-37b0-441d-8214-ece14dcebac1)

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-12-01 at 08 20 29_6534cea3](https://github.com/user-attachments/assets/a049cdb3-3187-4c6e-bf0c-f7a1ee8ef829)

MODEL GRAPH 
![WhatsApp Image 2025-12-01 at 08 20 52_0f381261](https://github.com/user-attachments/assets/7c2b7bda-6653-43d1-9150-514f9b868aad)


DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


##Tabulation
![WhatsApp Image 2025-12-01 at 08 23 35_e4480380](https://github.com/user-attachments/assets/65d091ae-3d4d-4ab0-88e0-89258a8e38b7)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-01 at 08 24 02_cee31b3c](https://github.com/user-attachments/assets/0f7f7fd0-6b8c-4967-94e1-9fdc9f217b15)

![WhatsApp Image 2025-12-01 at 08 24 07_a08ab800](https://github.com/user-attachments/assets/2471613f-7d93-40fc-adfe-a58a0b0684f9)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![WhatsApp Image 2025-12-01 at 08 26 14_4a1483f3](https://github.com/user-attachments/assets/7fde997e-a550-4f0e-b15d-51e1028962a6)


---

## MODEL GRAPH
![WhatsApp Image 2025-12-01 at 08 26 37_780fbd98](https://github.com/user-attachments/assets/4750943e-6899-4a59-9037-b02be4285da5)


---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

![WhatsApp Image 2025-12-01 at 08 26 47_a19cda80](https://github.com/user-attachments/assets/7c79f152-eb7c-4cd2-845c-c24fb125a2e0)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-01 at 08 29 53_c24bea8f](https://github.com/user-attachments/assets/c5e10068-6113-4950-8615-e6b0ca7d6bb9)

![WhatsApp Image 2025-12-01 at 08 30 12_22dd891b](https://github.com/user-attachments/assets/8e92b2fd-ba92-4252-bce1-535d92949425)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-12-01 at 08 32 21_866f8257](https://github.com/user-attachments/assets/278c5e22-20aa-4d1e-bdeb-d1cca6b92d61)

## MODEL GRAPH
![WhatsApp Image 2025-12-01 at 08 32 42_09aefba2](https://github.com/user-attachments/assets/fdd7b7c7-8b32-4059-b28a-19e66fcb1dbf)

---

## DESIGN


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-12-01 at 08 34 24_f5aa48e7](https://github.com/user-attachments/assets/d6ce5484-47e6-4178-a8a4-2c2c195444e7)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-01 at 08 34 42_36eb0e53](https://github.com/user-attachments/assets/d95ae941-50c6-4c88-843a-7b3420f69be8)


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![WhatsApp Image 2025-12-01 at 08 39 14_1a880607](https://github.com/user-attachments/assets/59167975-1ead-4c14-a57c-eb935482e4fb)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2025-12-01 at 08 39 31_86200b91](https://github.com/user-attachments/assets/eb2ae822-f029-47a1-8aa9-0def79aa4380)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-01 at 08 39 52_462b1c62](https://github.com/user-attachments/assets/e44b340f-fa7d-4b8d-bdfa-5540bd1493d1)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
