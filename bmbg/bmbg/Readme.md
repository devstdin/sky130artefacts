01.09.2024, 15:23:46

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
| Mean Reference Voltage | 1 / 1.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.19072000000003,10.0,126.25824000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.19072000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.25824000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.342 / 1.4 | V | 1242/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.109 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.214934912,10.0,19.747338239999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.214934912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.747338239999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.075 / 250.0 | mV | 1238/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.103 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.999359999999996,10.0,125.85324000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="39.999359999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.85324000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.341 / 1.4 | V | 1242/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -148.958 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.06252,10.0,84.03459000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.06252" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.03459000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 150.576 / 1200.0 | uV/°C | 1250/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.413 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="27.835200000000054,10.0,96.18336,10.0" style="stroke:green;stroke-width:2" /><circle cx="27.835200000000054" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.18336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.293 / -70.0 | uA | 1241/100.0%/0.0%/0.0% |  |

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
| Mean Reference Voltage | 1 / 1.124 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.58923999999998,10.0,135.26112,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.58923999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.26112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.367 / 1.4 | V | 1243/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.573 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.298002624,10.0,110.38293119999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.298002624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.38293119999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.643 / 25.0 | mV | 1240/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.124 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.789040000000014,10.0,123.10968000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.789040000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.10968000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.334 / 1.4 | V | 1243/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -5.177 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.3619,10.0,116.263668,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.3619" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="116.263668" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.462 / 20.0 | mV/V | 1243/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.151 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.87615999999997,10.0,120.14015999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.87615999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.14015999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.596 / -70.0 | uA | 1241/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -110.262 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.786707692307692,10.0,87.75906461538462,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.786707692307692" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.75906461538462" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -43.481 / 10 | dB | 1236/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.177 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.6511792,10.0,95.2942752,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.6511792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.2942752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.228 / 20 | dB | 1236/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.06724000000004,10.0,88.33872000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.06724000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.33872000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.237 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.611 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.65575744,10.0,10.26250752,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.65575744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.26250752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.609 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.224 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.389888,10.0,70.94438400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.389888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.94438400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.236 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / 24.924 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.49541119999999,10.0,80.65119840000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.49541119999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.65119840000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.187 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.33 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.43392000000001,10.0,106.66847999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.43392000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.66847999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.201 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.128 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.98676000000005,10.0,125.42591999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.98676000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.42591999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.34 / 1.4 | V | 1217/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.276 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.734848704,10.0,29.53558272,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.734848704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.53558272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 46.069 / 250.0 | mV | 1234/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.131 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.298239999999986,10.0,124.29552000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.298239999999986" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.29552000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.337 / 1.4 | V | 1217/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -130.13 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.1922,10.0,92.929374,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.1922" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="92.929374" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 298.823 / 1200.0 | uV/°C | 1249/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.299 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="28.931519999999985,10.0,95.52671999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="28.931519999999985" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.52671999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.362 / -70.0 | uA | 1191/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.82352000000003,10.0,88.53132000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.82352000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.53132000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.238 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.855 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.44452928,10.0,54.87303936,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.44452928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="54.87303936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.006 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.221 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.55987199999998,10.0,70.47811200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.55987199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.47811200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.234 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.258 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.1280368,10.0,100.716636,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.1280368" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.716636" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 7.144 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.226 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.11663999999999,10.0,126.83423999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.11663999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.83423999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.201 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.126 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,22.306785832439218,17,22.306785832439218,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.653392916219609,10.0,12.653392916219609,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.064888900508715,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="9.064888900508715" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.983 / 1.4 | V | 1248/94.4712%/5.5288%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.566 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.845419505377925,17,5.845419505377925,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.422709752688963,10.0,4.422709752688963,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.019128806659839,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.019128806659839" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 4258.241 / 25.0 | mV | 1250/94.16%/5.84%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 0.76 | <svg height="20" width="150"><polyline points="16.67011465098146,3,16.67011465098146,17,39.48757052762712,17,39.48757052762712,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="28.07884258930429,10.0,28.07884258930429,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.285 / 1.4 | V | 1248/94.391%/5.609%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -4.894 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.4581737049670895,17,5.4581737049670895,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.229086852483545,10.0,4.229086852483545,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.928337903288789,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.928337903288789" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2323.203 / 20.0 | mV/V | 1249/94.3155%/5.6845%/0.0% |  |
| Max. Supply Current | -100.0 / -23221.3 | <svg height="20" width="150"><polyline points="95.3191574166693,3,95.3191574166693,17,97.44153698540029,17,97.44153698540029,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="96.3803472010348,10.0,96.3803472010348,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 12078.71 / -70.0 | uA | 1242/94.686%/5.314%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:42 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:44 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 3.3V":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:42 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 3.3V":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:43 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ff_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ff_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ss_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/hh_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/tt_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_2/ll_mm/dc.csv Index:36 te:20.0 <br>
</details><br>


## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.322 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.1843856,10.0,29.816328,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.1843856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.816328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.622 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.627 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.8043704,10.0,7.199415392000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.8043704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.199415392000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.764 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -82.351 | <svg height="20" width="150"><polyline points="10.994087520749174,3,10.994087520749174,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.9970437603746,10.0,78.9970437603746,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,28.605493127687343,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="28.605493127687343" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -74.82 / -40 | dB | 5/80.0%/20.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 8.786 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="93.17365439999999,10.0,100.42968,10.0" style="stroke:green;stroke-width:2" /><circle cx="93.17365439999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.42968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.298 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10 Hz":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.3_bmbg_ext/batch_0/ff/ac_psrr.csv Index:0 <br>
</details><br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -111.169 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.782030769230774,10.0,111.14820923076924,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.782030769230774" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.14820923076924" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -22.366 / 10 | dB | 1218/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 8.139 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.0668928,10.0,104.904432,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.0668928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.904432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.23 / 20 | dB | 1217/100.0%/0.0%/0.0% |  |

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
