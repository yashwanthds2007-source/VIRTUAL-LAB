# VIRTUAL-LAB
# Virtual Lab Report  
## Characteristics and Parameters of Op-Amp (IC 741)

---

## Student Details

- **Name:** Yashawanth D S  
- **USN:** 4NI25EC426  
- **Course:** Linear Integrated Circuits  
- **Semester:** IV  
- **Section:** C  
- **Guide:** Dr. Remya Jayachandran  
- **Department:** Electronics and Communication Engineering  
- **Academic Year:** 2025-26  

---

# 1. Aim

To study and measure the following parameters of IC 741:

- Input Bias Current (Inverting)
- Input Bias Current (Non-Inverting)
- Input Offset Current
- Input Offset Voltage
- Slew Rate

---

# 2. Block Diagram of Op-Amp



The Op-Amp consists of:

- Differential Input Stage  
- Intermediate Stage  
- Level Translator  
- Output Stage (Push-Pull)

---

# 3. Schematic Symbol



- (+) → Non-inverting input  
- (−) → Inverting input  

---

# 4. IC 741 Pin Configuration



| Pin | Description |
|------|------------|
| 1 | Offset Null |
| 2 | Inverting Input |
| 3 | Non-Inverting Input |
| 4 | V- (Negative Supply) |
| 5 | Offset Null |
| 6 | Output |
| 7 | V+ (Positive Supply) |
| 8 | No Connection |

---

# 5. Ideal Op-Amp Characteristics

- Infinite Gain (A → ∞)
- Infinite Input Resistance (Ri → ∞)
- Zero Output Resistance (Ro = 0)
- Infinite Bandwidth
- Infinite CMRR
- Infinite Slew Rate
- Zero Offset Voltage

---

# 6. Measurement of Parameters

---

## 6.1 Input Offset Voltage (Vio)

<img width="1059" height="543" alt="input offset voltage" src="https://github.com/user-attachments/assets/8ce181ed-7ab1-441e-855f-a6b8a055e0ec" />

An ideal op-amp gives zero output when both inputs are equal.  
Practical IC 741 requires a small voltage difference called **Input Offset Voltage (Vio)**.

### Formula:

\[
V_{out} = \left(1 + \frac{R_f}{R_1}\right) V_{io}
\]

\[
V_{io} = \frac{V_{out}}{\left(1 + \frac{R_f}{R_1}\right)}
\]

---

## 6.2 Input Offset Current (Iio)

<img width="1060" height="530" alt="input offset current" src="https://github.com/user-attachments/assets/3c2ea01b-e515-428d-a355-b6aa759a9f0b" />


Difference between bias currents of two inputs.

### Formula:

\[
V_o = I_{io} \times R_f
\]

\[
I_{io} = \frac{V_o}{R_f}
\]

---

## 6.3 Inverting Bias Current (IB1)

<img width="1075" height="545" alt="inverting bias current" src="https://github.com/user-attachments/assets/a7535f63-f404-4bc5-8279-97bea6c2cac9" />


### Formula:

\[
V_o = I_{B1} \times R_f
\]

\[
I_{B1} = \frac{V_o}{R_f}
\]

---

## 6.4 Non-Inverting Bias Current (IB2)

<img width="1057" height="536" alt="noninverting bias current" src="https://github.com/user-attachments/assets/0056c71d-fcde-4f76-b381-93fbcb53073d" />


### Formula:

\[
I_{B2} = \frac{V_o}{R_1}
\]

---

## 6.5 Slew Rate (SR)

<img width="1066" height="536" alt="slew rate " src="https://github.com/user-attachments/assets/66dd630a-595c-4e7e-838a-7702ea2405fd" />

<img width="407" height="547" alt="slew rate wave" src="https://github.com/user-attachments/assets/38c3dcd2-d62a-4843-8aa3-2c2d51548059" />

Slew Rate is the maximum rate of change of output voltage.

### Formula:

\[
S.R = 2\pi f_{max} V_m
\]

Where:

- \( f_{max} \) = Frequency at distortion
- \( V_m \) = Peak output voltage

Unit: V/µs

---

# 7. Conclusion

The following parameters of IC 741 were studied and measured:

- Input Offset Voltage  
- Input Offset Current  
- Inverting Bias Current  
- Non-Inverting Bias Current  
- Slew Rate  

The practical values were observed and compared with theoretical calculations.

---
