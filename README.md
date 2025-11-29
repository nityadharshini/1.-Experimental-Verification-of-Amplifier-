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
![WhatsApp Image 2025-11-29 at 12 31 17_a6c4638f](https://github.com/user-attachments/assets/b8ca213e-ef88-4473-8356-054eef6304ac)

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-29 at 12 31 17_8d1edb24](https://github.com/user-attachments/assets/b5f4d84c-17ea-4922-bd4c-4503b21cd879)

MODEL GRAPH 
![WhatsApp Image 2025-11-29 at 12 31 17_41efc176](https://github.com/user-attachments/assets/b2b69761-2432-4659-83fc-af00b73198ea)


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


## TABULATION

![WhatsApp Image 2025-11-29 at 12 33 09_00e33c74](https://github.com/user-attachments/assets/b0265efd-fad7-40f3-ace3-a0c928b3c48e)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 12 34 40_a62e2c40](https://github.com/user-attachments/assets/c083f6ff-4de7-42f7-9b4c-f1b5ab8d545a)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-29 at 12 36 07_e6fddbc7](https://github.com/user-attachments/assets/2f62e01a-d4d1-4a7d-93c6-dc72b4341faf)



---

## MODEL GRAPH
![WhatsApp Image 2025-11-29 at 12 36 38_6efae09e](https://github.com/user-attachments/assets/87249521-e6dc-42da-9616-f48e95c0fc9e)


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
![WhatsApp Image 2025-11-29 at 12 37 35_c8c5c469](https://github.com/user-attachments/assets/4ba24716-7600-42e0-85c6-0ffdffbe98b5)


## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 12 38 02_65454f66](https://github.com/user-attachments/assets/3287b4a0-e56e-489f-b537-38db698664f4)


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-29 at 12 38 02_65454f66](https://github.com/user-attachments/assets/dd798cfe-9d07-4434-9db7-853f2b7e3095)

## MODEL GRAPH
![WhatsApp Image 2025-11-29 at 12 40 01_0d341419](https://github.com/user-attachments/assets/4b0f34b8-d62c-46ba-b21b-a27624f433a5)

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

![WhatsApp Image 2025-11-29 at 12 40 56_3a2a42d4](https://github.com/user-attachments/assets/7f7b5b0a-0526-4c35-bc80-2909ea4380b6)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 12 41 28_3c88b792](https://github.com/user-attachments/assets/e41279f5-0a1d-466a-8f6e-b06a22d299ef)


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![WhatsApp Image 2025-11-29 at 12 43 07_21b20204](https://github.com/user-attachments/assets/d9bbf3f9-570e-4ec4-bd59-b46919d6362a)


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

![WhatsApp Image 2025-11-29 at 12 43 58_3c22d4da](https://github.com/user-attachments/assets/2ed29448-601d-49d6-bf7e-7bcf6b78a86b)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-29 at 12 44 31_28b6cd79](https://github.com/user-attachments/assets/33586716-f917-4273-b4d9-2e2d7c4315a6)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
