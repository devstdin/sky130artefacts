29.08.2024, 21:17:52

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![bmbg](resources/bmbg.png "bmbg")

<br>

[🔗 Schematics](bmbg_sch.pdf)<br>

# LVS

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
| Mean Reference Voltage | 1 / 1.085 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="33.58451999999998,10.0,126.64524,10.0" style="stroke:green;stroke-width:2" /><circle cx="33.58451999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.64524" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.343 / 1.4 | V | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.883 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.084565952,10.0,19.03831104,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.084565952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.03831104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 27.844 / 250.0 | mV | 2476/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.09 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="35.233679999999964,10.0,126.99444000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="35.233679999999964" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.99444000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.344 / 1.4 | V | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -144.13 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.35220000000001,10.0,85.297932,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.35220000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="85.297932" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 171.632 / 1200.0 | uV/°C | 2498/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -83.009 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.109759999999994,10.0,101.84255999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.109759999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.84255999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.704 / -70.0 | uA | 2481/100.0%/0.0%/0.0% |  |

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
| Mean Reference Voltage | 1 / 1.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,139.10167929624086,17,139.10167929624086,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.05083964812043,10.0,71.05083964812043,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.272777537552,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="36.272777537552" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.423 / 1.4 | V | 2482/99.9194%/0.0806%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.407 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.346217343999999,10.0,115.39620479999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.346217343999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="115.39620479999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 19.513 / 25.0 | mV | 2474/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.1 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.085680000000025,10.0,124.08852000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="39.085680000000025" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.08852000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.336 / 1.4 | V | 2483/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -6.263 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="52.452192000000004,10.0,118.610292,10.0" style="stroke:green;stroke-width:2" /><circle cx="52.452192000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="118.610292" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.114 / 20.0 | mV/V | 2482/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.864 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.45327999999998,10.0,119.65391999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.45327999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.65391999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.697 / -70.0 | uA | 2480/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_2/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_2/ll_mm/dc.csv Index:3 te:20.0 <br>
</details><br>


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
| PSRR+ at 10 Hz | -120 / -111.186 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.763199999999992,10.0,87.62547692307692,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.763199999999992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.62547692307692" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -43.602 / 10 | dB | 2466/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.887 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.2558528,10.0,95.06921759999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.2558528" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.06921759999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.181 / 20 | dB | 2466/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.97400000000003,10.0,88.25124000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.97400000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.25124000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.237 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.783 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.7551744639999995,10.0,10.124002560000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.7551744639999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.124002560000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.368 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.223 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.32940799999999,10.0,70.88822399999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.32940799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.88822399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.236 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / 23.685 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.4210784,10.0,80.580495,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.4210784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.580495" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 93.008 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.044 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.18239999999999,10.0,108.96096000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.18239999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.96096000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -73.962 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.121 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.60068000000002,10.0,142.53744000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.60068000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="142.53744000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.388 / 1.4 | V | 2406/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.332 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.767184768,10.0,29.86002624,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.767184768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.86002624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 46.632 / 250.0 | mV | 2468/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.125 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.133559999999974,10.0,132.82752000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.133559999999974" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="132.82752000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.361 / 1.4 | V | 2406/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -138.322 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.70068,10.0,93.688704,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.70068" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.688704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 311.478 / 1200.0 | uV/°C | 2495/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.29 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.0131200000001,10.0,146.50271999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.0131200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.50271999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -70.052 / -70.0 | uA | 2356/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.77276000000005,10.0,88.39164,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.77276000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.39164" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.237 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.791 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.07503104,10.0,54.87172608,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.07503104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="54.87172608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.006 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.221 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.51868799999998,10.0,70.36579199999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.51868799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.36579199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.234 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.262 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.14220999999999,10.0,100.724826,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.14220999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.724826" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 7.146 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -90.652 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.86991999999998,10.0,127.98048,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.86991999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.98048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -73.962 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.072 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,22.304119988511363,17,22.304119988511363,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.652059994255682,10.0,12.652059994255682,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.490474455722678,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="6.490474455722678" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.984 / 1.4 | V | 2498/94.4756%/5.5244%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.569 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,6.254286786402277,17,6.254286786402277,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.6271433932011385,10.0,4.6271433932011385,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.028530518992515,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.028530518992515" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2870.157 / 25.0 | mV | 2498/94.2354%/5.7646%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 0.761 | <svg height="20" width="150"><polyline points="16.52317261554952,3,16.52317261554952,17,39.17013102877465,17,39.17013102877465,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="27.846651822162084,10.0,27.846651822162084,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.305 / 1.4 | V | 2498/94.5156%/5.4844%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -6.018 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.5686283078893455,17,5.5686283078893455,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.284314153944672,10.0,4.284314153944672,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.8978685201222594,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.8978685201222594" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2222.442 / 20.0 | mV/V | 2495/94.509%/5.491%/0.0% |  |
| Max. Supply Current | -100.0 / -22943.0 | <svg height="20" width="150"><polyline points="94.50957697999776,3,94.50957697999776,17,96.63238428680509,17,96.63238428680509,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="95.57098063340143,10.0,95.57098063340143,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 12234.06 / -70.0 | uA | 2491/94.3798%/5.6202%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ss_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_9/ss_mm/dc.csv Index:3 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ss_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:33 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 3.3V":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ss_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_9/ff_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_9/ss_mm/dc.csv Index:3 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 3.3V":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/hh_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_9/ss_mm/dc.csv Index:1 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/hh_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ss_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/hh_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/tt_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ss_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/hh_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/tt_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_1/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ss_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/hh_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/tt_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ll_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ff_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/ss_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/hh_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/hh_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_6/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/hh_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/tt_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ll_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_9/ff_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_9/ss_mm/dc.csv Index:4 te:20.0 <br>
</details><br>


## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 2.161 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.11201136,10.0,29.9621856,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.11201136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.9621856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.724 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.32854032,10.0,7.2092871679999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.32854032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.2092871679999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.767 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -82.751 | <svg height="20" width="150"><polyline points="12.265364075909853,3,12.265364075909853,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.63268203795494,10.0,79.63268203795494,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,29.154013852404763,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="29.154013852404763" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -74.986 / -40 | dB | 5/80.0%/20.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 8.34 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="91.0310592,10.0,97.86049919999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="91.0310592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="97.86049919999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.763 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10 Hz":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.3_bmbg_ext/batch_0/ff/ac_psrr.csv Index:0 <br>
</details><br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -110.907 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.072246153846159,10.0,100.14539076923077,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.072246153846159" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.14539076923077" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -32.299 / 10 | dB | 2445/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.345 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="86.2551984,10.0,101.950272,10.0" style="stroke:green;stroke-width:2" /><circle cx="86.2551984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.950272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.615 / 20 | dB | 2444/100.0%/0.0%/0.0% |  |

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
