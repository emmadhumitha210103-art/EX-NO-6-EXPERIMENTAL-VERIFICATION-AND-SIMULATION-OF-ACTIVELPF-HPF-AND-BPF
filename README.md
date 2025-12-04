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

<img width="1280" height="615" alt="image" src="https://github.com/user-attachments/assets/996836e4-2f99-45e3-a24f-72db64bec9d7" />


## MODEL GRAPH

<img width="1230" height="841" alt="image" src="https://github.com/user-attachments/assets/1dbf3286-396f-45ad-b283-776c36149b02" />

---

## DESIGN

<img width="1280" height="512" alt="image" src="https://github.com/user-attachments/assets/3059c094-fa6c-4e41-bfad-699662f700ce" />
<img width="1065" height="431" alt="image" src="https://github.com/user-attachments/assets/479c7f12-f851-416c-8b9b-f93fa659fcf8" />


Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

<img width="1280" height="927" alt="image" src="https://github.com/user-attachments/assets/aa81494b-82fc-45cd-8b10-7e4ee01ce438" />


---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="722" height="985" alt="image" src="https://github.com/user-attachments/assets/6a38a4e1-8cd5-4b67-a4b2-dd13689aacc9" />

<img width="1280" height="1023" alt="image" src="https://github.com/user-attachments/assets/83ed5b68-1413-489f-b78f-dfc3f57c2670" />


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

<img width="1280" height="620" alt="image" src="https://github.com/user-attachments/assets/0acc98ff-9d4d-4338-af66-c34c44af0186" />


## MODEL GRAPH

<img width="1184" height="635" alt="image" src="https://github.com/user-attachments/assets/89b6f0cf-9673-4078-ae9b-5b9e1b87f072" />

---

## DESIGN

<img width="1280" height="512" alt="image" src="https://github.com/user-attachments/assets/9e02ae3e-1716-4fc9-a26e-e0a21cae9fad" />


<img width="1065" height="431" alt="image" src="https://github.com/user-attachments/assets/441f1a80-b8a0-401d-bbd0-d8bdd76519e0" />


Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

<img width="1280" height="861" alt="image" src="https://github.com/user-attachments/assets/8104c658-133d-4407-977f-09eba6fa480b" />

		

---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="729" height="1005" alt="image" src="https://github.com/user-attachments/assets/cc178b82-a74f-4fca-be02-24f13d59497a" />

<img width="1280" height="1035" alt="image" src="https://github.com/user-attachments/assets/35ccb02e-87ca-4247-9980-ac452a0a93a9" />



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

<img width="1280" height="662" alt="image" src="https://github.com/user-attachments/assets/7dc7fe42-8ba2-43d5-9731-407c1c0e7efa" />

## MODEL GRAPH

<img width="1280" height="759" alt="image" src="https://github.com/user-attachments/assets/1e1e1274-67da-4543-9482-93eb2ed554bb" />


---

## DESIGN

DESIGN: BAND PASS FILTER

<img width="1088" height="1280" alt="image" src="https://github.com/user-attachments/assets/8bb575c2-57b9-4eb1-b6b4-bebad2a2f58e" />


Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

<img width="1280" height="914" alt="image" src="https://github.com/user-attachments/assets/4cb886c3-5ba8-4fd4-a12b-13b2058875b9" />
		

---

## OUT PUT WAVEFORM AND DISCUSSION 
<img width="729" height="1005" alt="image" src="https://github.com/user-attachments/assets/06046e68-b789-425c-b3b2-35a4e26b57bc" />

<img width="1280" height="1034" alt="image" src="https://github.com/user-attachments/assets/fe5b3a0a-e7d9-42b2-9e7c-cc00498452c5" />


---
##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   
