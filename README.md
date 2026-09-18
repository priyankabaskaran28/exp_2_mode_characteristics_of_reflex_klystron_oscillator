# exp_2_mode_characteristics_of_reflex_klystron_oscillator

# Experiment 2 — Mode Characteristics of Reflex Klystron
---
## Aim

To study the mode characteristics of a reflex klystron and hence determine the mode number, transit time, electronic tuning range (ETR) and electronic tuning sensitivity (ETS).

## Equipment and Components

1. Klystron power supply MTI KP 503
2. Klystron tube / 2K25
3. Isolator MTI/NVIS-204
4. Frequency meter MTI/NVIS-205A
5. Variable attenuator MTI/NVIS-206
6. Detector mount MTI/NVIS-209
7. Waveguide stands MTI/NVIS
8. VSWR meter MTI VS 501/NVIS
9. Cathode ray oscilloscope Scientech-801C

## Experimental Setup

<img width="870" height="295" alt="image" src="https://github.com/user-attachments/assets/9a3dedfa-312f-4f45-ab30-f3a8f4bd1639" />

<img width="701" height="292" alt="image" src="https://github.com/user-attachments/assets/7d3952ea-2bb0-43d7-b35c-2a6ffff002c7" />

---

## Theory

The reflex klystron is a microwave tube used as the microwave source in the lab. It uses **velocity modulation** to convert a continuous electron beam into microwave power; its oscillation frequency can be varied over a wide band and it can be pulse- and frequency-modulated.

Electrons emitted from the cathode are accelerated through the positive resonator grid towards the reflector. The reflector is negative with respect to the cathode, so it retards and finally reflects the electrons, which turn back through the resonator grids. When the klystron oscillates a high field exists between the resonator grids: an electron crossing the gap is either accelerated or retarded as the gap voltage changes in amplitude. Accelerated electrons leave at increased velocity, retarded electrons at reduced velocity, so the electrons need different times to return — different transit times — and the returning electrons group together in **bunches**. This variation of electron velocity is velocity modulation.

As the bunches pass back through the resonator grids they interact with the gap voltage. If they arrive when the grid voltage slows them down, energy is delivered to the resonator and the klystron oscillates. The strongest oscillation occurs when the transit time in the reflector region equals **n + ¾** cycles of the resonator frequency, where *n* is an integer including zero. If the bunches arrive when the field accelerates them, energy is removed from the resonator and no oscillation occurs.

<img width="551" height="376" alt="image" src="https://github.com/user-attachments/assets/f46fd238-b33e-4b3e-a345-7f672af0752e" />

### Mechanical and Electronic Tuning

* **Mechanical tuning** changes the width of the cavity, i.e. its effective capacitance, and hence the resonant frequency. The output power stays essentially the same.
* **Electronic tuning** changes the repeller voltage, which changes the output frequency — but the output power also changes. It is quantified by the **electronic tuning sensitivity (ETS)**, obtained as the slope of the frequency characteristic of the mode.

---

## Procedure

1. Connect the components and equipment as shown in Fig. (A).
2. Keep the control knobs of the klystron power supply as follows:

   | Control | Setting |
   |---|---|
   | Mode switch | AM |
   | Beam voltage knob | Fully anti-clockwise |
   | Repeller voltage knob | Fully clockwise |
   | Meter switch | Beam current |

3. Rotate the frequency meter to one side (**rotate the frequency meter very slowly**).
4. Switch on the klystron power supply, the VSWR meter/CRO and the cooling fan for the klystron tube. Wait 1–2 minutes for the klystron to respond.
5. With the cathode voltage knob at minimum the beam voltage is about 235–300 V. Observe the beam current by switching the meter to the beam-current position. **The beam current must not exceed 30 mA** — try to set it to about 20 mA by adjusting the beam voltage knob.
6. Change the meter switch to the repeller/reflector voltage position.
7. Decreasing the reflector/repeller voltage, record the output power and the frequency.
8. To measure frequency, set the mode switch to AM and observe the output on the CRO. Use the AM amplitude and frequency controls and the oscilloscope front-panel controls to get a clear display. Rotate the frequency meter and watch for a dip in the output; note the corresponding frequency.
9. Switch on the beam voltage and rotate the beam voltage knob clockwise slowly while watching the VSWR meter; set it for maximum deflection.
10. Change the repeller voltage slowly and set it for maximum deflection on the VSWR meter.
11. Rotate the frequency meter knob slowly and stop where the output on the VSWR meter is lowest.
12. Read the frequency directly on the frequency meter, between the two horizontal fine marks.
13. Change the repeller voltage and read the power and frequency for each repeller voltage.

## Observation

### Observation Table

**Operating Parameters:**

* Beam Voltage ($V_{\text{beam}}$) = $280\text{ V}$
* Beam Current ($I_{\text{beam}}$) = $20\text{ mA}$

