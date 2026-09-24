# SSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB-T1-M4-ODD
# SSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** The baseband signal that will be modulated.
* **Carrier Signal:** A high-frequency signal used for modulation.
* **Analytic Signal:** Constructed using the Hilbert transform to get the in-phase and quadrature components.

### 3. SSBSC Modulation:

* **Modulated Signal:** Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

### 4. SSBSC Demodulation:

* **Mixing:** Multiply the SSBSC signal with the carrier to retrieve the message signal.
* **Low-pass Filtering:** Apply a low-pass filter to remove high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 32 45 PM" src="https://github.com/user-attachments/assets/af107cab-f518-41e8-a372-91aba903e11a" />

---

## PROGRAM 
<img width="1599" height="985" alt="WhatsApp Image 2026-09-24 at 3 33 02 PM" src="https://github.com/user-attachments/assets/67d70ac3-f2ba-4de9-928e-ef1cec0969ef" />
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 33 11 PM" src="https://github.com/user-attachments/assets/90d8211e-c6b7-4aad-9600-202a63209208" />

## GRAPH

<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 33 17 PM" src="https://github.com/user-attachments/assets/38bd3c9d-e102-47df-972d-8f36c8988f20" />

## RESULT 

<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 33 25 PM" src="https://github.com/user-attachments/assets/8c247f45-7626-4ed1-9a77-b802c59381f8" />

## MARK ALLOCATION 
<img width="899" height="1599" alt="WhatsApp Image 2026-09-24 at 3 33 31 PM" src="https://github.com/user-attachments/assets/c9706c0e-ed95-4c61-aabc-b63c0725bd72" />

