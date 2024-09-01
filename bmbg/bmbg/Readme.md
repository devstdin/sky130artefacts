01.09.2024, 12:45:59

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![bmbg](resources/bmbg.png "bmbg")

<br>

[🔗 Schematics](bmbg_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](bmbg_bmbg_netgen_comp.out)<br>

# SPECIFICATIONS

## Reference Voltage Curvature vs Temperature <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.21 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.74004,10.0,83.93267999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.74004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.93267999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.225 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.035 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.324389824000001,10.0,9.33704256,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.324389824000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.33704256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.002 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.213 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.39555200000001,10.0,67.90454399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.39555200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.90454399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.225 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -24.66 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.52037,10.0,77.5885452,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.52037" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.5885452" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.142 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.533 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.48223999999996,10.0,106.07711999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.48223999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.07711999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.263 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.07140000000003,10.0,120.05184000000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.07140000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.05184000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.325 / 1.4 | V | 249/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.447 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.4097311999999995,10.0,17.8225248,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.4097311999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.8225248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.734 / 250.0 | mV | 247/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.097 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="37.931520000000006,10.0,120.14616000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="37.931520000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.14616000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.325 / 1.4 | V | 249/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -166.096 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.03424000000001,10.0,84.32729400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.03424000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.32729400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 155.455 / 1200.0 | uV/°C | 250/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -81.502 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.57888000000009,10.0,96.86591999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.57888000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.86591999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.222 / -70.0 | uA | 248/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.7954,10.0,83.56835999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.7954" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.56835999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.224 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.614 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.05702016,10.0,52.31214336,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.05702016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="52.31214336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.561 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.95043199999997,10.0,67.00598399999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.95043199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.00598399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.176 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.8344856,10.0,99.5339532,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.8344856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.5339532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 6.815 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.322 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.65535999999999,10.0,126.53855999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.65535999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.53855999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.263 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.093 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.330960000000026,10.0,125.37084000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.330960000000026" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.37084000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.34 / 1.4 | V | 249/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.697 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.014240192,10.0,91.0777152,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.014240192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.0777152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 15.291 / 25.0 | mV | 249/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.093 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.48,10.0,123.41171999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.48" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.41171999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.334 / 1.4 | V | 249/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -5.21 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.243064,10.0,110.49591,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.243064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.49591" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.86 / 20.0 | mV/V | 249/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -82.297 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.97535999999998,10.0,122.63855999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.97535999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.63855999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.075 / -70.0 | uA | 249/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 MHz | -10 / 6.81 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.68907999999999,10.0,91.2247344,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.68907999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.2247344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.38 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10 Hz":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.3_bmbg/batch_0/ff/ac_psrr.csv Index:0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.3_bmbg/batch_0/hh/ac_psrr.csv Index:0 <br>
</details><br>


## PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -92.903 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="33.014916923076925,10.0,87.56123076923078,10.0" style="stroke:green;stroke-width:2" /><circle cx="33.014916923076925" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.56123076923078" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -43.66 / 10 | dB | 247/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.048 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.0299728,10.0,95.0635104,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.0299728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.0635104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.18 / 20 | dB | 247/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.06724000000004,10.0,88.33872000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.06724000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.33872000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.237 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.611 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.65575744,10.0,10.26250752,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.65575744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.26250752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.609 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.224 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.389888,10.0,70.94438400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.389888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.94438400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.236 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / 24.924 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.49541180000001,10.0,80.65119840000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.49541180000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.65119840000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.187 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.33 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.43392000000001,10.0,106.66847999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.43392000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.66847999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.201 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.124 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.76060000000004,10.0,138.22788000000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.76060000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="138.22788000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.376 / 1.4 | V | 243/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.057 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.608592384,10.0,23.743050240000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.608592384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="23.743050240000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 36.012 / 250.0 | mV | 247/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.128 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.92376000000003,10.0,119.67888000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.92376000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.67888000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.324 / 1.4 | V | 243/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -107.623 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.54262,10.0,89.399526,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.54262" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.399526" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 239.992 / 1200.0 | uV/°C | 249/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -81.507 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.528959999999984,10.0,95.97599999999993,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.528959999999984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.97599999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.315 / -70.0 | uA | 237/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.82352000000003,10.0,88.53132000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.82352000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.53132000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.238 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.855 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.44452928,10.0,54.87303936,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.44452928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="54.87303936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.006 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.221 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.55987199999998,10.0,70.47811200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.55987199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.47811200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.234 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.258 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.1280332,10.0,100.716636,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.1280332" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.716636" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 7.144 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.226 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.11663999999999,10.0,126.83423999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.11663999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.83423999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.201 / -70.0 | uA | 14/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.134 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,22.317333483579258,17,22.317333483579258,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.658666741789629,10.0,12.658666741789629,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.450009356833405,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="9.450009356833405" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.982 / 1.4 | V | 250/93.6%/6.4%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.685 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,6.332689693570217,17,6.332689693570217,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.666344846785108,10.0,4.666344846785108,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.036501976230739,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.036501976230739" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2701.304 / 25.0 | mV | 250/93.2%/6.8%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.135 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,28.212158563467224,17,28.212158563467224,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="15.606079281733612,10.0,15.606079281733612,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.477651347362263,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="11.477651347362263" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.285 / 1.4 | V | 250/93.6%/6.4%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -3.756 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,8.655114034490895,17,8.655114034490895,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.827557017245447,10.0,5.827557017245447,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.296493740937459,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="5.296493740937459" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 998.547 / 20.0 | mV/V | 250/93.6%/6.4%/0.0% |  |
| Max. Supply Current | -100.0 / -22821.4 | <svg height="20" width="150"><polyline points="144.70037030184898,3,144.70037030184898,17,146.89010381778795,17,146.89010381778795,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="145.79523705981848,10.0,145.79523705981848,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -52.624 / -70.0 | uA | 249/93.9759%/6.0241%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:8 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:8 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 3.3V":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:8 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 3.3V":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:8 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:7 te:20.0 <br>
</details><br>


## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.322 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.1843856,10.0,29.816328,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.1843856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.816328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.622 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.627 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.8043704,10.0,7.199415104,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.8043704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.199415104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.764 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -77.88 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,75.04399249330116,17,75.04399249330116,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.02199624665058,10.0,39.02199624665058,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.817611162220039,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="6.817611162220039" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -0.049 / -40 | dB | 5/80.0%/20.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / -0.049 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.76579504,10.0,100.429296,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.76579504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.429296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.298 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10 Hz":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.3_bmbg_ext/batch_0/ff/ac_psrr.csv Index:0 <br>
</details><br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -104.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.867938461538458,10.0,110.88070153846155,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.867938461538458" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.88070153846155" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -22.608 / 10 | dB | 241/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 8.252 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.6089712,10.0,103.35537599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.6089712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.35537599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.907 / 20 | dB | 240/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## Voltage Curvature vs Temperature Performance<br>

| ![xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59](xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance<br>

| ![xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6](xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba.png "") |
| :-- |
|  |
<br>
