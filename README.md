## **EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS

## **DATE:**  09-08-2025
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
| 6 | Resistors | 1.5K, 15K | 2 |
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

## PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

## CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-12-04 at 00 03 38_f1c8628b](https://github.com/user-attachments/assets/c06342f9-65e2-48e8-84fe-833e9e19140c)


MODEL GRAPH 

<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



## DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1.5kΩ, Rf=15kΩ
![WhatsApp Image 2025-12-04 at 00 06 55_35e20ecb](https://github.com/user-attachments/assets/79798f70-0bb0-44c2-b6cd-8d10ed35d832)


## PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION
![WhatsApp Image 2025-12-04 at 00 07 54_816b35aa](https://github.com/user-attachments/assets/356fe796-9539-42cf-97fc-ee33a657a0f5)




---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-04 at 00 09 30_7da7505c](https://github.com/user-attachments/assets/60918e67-36ec-4057-87e4-b1b0df6930d7)



---
### **Non-Inverting Amplifier** 
## **DATE:** 19-08-2025

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1
Rf=15kohm,R1=1.5kohm
![WhatsApp Image 2025-12-04 at 00 12 32_f05951b9](https://github.com/user-attachments/assets/dcf78e75-6106-4b12-a71e-12f6f9e11560)

---

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-12-04 at 00 10 10_7b631781](https://github.com/user-attachments/assets/a561c21f-7145-4a05-8e28-98f198de7a96)





---

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

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
![WhatsApp Image 2025-12-04 at 00 10 27_8d66d278](https://github.com/user-attachments/assets/f0eb3ea7-2fbe-4ac6-a5af-a3bbd50df116)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-04 at 00 11 02_ee47eac4](https://github.com/user-attachments/assets/9921ba03-db9b-4b4e-b79c-89dcded77555)
![WhatsApp Image 2025-12-04 at 00 11 28_28214ebd](https://github.com/user-attachments/assets/a35e4827-8c27-44cc-9f05-ce909008deea)



---
## DIFFERENTIAL AMPLIFIER 
## **DATE:** 23-08-2025

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-12-04 at 00 15 49_7c91160d](https://github.com/user-attachments/assets/90a2f41c-55bf-4b6f-b57d-6b75230206e8)


## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1.5kOhm, Rf = 15kOhm
![WhatsApp Image 2025-12-04 at 00 19 26_5ae6507f](https://github.com/user-attachments/assets/882299d6-eca7-408b-83b1-c196350472a8)


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
![WhatsApp Image 2025-12-04 at 00 16 21_7fd37162](https://github.com/user-attachments/assets/ed6596a0-e14f-4c13-9d7f-f2a2bf612013)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-04 at 00 16 56_2aae4a58](https://github.com/user-attachments/assets/29b192bc-cb43-4906-bc96-63f920e83328)

---
## INSTRUMENTATION AMPLIFIER 
## **DATE:** 28-10-2025

## THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
![WhatsApp Image 2025-12-04 at 00 21 22_08fe798d](https://github.com/user-attachments/assets/504b22c3-b005-43e7-a623-fec011c67fd0)


## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![WhatsApp Image 2025-12-04 at 00 20 45_33157bdd](https://github.com/user-attachments/assets/311bd5ad-7fe2-4d22-96ec-60d31a28429d)


## PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![WhatsApp Image 2025-12-04 at 00 21 03_a20577ff](https://github.com/user-attachments/assets/310668b0-4c83-4973-ade8-ebf48f511328)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-12-04 at 00 21 50_93c65db9](https://github.com/user-attachments/assets/b263728f-7fe5-4957-878f-3f33b4794b1d)



---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
