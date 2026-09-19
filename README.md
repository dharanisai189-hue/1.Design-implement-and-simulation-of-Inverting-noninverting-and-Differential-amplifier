# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**
<img width="1600" height="1421" alt="design 1" src="https://github.com/user-attachments/assets/e2d946e0-b229-4415-8a6d-73a7c6f021f5" />
<img width="1599" height="1066" alt="design 2" src="https://github.com/user-attachments/assets/4d250f23-71be-40dd-ba7c-061765cc6f35" />



**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**
<img width="1600" height="1176" alt="pin" src="https://github.com/user-attachments/assets/bbb9b769-58ab-406c-b8d8-55c8b9cef1fb" />


**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  <img width="1386" height="1600" alt="circuit invert" src="https://github.com/user-attachments/assets/9fab87a1-345e-4fb7-b253-253013c028dc" />



  **MODEL GRAPH:**
  <img width="1600" height="1128" alt="invert model" src="https://github.com/user-attachments/assets/af981ec0-8388-4839-bdff-073f8222e734" />



  **TABULATION:**
  <img width="1599" height="1200" alt="WhatsApp Image 2026-09-19 at 6 05 19 AM" src="https://github.com/user-attachments/assets/183adb6e-0647-42b1-ac75-803955e27c73" />

 

**MODEL CALCULATION:**

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  <img width="1600" height="1200" alt="WhatsApp Image 2026-09-19 at 5 53 26 AM" src="https://github.com/user-attachments/assets/82a11b09-b0e4-4f07-be92-ef36c4af9f8b" />



  **MODEL GRAPH:**


  **TABULATION:**
  <img width="1600" height="496" alt="WhatsApp Image 2026-09-19 at 5 53 31 AM" src="https://github.com/user-attachments/assets/dfe3c16a-e588-4f5d-af70-c35ff3a5f683" />


  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  <img width="1600" height="1199" alt="WhatsApp Image 2026-09-19 at 5 53 27 AM" src="https://github.com/user-attachments/assets/b811c648-17f4-4428-b886-57ce9dfa9463" />



  **MODEL GRAPH:**
  <img width="1599" height="898" alt="WhatsApp Image 2026-09-19 at 5 53 30 AM" src="https://github.com/user-attachments/assets/91659993-224c-485b-9d4d-9f324eb72a9a" />



  **TABULATION:**
  <img width="1600" height="1200" alt="WhatsApp Image 2026-09-19 at 5 53 31 AM (1)" src="https://github.com/user-attachments/assets/456fe571-ae69-4bf1-ba77-33792784588f" />


**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
  <img width="957" height="1600" alt="WhatsApp Image 2026-09-19 at 5 53 34 AM (2)" src="https://github.com/user-attachments/assets/bbf9d5b5-f349-4c49-ab9e-8d319c92e0d7" />

  <img width="1158" height="1380" alt="WhatsApp Image 2026-09-19 at 5 53 36 AM" src="https://github.com/user-attachments/assets/2d9d1f5a-ba57-4ac7-8144-067af9975ac2" />


**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






