# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:**  
         
---

## AIM
            
**DATE:**  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
<img width="522" height="338" alt="image" src="https://github.com/user-attachments/assets/8b7d9036-37a6-4da7-8f56-a33cd599c6c3" />



## MODEL GRAPH
<img width="557" height="461" alt="image" src="https://github.com/user-attachments/assets/f6f0bcdf-812d-4b74-8b3c-a7435b8d89a3" />


---

## DESIGN

<img width="521" height="436" alt="image" src="https://github.com/user-attachments/assets/b64a7ad1-5ba9-41e8-b0ab-1629d2091795" />



## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

<img width="642" height="533" alt="image" src="https://github.com/user-attachments/assets/680e4c42-492f-4a61-8b53-d248386f9549" />

		

---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1025" height="734" alt="image" src="https://github.com/user-attachments/assets/816479aa-aa3a-4a28-bd49-dfe518126327" />



---

 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

<img width="559" height="321" alt="image" src="https://github.com/user-attachments/assets/aa41486b-0ccb-43e8-9312-a3cc10ad29ce" />



## MODEL GRAPH

<img width="538" height="431" alt="image" src="https://github.com/user-attachments/assets/8831b5c5-fd65-496a-a8c6-20526022ef70" />


---

## DESIGN

<img width="534" height="488" alt="image" src="https://github.com/user-attachments/assets/69f1d484-14e7-43b2-ab34-29081406e9a8" />



## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
<img width="573" height="400" alt="image" src="https://github.com/user-attachments/assets/ee2a2920-7e0a-420a-ad72-ee02e58404d4" />


---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="688" height="498" alt="image" src="https://github.com/user-attachments/assets/8e0d2f80-10a4-4fe1-b564-a23c5c50ed92" />


---

 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

<img width="492" height="299" alt="image" src="https://github.com/user-attachments/assets/6314107a-4c72-41dd-bd5d-bbb0872f59a1" />


## MODEL GRAPH

<img width="527" height="500" alt="image" src="https://github.com/user-attachments/assets/c97aa704-6cba-48d8-8579-a21aef03d3ef" />


---

## DESIGN

DESIGN: BAND PASS FILTER

<img width="575" height="814" alt="image" src="https://github.com/user-attachments/assets/b8db56fb-4dea-4eee-b42b-1a8d893e2f5c" />



## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

		
<img width="586" height="516" alt="image" src="https://github.com/user-attachments/assets/c72f3f42-0bad-4834-ba40-26cfb918bed8" />


---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="638" height="489" alt="image" src="https://github.com/user-attachments/assets/8c0ed6e8-1ede-40a4-ab18-cb88dd58a879" />

---
##RESULT:
<img width="526" height="492" alt="image" src="https://github.com/user-attachments/assets/05c54703-5f59-439d-8e1c-7a15cd139243" />

---

   
