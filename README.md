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
![WhatsApp Image 2025-12-01 at 11 06 08_e5710ad3](https://github.com/user-attachments/assets/43f385ed-9bc8-47bf-be68-e10ffd22c8ec)

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-12-01 at 11 06 36_16c01f03](https://github.com/user-attachments/assets/19f10b2c-55bc-4b73-838c-ce04a2a47ace)


MODEL GRAPH 

![WhatsApp Image 2025-12-01 at 11 07 09_01975867](https://github.com/user-attachments/assets/42912aea-7f73-4229-9d73-57989a726afe)




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

![WhatsApp Image 2025-12-01 at 11 07 46_71ad358a](https://github.com/user-attachments/assets/73f63398-40eb-42a7-9b45-b08c1356547d)
	
 


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-01 at 11 08 05_e2c5703b](https://github.com/user-attachments/assets/aa11c4a2-f54b-4fbc-a471-df222bfac063)

---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


![WhatsApp Image 2025-12-01 at 11 08 37_8879ca7b](https://github.com/user-attachments/assets/465eeb3c-f832-4fc6-a73e-bae3c879e8d8)


---

## MODEL GRAPH
![WhatsApp Image 2025-12-01 at 11 09 02_ba380f70](https://github.com/user-attachments/assets/8574af3f-42a0-4c62-bee8-bff1fe25b2de)



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

![WhatsApp Image 2025-12-01 at 11 09 33_43f4b11b](https://github.com/user-attachments/assets/e3ea30b9-d691-42eb-b831-d0a6735ee75d)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-01 at 11 09 52_488ba7d2](https://github.com/user-attachments/assets/be758a67-e79a-4114-8609-00d1956506bf)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-12-01 at 11 10 21_fee53fcf](https://github.com/user-attachments/assets/508cf7ed-7d6c-490c-86b8-4c8a7f3039e9)

## MODEL GRAPH
![WhatsApp Image 2025-12-01 at 11 12 30_99ec2717](https://github.com/user-attachments/assets/e1007d06-52e1-49cd-a4d0-7ebcefc66f94)

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

![WhatsApp Image 2025-12-01 at 11 13 03_4dd898b4](https://github.com/user-attachments/assets/db6ea9a0-92a9-4975-b4fc-ece8af5bea8a)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-01 at 11 13 28_785e6ed3](https://github.com/user-attachments/assets/b0405207-d302-4614-9e00-fe2631206f69)


---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![WhatsApp Image 2025-12-01 at 11 15 41_897bb20a](https://github.com/user-attachments/assets/f1f185fa-3141-4e2d-8874-5a344db826e2)


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

![WhatsApp Image 2025-12-01 at 11 16 09_e9afad7b](https://github.com/user-attachments/assets/1d35be51-7c0b-4e2f-94b7-987f4e4af222)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-01 at 11 16 51_27888472](https://github.com/user-attachments/assets/4106863a-5865-49c4-88e1-0b00f5e2005f)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
