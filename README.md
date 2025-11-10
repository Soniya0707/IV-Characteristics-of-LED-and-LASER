# EX.NO: 3 — Experimental Verification of IV Characteristics of LED and LASER

---

## AIM
To study the IV characteristics of a fiber optic LED and plot the graph of **forward current vs output optical energy**, and also to study the **photo detector response**.

---

## EQUIPMENTS REQUIRED
- Link-B Kit with power supply  
- FCL-01 & FCL-02 modules  
- Patch chords  
- 20 MHz Dual Channel Oscilloscope  
- 1 MHz Function Generator  
- 1 Meter Fiber Cable  
- Jumper to crocodile wires  

---

## THEORY
In an optical fiber communication system, an **electrical signal** is first converted into an **optical signal** with the help of an electro-optical (E/O) device such as an LED.  
After the optical signal is transmitted through the optical fiber, it is converted back into its original electrical form using an **opto-electrical (O/E)** device such as a photo detector.

Different LED fabrication technologies lead to variations in output power, wavelength, and conversion efficiency.  
Key LED parameters include:
- **Peak wavelength of emission**
- **Conversion efficiency** (power launched into fiber per forward current)
- **Rise and fall times** (define frequency limit)
- **Maximum forward current and voltage**

Photodetectors (like photodiodes) are characterized by:
- **Response time**
- **Wavelength sensitivity**
- **Responsivity (A/W)**

In optical communication, LEDs and LASERs are used as sources. LEDs show a linear optical output vs forward current over a certain operating region, making them suitable for intensity modulation and analog transmission.  
**Numerical Aperture (NA)** defines the acceptance cone of the fiber — light entering within this cone is guided by total internal reflection.

---

## PROCEDURE
1. Refer to the block diagram and make the following connections.
2. Keep all switch faults in **OFF** position.
3. Slightly unscrew the cap of **LED SFH756V (660 nm)**, insert the **1-meter fiber**, and tighten the cap.
4. Similarly, connect the other end of the fiber to **Photo Diode SFH250V**.
5. Set jumpers on FCL-01 as:
   - JP1 → short for +12V  
   - JP2 → towards sine wave  
   - JP3 → short for +12V  
   - JP4 → towards TX1  
6. Keep switch **SW2** in **VI** position on FCL-01.
7. Connect voltmeter and ammeter as shown in the block diagram.
8. Switch on the power supply.
9. Rotate potentiometer **P3** slowly (to control LED current). Keep **P4** fully clockwise.
10. Measure **forward current (If)** and **forward voltage (Vf)** for different settings.
11. Plot:
    - **Forward voltage vs forward current (I–V curve)**  
    - **Forward current vs output optical power**
12. Calculate **electrical power = If × Vf**.  
    Given that **at 10 mA → optical power = 200 µW**, efficiency ≈ **1.15%**.
13. Using this efficiency, compute optical power for all readings.
14. Measure detector current and plot **receiver current vs optical power**.
15. Repeat for LED and LASER combinations if required.

---

## TABULATION

| Forward Voltage (Vf) | Forward Current (If) (mA) | Electrical Power (mW) | Optical Power (µW) | Detector Current (µA) |
|----------------------:|--------------------------:|----------------------:|------------------:|---------------------:|
| 1.50 | 0  | 0.00  | 0.00  | 0.00 |
| 1.60 | 2  | 3.20  | 36.8  | 16.6 |
| 1.65 | 4  | 6.60  | 75.9  | 34.1 |
| 1.68 | 6  | 10.1  | 115.9 | 52.1 |
| 1.72 | 8  | 13.8  | 157.8 | 71.0 |
| 1.75 | 10 | 17.5  | 200.0 | 90.0 |
| 1.78 | 12 | 21.4  | 244.2 | 110.0 |
| 1.83 | 15 | 27.4  | 312.9 | 141.0 |
| 1.88 | 18 | 33.8  | 385.3 | 173.0 |
| 1.92 | 20 | 38.4  | 438.6 | 197.0 |

---

##  MODEL GRAPH

### IV Characteristics of LED

---

## RESULT
- The **IV characteristic** of the LED shows the expected forward conduction behavior.  


