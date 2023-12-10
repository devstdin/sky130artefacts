10.12.2023, 15:11:29

# Beta-Multiplier Bandgap OTA

OTA for Beta-Multiplier Bandgap.

![bmbgota](resources/bmbgota.png "bmbgota")

<br>

[🔗 Schematics](bmbgota_sch.pdf)<br>

# LVS

[🔗 LVS-report](bmbgota_bmbgota_netgen_comp.out)<br>

# SPECIFICATIONS

## AC Open-Loop Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.36 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.79120799999995,10.0,51.318248000000054,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.79120799999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.318248000000054" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.433 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 95.784 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="106.0578912,10.0,115.89335039999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="106.0578912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="115.89335039999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 99.199 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 62.415 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.38497129411763,10.0,107.37111529411764,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.38497129411763" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.37111529411764" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 86.608 / 110.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.439 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.928058181818181,10.0,11.683957818181819,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.928058181818181" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.683957818181819" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.56 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.286 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.256896,10.0,51.86991199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.256896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.86991199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.51 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 92.334 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="96.12209279999998,10.0,126.51744000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="96.12209279999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.51744000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.888 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 54.389 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="52.78798305882353,10.0,131.50712470588235,10.0" style="stroke:green;stroke-width:2" /><circle cx="52.78798305882353" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="131.50712470588235" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 100.855 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.416 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.600907636363637,10.0,10.055994181818182,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.600907636363637" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.055994181818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.585 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.297 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.4679536,10.0,65.15096,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.4679536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.15096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.772 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 67.323 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.6283810909091,10.0,106.96792145454545,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.6283810909091" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.96792145454545" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.71 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.54 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.263824,10.0,93.281952,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.263824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.281952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.426 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 52.774 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.12813714285714,10.0,77.244384,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.12813714285714" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.244384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 53.046 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 40 / 84.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.053398,10.0,83.677854,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.053398" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.677854" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.821 / 120 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.985 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.8586112,10.0,67.851264,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.8586112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.851264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.755 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 64.014 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.180577600000003,10.0,75.12297600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.180577600000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.12297600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 100.085 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 61.523 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.44143418181818,10.0,130.0405178181818,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.44143418181818" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.0405178181818" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 83.522 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 66.176 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.88190400000001,10.0,125.10352,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.88190400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.10352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 116.315 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 51.477 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.78981028571427,10.0,87.41386971428571,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.78981028571427" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.41386971428571" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 55.517 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.134 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.10466057142855,10.0,79.650336,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.10466057142855" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.650336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.261 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.774 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.83129280000001,10.0,69.31641599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.83129280000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.31641599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.908 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<br>


## Output Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -2.5 / -2.263 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.29056,10.0,74.09567999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.29056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.09567999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.253 / -2 | V | 5/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.086911999999984,10.0,38.59910399999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.086911999999984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.59910399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.124 / 2.5 | V | 5/100.0%/0.0%/0.0% |  |

<br>


