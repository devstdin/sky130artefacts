19.12.2023, 20:08:05

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
| Mean Reference Voltage | 1 / 1.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.80720000000001,10.0,82.40231999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.80720000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.40231999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.221 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.409 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.53933632,10.0,11.23349952,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.53933632" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.23349952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.294 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.04569599999997,10.0,66.851328,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.04569599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.851328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -45.603 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.263796,10.0,76.5645348,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.263796" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.5645348" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.076 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.625 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.602879999999985,10.0,105.75456000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.602879999999985" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.75456000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 0.961 | <svg height="20" width="150"><polyline points="15.67742204659856,3,15.67742204659856,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.33871102329928,10.0,81.33871102329928,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,130.1289884103265,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="130.1289884103265" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.349 / 1.4 | V | 2419/99.8346%/0.1654%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.762 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.014882624,10.0,21.641664,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.014882624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="21.641664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 32.364 / 250.0 | mV | 2410/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.11 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.63959999999998,10.0,128.74331999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.63959999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.74331999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.349 / 1.4 | V | 2411/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -165.865 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.0481,10.0,83.42669400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.0481" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.42669400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 140.445 / 1200.0 | uV/°C | 2411/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.743 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.66912000000001,10.0,93.63552,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.66912000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.63552" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.559 / -70.0 | uA | 2410/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/tt_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/tt_mm/dc.csv Index:29 vsup:5.0 <br>
</details><br>


## Reference Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.201 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.49788000000004,10.0,82.18524000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.49788000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.18524000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.22 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.388 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.5156864,10.0,59.35991808,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.5156864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.35991808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.785 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.198 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.960064,10.0,65.79609600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.960064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.79609600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.218 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.797 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.06801200000001,10.0,105.00939480000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.06801200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.00939480000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.336 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.325 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.639040000000016,10.0,126.37728,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.639040000000016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.37728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.027 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.790560000000001,10.0,131.36916000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.790560000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="131.36916000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.357 / 1.4 | V | 2458/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.837 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.81939776,10.0,141.93903360000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.81939776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="141.93903360000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 24.121 / 25.0 | mV | 2456/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.093 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.591240000000035,10.0,128.92872,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.591240000000035" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.92872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.35 / 1.4 | V | 2457/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -4.08 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.31196400000001,10.0,127.620516,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.31196400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.620516" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.617 / 20.0 | mV/V | 2456/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.284 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.23584,10.0,120.81168,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.23584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.81168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.456 / -70.0 | uA | 2456/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 12.924 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.6109056,10.0,28.947014400000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.6109056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="28.947014400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.019 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.61 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.755827136,10.0,7.134408896,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.755827136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.134408896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.741 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -65.127 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.542440000000006,10.0,66.24732,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.542440000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.24732" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.431 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.585 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.6091232,10.0,89.9685312,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.6091232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.9685312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.118 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -112.945 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.814769230769238,10.0,108.65867076923078,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.814769230769238" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.65867076923078" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -24.614 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.592 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.840712,10.0,93.819984,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.840712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.819984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.921 / 20 | dB | 2422/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.217 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.95728,10.0,86.64528000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.95728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.64528000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.232 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.057 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.336667264000001,10.0,8.407310592,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.336667264000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.407310592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.388 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.92627199999998,10.0,69.78777600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.92627199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.78777600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.232 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / 1.38 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.08278104,10.0,79.48157220000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.08278104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.48157220000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.693 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.087 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.768640000000055,10.0,108.73535999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.768640000000055" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.73535999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -73.986 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.06 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,135.44698096764478,17,135.44698096764478,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.22349048382239,10.0,69.22349048382239,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.794863540519355,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="22.794863540519355" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.435 / 1.4 | V | 2435/99.9179%/0.0821%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.071 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.192929984,10.0,24.10840128,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.192929984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="24.10840128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 36.647 / 250.0 | mV | 2427/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.122 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.83180000000003,10.0,130.42200000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.83180000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.42200000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.354 / 1.4 | V | 2440/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -168.342 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.89948000000001,10.0,90.13880400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.89948000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.13880400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 252.313 / 1200.0 | uV/°C | 2473/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.828 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.852160000000104,10.0,144.6086399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.852160000000104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="144.6086399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -70.249 / -70.0 | uA | 2390/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ff_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/tt_mm/dc.csv Index:12 vsup:5.0 <br>
</details><br>


## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.38568000000001,10.0,86.07036,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.38568000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.07036" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.231 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.518 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.26492416,10.0,62.144313600000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.26492416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.144313600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.268 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.214 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.61961599999998,10.0,68.686464,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.61961599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.686464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.228 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.9 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.44138600000001,10.0,106.36421879999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.44138600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.36421879999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.712 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -90.648 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.88816000000002,10.0,127.86767999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.88816000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.86767999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -73.986 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.117 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,141.69291558513478,17,141.69291558513478,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.34645779256739,10.0,72.34645779256739,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.469552570875436,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="43.469552570875436" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.415 / 1.4 | V | 2435/99.9589%/0.0411%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.863 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.97227968,10.0,139.3650048,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.97227968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="139.3650048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 23.674 / 25.0 | mV | 2429/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.117 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.01055999999998,10.0,127.5402,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.01055999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.5402" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.346 / 1.4 | V | 2436/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -4.058 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.389579999999995,10.0,127.823952,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.389579999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.823952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.673 / 20.0 | mV/V | 2435/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -84.353 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.10560000000001,10.0,121.51775999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.10560000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.51775999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.309 / -70.0 | uA | 2458/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_4/ll_mm/dc.csv Index:6 te:20.0 <br>
</details><br>


## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.039881599999998,10.0,29.6575824,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.039881599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.6575824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.512 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.622 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.791591840000001,10.0,7.1858891840000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.791591840000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.1858891840000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.759 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -107.036 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.360123076923074,10.0,135.9370110166154,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.360123076923074" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.9370110166154" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.013 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.158 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.3569888,10.0,100.35974399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.3569888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.35974399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.283 / 20 | dB | 2441/100.0%/0.0%/0.0% |  |

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
