01.09.2024, 15:23:46

# Beta-Multiplier Bandgap OTA

OTA for Beta-Multiplier Bandgap.

![bmbgota](resources/bmbgota.png "bmbgota")

<br>

[🔗 Schematics](bmbgota_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

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
| Open-Loop Gain | 90 / 96.272 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.15710400000004,10.0,51.869624,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.15710400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.869624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.51 / 110 | dB | 1250/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 92.112 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="95.48391360000001,10.0,126.41174399999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="95.48391360000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.41174399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.851 / 110 | deg | 1250/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 54.584 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.118454588235295,10.0,131.99045647058824,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.118454588235295" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="131.99045647058824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 101.14 / 110.0 | MHz | 1250/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.422 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.6767461818181815,10.0,10.115550545454546,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.6767461818181815" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.115550545454546" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.589 / 10.0 | kHz | 1250/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 65.01 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.61389599999999,10.0,69.8268576,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.61389599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.8268576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.408 / 150 | dB | 1250/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 61.186 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.5597090909091,10.0,129.18240872727273,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.5597090909091" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="129.18240872727273" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 83.195 / 90 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 64.857 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.77152000000001,10.0,90.281728,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.77152000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.281728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.551 / 130 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 51.489 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.83992228571428,10.0,87.709728,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.83992228571428" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.709728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 55.589 / 70 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.939 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.76109257142856,10.0,79.55696228571429,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.76109257142856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.55696228571429" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.215 / 120 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.752 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.6151968,10.0,70.570848,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.6151968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.570848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.039 / 20 | dB | 1250/100.0%/0.0%/0.0% |  |

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
| Negative Output Bound | -2.5 / -2.265 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.81823999999997,10.0,74.82432,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.81823999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.82432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.251 / -2 | V | 1250/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.09043199999998,10.0,38.78169600000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.09043199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.78169600000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.124 / 2.5 | V | 1250/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.905 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.694916571428557,10.0,59.34514285714287,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.694916571428557" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.34514285714287" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.074 / 1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.895 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.63388571428571,10.0,61.48045714285712,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.63388571428571" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.48045714285712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.084 / 1.5 | V | 1250/100.0%/0.0%/0.0% | Input transistor sat. |

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
| Input Offset | -10.0 / -1.841 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.74141600000001,10.0,95.63592,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.74141600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.63592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.866 / 10.0 | mV | 1250/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.715 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.148288,10.0,77.663496,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.148288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.663496" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.37 / 30.0 | MV/s | 1250/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -21.957 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.912479999999995,10.0,96.09888,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.912479999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.09888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -17.07 / -10.0 | MV/s | 1250/100.0%/0.0%/0.0% |  |

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
| THD | 0 / 0.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.1540944,10.0,71.93208,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.1540944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.93208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.144 / 0.3 | % | 1250/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.36 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.79127999999997,10.0,51.31831999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.79127999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.31831999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.433 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 82.672 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.29524479999999,10.0,83.98381440000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.29524479999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.98381440000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 88.119 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 46.27 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.033306352941175,10.0,60.105859764705876,10.0" style="stroke:green;stroke-width:2" /><circle cx="39.033306352941175" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="60.105859764705876" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 58.708 / 110.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.415 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.576391272727272,10.0,11.120855272727272,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.576391272727272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.120855272727272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.521 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.248 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.98848000000003,10.0,51.95919199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.98848000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.95919199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.522 / 110 | dB | 1250/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 80.716 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.662051200000015,10.0,92.1897408,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.662051200000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="92.1897408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 90.969 / 110 | deg | 1250/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 41.706 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.30235294117647,10.0,69.08151529411765,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.30235294117647" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.08151529411765" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 64.006 / 110.0 | MHz | 1250/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.4 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.358904727272727,10.0,9.447023999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.358904727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.447023999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.543 / 10.0 | kHz | 1250/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.297 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.468025600000004,10.0,65.1510176,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.468025600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.1510176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.772 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 53.908 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="52.50555054545454,10.0,72.21394036363635,10.0" style="stroke:green;stroke-width:2" /><circle cx="52.50555054545454" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.21394036363635" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.436 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.54 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.26388800000001,10.0,93.282,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.26388800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.282" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.426 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 54.366 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.67573485714286,10.0,101.84476799999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.67573485714286" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.84476799999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 59.025 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 40 / 84.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.0532,10.0,83.67798,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.0532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.67798" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.821 / 120 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.477 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.975772799999994,10.0,61.23983999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.975772799999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.23983999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.067 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.741 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.667443200000005,10.0,79.02393599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.667443200000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.02393599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.794 / 150 | dB | 1250/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 51.723 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.78343563636363,10.0,83.14066036363636,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.78343563636363" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.14066036363636" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.609 / 90 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 67.293 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.669247999999996,10.0,99.38144,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.669247999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.38144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 100.238 / 130 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 52.671 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.70485942857142,10.0,101.23671771428572,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.70485942857142" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.23671771428572" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 58.877 / 70 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 83.17 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.23618971428571,10.0,81.14281371428572,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.23618971428571" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.14281371428572" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.986 / 120 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.199 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.310035199999994,10.0,64.284288,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.310035199999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="64.284288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.384 / 20 | dB | 1250/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.265758,10.0,78.41815248,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.265758" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.41815248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.535 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="35.653583999999995,10.0,59.846016,10.0" style="stroke:green;stroke-width:2" /><circle cx="35.653583999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.846016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.895 / 30.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -19.769 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.66463999999999,10.0,104.11175999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.66463999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.11175999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -15.957 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -3.044 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.083200000000005,10.0,90.7327776,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.083200000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.7327776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.185 / 10.0 | mV | 1250/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 13.946 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.411344,10.0,59.034144,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.411344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.034144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.783 / 30.0 | MV/s | 1250/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -19.859 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.01304,10.0,107.3712,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.01304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.3712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -15.504 / -10.0 | MV/s | 1250/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 0.943 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.58140752,10.0,19.859806399999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.58140752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.859806399999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.032 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.61294944,10.0,12.20183312,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.61294944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.20183312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.05 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.12 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.451536,10.0,77.077152,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.451536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.077152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.154 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.11 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.855104,10.0,89.63759999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.855104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.63759999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.18 / 0.3 | % | 1250/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b3ac3a92908c822984c8d36b424357cf](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b3ac3a92908c822984c8d36b424357cf.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b3ac3a92908c822984c8d36b424357cf](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b3ac3a92908c822984c8d36b424357cf.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b3ac3a92908c822984c8d36b424357cf](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b3ac3a92908c822984c8d36b424357cf.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b3ac3a92908c822984c8d36b424357cf](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b3ac3a92908c822984c8d36b424357cf.png "") |
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

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8089bad58d398cd7643be64bb9ce0fed.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b2d3cc2d9e94077697adcf0625de17a4](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b2d3cc2d9e94077697adcf0625de17a4.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b2d3cc2d9e94077697adcf0625de17a4](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b2d3cc2d9e94077697adcf0625de17a4.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__899509377f527afd409351131e0505cd](histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__899509377f527afd409351131e0505cd.png "") |
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

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bc266178684032d549481f35a5fd54a2](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bc266178684032d549481f35a5fd54a2.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bc266178684032d549481f35a5fd54a2](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bc266178684032d549481f35a5fd54a2.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bc266178684032d549481f35a5fd54a2](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bc266178684032d549481f35a5fd54a2.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e31739dda2f244202d523d839e860f21](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e31739dda2f244202d523d839e860f21.png "") |
| :-- |
|  |
<br>
