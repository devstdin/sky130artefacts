17.09.2022, 22:12:03

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
| Open-Loop Gain | 90 / 96.259 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.06566399999997,10.0,51.99828800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.06566399999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.99828800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.528 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 93.558 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="99.6459744,10.0,124.20019199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="99.6459744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.20019199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.083 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 56.646 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.611996235294114,10.0,124.30361788235294,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.611996235294114" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.30361788235294" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.603 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.421 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.6638981818181815,10.0,10.041268363636364,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.6638981818181815" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.041268363636364" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.584 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 63.415 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.3175712,10.0,78.08217599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.3175712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.08217599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.14 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 61.83 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.2459229090909,10.0,130.8933381818182,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.2459229090909" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.8933381818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 83.848 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 62.174 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.477808,10.0,112.6144,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.477808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="112.6144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 108.509 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 51.318 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.1358034285714,10.0,91.7577737142857,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.1358034285714" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.7577737142857" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 56.573 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.171 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.181248,10.0,78.02704457142856,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.181248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.02704457142856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 86.471 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.816 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.232975999999994,10.0,69.454752,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.232975999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.454752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.922 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

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
| Negative Output Bound | -2.5 / -2.264 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.87295999999995,10.0,74.54783999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.87295999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.54783999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.252 / -2 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.095 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.48671999999999,10.0,39.22089600000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.48671999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.22089600000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.126 / 2.5 | V | 2500/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.905 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.694916571428557,10.0,59.34514285714287,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.694916571428557" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.34514285714287" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.074 / 1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.892 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.925055999999998,10.0,62.291794285714296,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.925055999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.291794285714296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.088 / 1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

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
| Input Offset | -10.0 / -4.409 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.252392,10.0,103.9493928,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.252392" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.9493928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.021 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.405 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.919168,10.0,79.3686,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.919168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.3686" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.607 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -22.038 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.3228,10.0,96.56832,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.3228" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.56832" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -17.004 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

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
| THD | 0 / 0.093 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.650406399999994,10.0,71.138784,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.650406399999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.138784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.142 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

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
| Open-Loop Gain | 90 / 96.269 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.13535999999999,10.0,51.87797599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.13535999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.87797599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.511 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 85.251 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.7229952,10.0,103.18903679999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.7229952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.18903679999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.788 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 43.424 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="34.21223717647059,10.0,71.6544734117647,10.0" style="stroke:green;stroke-width:2" /><circle cx="34.21223717647059" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.6544734117647" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.525 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.397 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.320558545454546,10.0,9.521010909090908,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.320558545454546" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.521010909090908" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.548 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 63.724 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.763236799999994,10.0,65.12099519999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.763236799999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.12099519999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 93.14 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 54.762 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.73940945454546,10.0,86.30753454545454,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.73940945454546" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.30753454545454" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 66.819 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 62.919 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.670048,10.0,100.91184000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="39.670048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.91184000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 101.195 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 47.833 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.79665371428572,10.0,77.22414171428571,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.79665371428572" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.22414171428571" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 53.041 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.689 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.24688914285713,10.0,79.21504457142856,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.24688914285713" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.21504457142856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.049 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.352 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.77814399999999,10.0,63.585119999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.77814399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.585119999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.311 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

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
| Input Offset | -10.0 / -3.932 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.692408,10.0,107.3727696,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.692408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.3727696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.496 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.014 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.903176,10.0,61.938407999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.903176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.938407999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.186 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -19.975 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.17927999999999,10.0,105.90671999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.17927999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.90671999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -15.707 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

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
| THD | 0 / 0.11 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.899888000000004,10.0,85.998528,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.899888000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="85.998528" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.173 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89.png "") |
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

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__7268da64711c9c5b18b48d467dd95411](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__7268da64711c9c5b18b48d467dd95411.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__7268da64711c9c5b18b48d467dd95411](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__7268da64711c9c5b18b48d467dd95411.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__d7804ec337891d79b9e125cf65f36757](histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__d7804ec337891d79b9e125cf65f36757.png "") |
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

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b24c2ee304e43216830b82402f8d8537](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b24c2ee304e43216830b82402f8d8537.png "") |
| :-- |
|  |
<br>