## Output Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -2.5 / -2.264 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.05151999999997,10.0,74.75232000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.05151999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.75232000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.251 / -2 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.392031999999944,10.0,39.28252799999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.392031999999944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.28252799999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.126 / 2.5 | V | 2500/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.905 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.694916571428557,10.0,59.34514285714287,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.694916571428557" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.34514285714287" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.074 / 1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.894 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.326672000000002,10.0,61.520777142857135,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.326672000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.520777142857135" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.084 / 1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Slew-Rate/Offset Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.265902,10.0,78.41806176,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.265902" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.41806176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.989 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.121088,10.0,76.42286399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.121088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.42286399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.198 / 30.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -21.782 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.166,10.0,94.80792,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.166" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.80792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -17.249 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -3.397 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.539944,10.0,106.3866864,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.539944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.3866864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.359 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.595 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.28688,10.0,78.02997599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.28688" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.02997599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.421 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -22.304 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.41336,10.0,96.80448,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.41336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.80448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -16.972 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 0.943 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.5813816,10.0,19.859777599999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.5813816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.859777599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.032 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.61293648,10.0,12.20181872,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.61293648" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.20181872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.05 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.1 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.143471999999996,10.0,65.18803199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.143471999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.18803199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.13 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.093 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.618808,10.0,72.81648,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.618808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.81648" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.145 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.36 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.79127999999997,10.0,51.31831999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.79127999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.31831999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.433 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 89.457 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.83708159999999,10.0,101.42368320000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.83708159999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.42368320000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.175 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 50.717 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.56684423529411,10.0,71.47345694117647,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.56684423529411" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.47345694117647" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.418 / 110.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.416 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.592078545454545,10.0,11.145631999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.592078545454545" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.145631999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.523 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.276 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.19043999999998,10.0,51.87243199999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.19043999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.87243199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.51 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 88.02 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.6981472,10.0,108.63831359999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.6981472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.63831359999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.68 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 45.66 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.00130070588235,10.0,87.18607623529411,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.00130070588235" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.18607623529411" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.693 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.399 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.345335272727273,10.0,9.502536727272727,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.345335272727273" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.502536727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.547 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.297 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.468025600000004,10.0,65.1510176,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.468025600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.1510176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.772 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 54.358 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.683077818181815,10.0,72.10138472727273,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.683077818181815" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.10138472727273" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.393 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.54 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.26388800000001,10.0,93.282,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.26388800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.282" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.426 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 52.857 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.46875885714286,10.0,86.50786285714284,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.46875885714286" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.50786285714284" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 55.297 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 40 / 84.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.0532,10.0,83.67798,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.0532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.67798" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.821 / 120 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.552 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.6949088,10.0,61.91510400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.6949088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.91510400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.137 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 63.607 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.594007999999995,10.0,75.183168,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.594007999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.183168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 100.127 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 52.812 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.635892363636366,10.0,84.49810909090911,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.635892363636366" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.49810909090911" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 66.128 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 64.383 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.012879999999996,10.0,120.19120000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.012879999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.19120000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 113.244 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 52.011 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.98609828571426,10.0,98.89737600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.98609828571426" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="98.89737600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 58.308 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 83.152 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.19942857142857,10.0,80.20545599999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.19942857142857" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.20545599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.53 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.461 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.8245056,10.0,63.982272,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.8245056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.982272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.352 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.26578464,10.0,78.41817408,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.26578464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.41817408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.687 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.742944,10.0,61.902696,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.742944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.902696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.181 / 30.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -19.87 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.93455999999999,10.0,103.64376,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.93455999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.64376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -16.022 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -3.129 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="52.474152,10.0,106.1447376,10.0" style="stroke:green;stroke-width:2" /><circle cx="52.474152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.1447376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.326 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.152 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="32.89152,10.0,64.559208,10.0" style="stroke:green;stroke-width:2" /><circle cx="32.89152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="64.559208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.55 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -20.322 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.68088,10.0,107.54688,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.68088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.54688" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -15.48 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 0.943 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.58140464,10.0,19.859806399999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.58140464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.859806399999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.032 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.61294656,10.0,12.20183312,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.61294656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.20183312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.05 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.117 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.944384,10.0,75.02476800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.944384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.02476800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.15 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.107 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.554256,10.0,82.737216,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.554256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.737216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.166 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a.png "") |
| :-- |
|  |
<br>

## CMRR/PSRR Performance<br>

| ![xyplot_frequencycmrrgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3](xyplot_frequencycmrrgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3](xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencypsrr_ngroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3](xyplot_frequencypsrr_ngroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3.png "") |
| :-- |
|  |
<br>

## CMRR/PSRR Performance (Monte Carlo)<br>

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__876ab014c98c6dbdee6eb52835fbccf8](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__876ab014c98c6dbdee6eb52835fbccf8.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__876ab014c98c6dbdee6eb52835fbccf8](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__876ab014c98c6dbdee6eb52835fbccf8.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__aed52ce6bc208f67eab947c3b90b8203](histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__aed52ce6bc208f67eab947c3b90b8203.png "") |
| :-- |
|  |
<br>

## Slew-Rate/Offset Performance<br>

| ![xyplot_timev(opout_10f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__257c10c66e943eee42eeaaf7527daa22](xyplot_timev(opout_10f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__257c10c66e943eee42eeaaf7527daa22.png "") |
| :-- |
|  |
<br>

| ![xyplot_timev(opout_500f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__257c10c66e943eee42eeaaf7527daa22](xyplot_timev(opout_500f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__257c10c66e943eee42eeaaf7527daa22.png "") |
| :-- |
|  |
<br>

## Slew-Rate/Offset Performance (Monte Carlo)<br>

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6d55a1dcf0deaaffc578b64172ae3518](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6d55a1dcf0deaaffc578b64172ae3518.png "") |
| :-- |
|  |
<br>