| S.No | Mode Index ($n$) | Mode Number ($N = n + \frac{3}{4}$) | Repeller Voltage $\Vert{}V_{\text{rep}}\Vert{}$ (V) | Output Power $P_{\text{out}}$ (mW) | Resonant Frequency $f_0$ (GHz) | Half-Power Frequencies $f_1 - f_2$ (GHz) | Electronic Tuning Range $\text{ETR}$ (MHz) | Voltage Difference $\Delta V$ (V) | Electronic Tuning Sensitivity $\text{ETS}$ (MHz/V) | Transit Time $T_0$ (ns) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | 1 | $1\frac{3}{4}\ (1.75)$ | 200 | 27.5 | 9.170 | 9.145 – 9.208 | 63 | 18 | 3.50 | 0.191 |
| 2 | 2 | $2\frac{3}{4}\ (2.75)$ | 138 | 20.4 | 9.172 | 9.142 – 9.210 | 68 | 15 | 4.53 | 0.300 |
| 3 | 3 | $3\frac{3}{4}\ (3.75)$ | 90 | 12.2 | 9.175 | 9.138 – 9.215 | 77 | 13 | 5.92 | 0.409 |

---

### Detailed Point-by-Point Readings for Graph Plotting

#### Mode 1 ($N = 1\frac{3}{4}$)

* Peak Repeller Voltage: $-200\text{ V}$
* Peak Output Power: $27.5\text{ mW}$

| Repeller Voltage $\Vert{}V_{\text{rep}}\Vert{}$ (V) | Output Power $P_{\text{out}}$ (mW) | Frequency (GHz) |
| --- | --- | --- |
| 180 | 0.0 | — |
| 185 | 8.2 | 9.130 |
| 191 | 13.8 (Half Power) | 9.145 ($f_1$) |
| 195 | 22.0 | 9.158 |
| 200 | 27.5 (Peak) | 9.170 ($f_0$) |
| 205 | 21.6 | 9.186 |
| 209 | 13.8 (Half Power) | 9.208 ($f_2$) |
| 215 | 6.5 | 9.220 |
| 220 | 0.0 | — |

#### Mode 2 ($N = 2\frac{3}{4}$)

* Peak Repeller Voltage: $-138\text{ V}$
* Peak Output Power: $20.4\text{ mW}$

| Repeller Voltage $\Vert{}V_{\text{rep}}\Vert{}$ (V) | Output Power $P_{\text{out}}$ (mW) | Frequency (GHz) |
| --- | --- | --- |
| 120 | 0.0 | — |
| 125 | 6.0 | 9.128 |
| 130 | 10.2 (Half Power) | 9.142 ($f_1$) |
| 134 | 16.5 | 9.155 |
| 138 | 20.4 (Peak) | 9.172 ($f_0$) |
| 142 | 15.8 | 9.188 |
| 145 | 10.2 (Half Power) | 9.210 ($f_2$) |
| 150 | 4.8 | 9.224 |
| 155 | 0.0 | — |

#### Mode 3 ($N = 3\frac{3}{4}$)

* Peak Repeller Voltage: $-90\text{ V}$
* Peak Output Power: $12.2\text{ mW}$

| Repeller Voltage $\Vert{}V_{\text{rep}}\Vert{}$ (V) | Output Power $P_{\text{out}}$ (mW) | Frequency (GHz) |
| --- | --- | --- |
| 75 | 0.0 | — |
| 80 | 3.5 | 9.122 |
| 83 | 6.1 (Half Power) | 9.138 ($f_1$) |
| 87 | 10.0 | 9.156 |
| 90 | 12.2 (Peak) | 9.175 ($f_0$) |
| 93 | 9.8 | 9.192 |
| 96 | 6.1 (Half Power) | 9.215 ($f_2$) |
| 100 | 2.8 | 9.230 |
| 105 | 0.0 | — |

---

### Inferences from Observations

* **Mode Number & Repeller Voltage:** As the magnitude of repeller voltage decreases ($200\text{ V} \rightarrow 138\text{ V} \rightarrow 90\text{ V}$), the retarding electric field becomes weaker, requiring electrons to take more cycles to return; hence the mode number increases ($N = 1.75 \rightarrow 2.75 \rightarrow 3.75$).
* **Power Variation:** The lowest-order mode ($N = 1\frac{3}{4}$) produces the highest output power ($27.5\text{ mW}$). Higher-order modes deliver less power because the electron bunches disperse more due to space-charge repulsion during their longer transit times.
* **Tuning Sensitivity (ETS):** Higher-order modes have higher tuning sensitivity ($5.92\text{ MHz/V}$ for Mode 3 vs. $3.50\text{ MHz/V}$ for Mode 1), meaning smaller shifts in repeller voltage produce larger frequency adjustments.

## Graph
<img width="696" height="423" alt="image" src="https://github.com/user-attachments/assets/1f01c9ca-3b97-443d-b579-f073c98cbd41" />

## Precautions

1. Check the connections before switching on the kit.
2. Keep all knobs at their minimum positions before switching on the VSWR meter / klystron power supply.
3. On the klystron power supply the **HT must be OFF** before switching on the mains supply.
4. The beam knob must be fully anti-clockwise and the repeller voltage knob fully clockwise.
5. Switch on the mains and allow some warm-up time for accurate readings.
6. Make all connections properly.
7. Do not look directly into the waveguide.
8. After the experiment, switch off the mains and return all knobs to their minimum positions before leaving the bench.
9. If the mains supply fails mid-experiment, return to the initial condition — all knobs at minimum — and switch off the main switches.
10. Do not increase the repeller voltage beyond −70 V; it should stay between −70 V and 270 V.

## Conclusion
Thus the experiment is verified .
