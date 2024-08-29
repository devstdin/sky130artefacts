29.08.2024, 19:45:44

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![bmbg](resources/bmbg.png "bmbg")

<br>

[🔗 Schematics](bmbg_sch.pdf)<br>

# LVS
> **FAIL:** LVS-state: Netlists do not match.<br>

[🔗 LVS-report](bmbg_bmbg_netgen_comp.out)<br>

# SPECIFICATIONS

## Reference Voltage Curvature vs Temperature <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.21 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.74004,10.0,83.93267999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.74004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.93267999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.225 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.035 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.32438752,10.0,9.33704256,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.32438752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.33704256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.002 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.213 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.39555200000001,10.0,67.90454399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.39555200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.90454399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.225 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -24.661 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.520358,10.0,77.5886478,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.520358" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.5886478" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.144 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.651 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.34848000000001,10.0,105.45983999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.34848000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.45983999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.327 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.087 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="34.442759999999964,10.0,132.65436000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="34.442759999999964" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="132.65436000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.36 / 1.4 | V | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.678 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.966439296,10.0,20.170168320000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.966439296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.170168320000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.809 / 250.0 | mV | 2471/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.250679999999996,10.0,130.60524000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.250679999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.60524000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.354 / 1.4 | V | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -152.378 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.85731999999999,10.0,86.14134,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.85731999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.14134" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 185.689 / 1200.0 | uV/°C | 2500/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.963 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.553280000000054,10.0,98.01408000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.553280000000054" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="98.01408000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.103 / -70.0 | uA | 2484/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.79504000000003,10.0,83.56835999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.79504000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.56835999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.224 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.75 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.83790336,10.0,52.312154879999994,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.83790336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="52.312154879999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.561 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.95043199999997,10.0,67.00598399999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.95043199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.00598399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.176 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.834104,10.0,99.5373912,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.834104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.5373912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 6.816 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.413 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.218560000000004,10.0,126.22991999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.218560000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.22991999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.327 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.113 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.76244000000001,10.0,127.73100000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.76244000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.73100000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.346 / 1.4 | V | 2481/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.458 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.637057024000001,10.0,121.1061504,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.637057024000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.1061504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.505 / 25.0 | mV | 2480/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.111 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.90203999999997,10.0,127.08732,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.90203999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.08732" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.345 / 1.4 | V | 2481/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -4.585 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.495188000000006,10.0,119.93714400000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.495188000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.93714400000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.483 / 20.0 | mV/V | 2481/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.551 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.95376000000002,10.0,121.65215999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.95376000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.65215999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.281 / -70.0 | uA | 2481/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.063 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.8101584,10.0,29.2364976,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.8101584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.2364976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.22 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.616 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.773733248,10.0,7.156685120000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.773733248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.156685120000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.749 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -85.684 | <svg height="20" width="150"><polyline points="20.915641684014215,3,20.915641684014215,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.95782084200711,10.0,83.95782084200711,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,33.659933411698255,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="33.659933411698255" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -75.957 / -40 | dB | 5/60.0%/40.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.811 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.69360160000001,10.0,91.22933760000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.69360160000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.22933760000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.381 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10 Hz":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.3_bmbg/batch_0/ff/ac_psrr.csv Index:0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.3_bmbg/batch_0/hh/ac_psrr.csv Index:0 <br>
</details><br>


## PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -113.459 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.24541538461538,10.0,108.10349538461539,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.24541538461538" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.10349538461539" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -25.115 / 10 | dB | 2463/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.998 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.7890032,10.0,95.05244640000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.7890032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.05244640000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.178 / 20 | dB | 2460/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.217 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.95728,10.0,86.64528000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.95728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.64528000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.232 / 1.4 | V | 14/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.057 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.336667264000001,10.0,12.272079360000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.336667264000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.272079360000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 16.097 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.92627199999998,10.0,69.78777600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.92627199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.78777600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.232 / 1.5 | V | 14/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -85.737 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.85578600000001,10.0,79.48157220000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.85578600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.48157220000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.693 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.086 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.77056000000006,10.0,108.73535999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.77056000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.73535999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -73.986 / -70.0 | uA | 14/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.084 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,134.06219538278802,17,134.06219538278802,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.53109769139401,10.0,68.53109769139401,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.582366673796223,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="30.582366673796223" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.439 / 1.4 | V | 2437/99.959%/0.041%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.023 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.165306176,10.0,25.873610879999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.165306176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="25.873610879999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 39.711 / 250.0 | mV | 2441/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.122 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.90488000000001,10.0,133.08636,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.90488000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="133.08636" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.361 / 1.4 | V | 2439/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -169.68 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.8192,10.0,91.64373,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.8192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.64373" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 277.396 / 1200.0 | uV/°C | 2475/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.419 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="27.77376000000005,10.0,144.20255999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="27.77376000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="144.20255999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -70.291 / -70.0 | uA | 2392/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ll_mm/dc.csv Index:21 vsup:5.0 <br>
</details><br>


## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.38568000000001,10.0,86.07036,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.38568000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.07036" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.231 / 1.4 | V | 14/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.518 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.26492416,10.0,62.144313600000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.26492416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.144313600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.268 / 25.0 | mV | 14/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.214 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.61961599999998,10.0,68.686464,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.61961599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.686464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.228 / 1.5 | V | 14/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.9 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.44138600000001,10.0,106.36421879999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.44138600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.36421879999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.712 / 20.0 | mV/V | 14/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -90.648 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.88816000000002,10.0,127.86767999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.88816000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.86767999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -73.986 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.113 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,139.55858149773465,17,139.55858149773465,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.27929074886733,10.0,71.27929074886733,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.56004665751536,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="41.56004665751536" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.422 / 1.4 | V | 2441/99.9181%/0.0819%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.938 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.401188864,10.0,122.7389376,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.401188864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.7389376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.788 / 25.0 | mV | 2437/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.113 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.75127999999997,10.0,123.76380000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.75127999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.76380000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.335 / 1.4 | V | 2442/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -3.506 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.380164,10.0,122.19096,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.380164" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.19096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.109 / 20.0 | mV/V | 2441/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -84.006 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.77263999999998,10.0,122.21328000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.77263999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.21328000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.164 / -70.0 | uA | 2460/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_9/hh_mm/dc.csv Index:11 te:20.0 <br>
</details><br>


## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.039881599999998,10.0,29.6575824,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.039881599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.6575824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.512 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.622 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.791592128,10.0,7.1858891840000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.791592128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.1858891840000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.759 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -64.987 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.045360000000024,10.0,66.55980000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.045360000000024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.55980000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.344 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.964 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.22942719999999,10.0,95.65082400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="89.22942719999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.65082400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.302 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -112.816 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.957661538461537,10.0,130.07826092307693,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.957661538461537" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.07826092307693" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -5.277 / 10 | dB | 2454/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.989 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="84.5475984,10.0,99.581328,10.0" style="stroke:green;stroke-width:2" /><circle cx="84.5475984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.581328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.121 / 20 | dB | 2441/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## Voltage Curvature vs Temperature Performance<br>

| ![xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59](xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance<br>

| ![xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6](xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f.png "") |
| :-- |
|  |
<br>
