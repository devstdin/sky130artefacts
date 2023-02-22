22.02.2023, 12:16:06

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
| Open-Loop Gain | 90 / 96.269 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.13593599999997,10.0,51.86451200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.13593599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.86451200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.509 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 93.864 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="100.52783039999997,10.0,125.353344,10.0" style="stroke:green;stroke-width:2" /><circle cx="100.52783039999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.353344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.484 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 56.215 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.88196705882353,10.0,123.80998588235293,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.88196705882353" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.80998588235293" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.311 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.417 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.604872727272727,10.0,10.087733818181817,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.604872727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.087733818181817" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.587 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 62.992 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.708825600000004,10.0,77.01225600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.708825600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.01225600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 101.397 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 61.5 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.38304872727272,10.0,137.68314763636363,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.38304872727272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.68314763636363" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 86.441 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 63.6 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.75936000000001,10.0,95.82976000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.75936000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.82976000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 98.019 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 50.534 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.91094399999999,10.0,86.82828342857141,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.91094399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.82828342857141" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 55.375 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.04 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.9115154285714,10.0,81.66117257142855,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.9115154285714" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.66117257142855" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 88.238 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.674 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.87074559999999,10.0,69.44207999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.87074559999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.44207999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.921 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

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
| Negative Output Bound | -2.5 / -2.265 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.63967999999996,10.0,74.87615999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.63967999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.87615999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.25 / -2 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.091 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.117280000000036,10.0,39.40464000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.117280000000036" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.40464000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.126 / 2.5 | V | 2500/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.905 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.694916571428557,10.0,59.34514285714287,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.694916571428557" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.34514285714287" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.074 / 1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.895 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.460489142857146,10.0,61.277417142857146,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.460489142857146" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.277417142857146" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.083 / 1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

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
| Input Offset | -10.0 / -3.512 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.710936000000004,10.0,100.9913952,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.710936000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.9913952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.61 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.563 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.053096,10.0,79.64608799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.053096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.64608799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.645 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -22.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.89656,10.0,97.03631999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.89656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="97.03631999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -16.939 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

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
| THD | 0 / 0.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.8970352,10.0,71.7804,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.8970352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.7804" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.143 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.36 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.79127999999997,10.0,51.31831999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.79127999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.31831999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.433 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 86.895 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.45656319999999,10.0,97.02837120000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.45656319999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="97.02837120000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 92.649 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 46.919 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.132975058823526,10.0,61.603256470588235,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.132975058823526" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.603256470588235" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 59.592 / 110.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.416 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.596925090909091,10.0,11.153290181818182,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.596925090909091" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.153290181818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.523 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.256 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.041111999999956,10.0,51.913184000000015,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.041111999999956" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.913184000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.516 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 85.299 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.86160960000001,10.0,102.57795840000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.86160960000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="102.57795840000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.576 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 41.696 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.284429176470585,10.0,72.10141552941177,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.284429176470585" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.10141552941177" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.789 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.399 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.351041454545454,10.0,9.541594181818182,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.351041454545454" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.541594181818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.55 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.297 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.468025600000004,10.0,65.1510176,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.468025600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.1510176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.772 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 55.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.603895272727264,10.0,79.14992290909093,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.603895272727264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.14992290909093" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 64.085 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.54 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.26388800000001,10.0,93.282,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.26388800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.282" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.426 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 49.406 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.26912457142856,10.0,70.1088137142857,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.26912457142856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.1088137142857" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.311 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 40 / 84.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.0532,10.0,83.67798,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.0532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.67798" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.821 / 120 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.486 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.06097280000001,10.0,61.43539200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.06097280000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.43539200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.087 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 66.361 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="26.559710400000004,10.0,97.39488,10.0" style="stroke:green;stroke-width:2" /><circle cx="26.559710400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="97.39488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 115.552 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 54.611 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.34463999999999,10.0,101.31147054545455,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.34463999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.31147054545455" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 72.55 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 63.313 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.301392,10.0,117.42192,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.301392" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.42192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 111.514 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 49.283 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.765536,10.0,77.33938285714287,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.765536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.33938285714287" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 53.069 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.52 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.89892342857141,10.0,80.26918628571427,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.89892342857141" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.26918628571427" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.561 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.267 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.959091199999996,10.0,62.88940799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.959091199999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.88940799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.238 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.2656824,10.0,78.41793936,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.2656824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.41793936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.427 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="34.87296,10.0,59.113704,10.0" style="stroke:green;stroke-width:2" /><circle cx="34.87296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.113704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.794 / 30.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -19.692 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.22048,10.0,104.4768,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.22048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.4768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -15.906 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -3.02 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.25636,10.0,99.087024,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.25636" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.087024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.345 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 13.91 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.149264,10.0,64.63135199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.149264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="64.63135199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.56 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -20.512 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.31,10.0,105.92112,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.31" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.92112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -15.705 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

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
| THD | 0 / 0.122 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.647983999999994,10.0,78.76660799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.647983999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.76660799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.158 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.113 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.386592,10.0,89.598384,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.386592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.598384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.18 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

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
