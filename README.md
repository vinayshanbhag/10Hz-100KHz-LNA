# 10Hz-100KHz-LNA
Low noise amplifier for ripple and noise measurements (10Hz-100Khz)
based on <a href="https://github.com/vinayshanbhag/10Hz-100KHz-LNA/blob/main/an-83.pdf">AN-83</a>

### Schematic
![image](https://github.com/user-attachments/assets/9c2298d6-a2c3-4b30-b1ca-b224c759b0e1)

### Impulse response (spice model)
<img src="https://github.com/vinayshanbhag/10Hz-100KHz-LNA/blob/main/impulse-response-spice.png" width=900/>

### Frequency response (spice model)
<img src="https://github.com/vinayshanbhag/10Hz-100KHz-LNA/blob/main/freq-response-spice.png" width=900/>

### Frequency response (measured)
<img src="https://github.com/vinayshanbhag/10Hz-100KHz-LNA/blob/main/freq-response-measured.png" width=900/>

### Input referred noise (spice model)
<img src="https://raw.githubusercontent.com/vinayshanbhag/10Hz-100KHz-LNA/refs/heads/main/input-referred-noise-spice.png" width="900"/>

### Input referred noise (measured)
<img src="https://raw.githubusercontent.com/vinayshanbhag/10Hz-100KHz-LNA/refs/heads/main/noise_short.png" width="900"/>

| Power Supply | Noise spec | Measured (HP34401A) |
|--------------|------------|---------------------|
| HP6114A      | 40uVrms at any line voltage and under any load condition within rating   | 48uVrms   @25V      |
| HP33120A     | NA         | 72uVrms   @10V DC out     |
| HP6203B      | <200uVrms  | 128uVrms  @5V       |
| TPS4000      | <0.5mVrms  | 0.1mVrms  @20V      |
