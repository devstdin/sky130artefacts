31.08.2024, 13:50:35

# LDO OP

OpAmp used in LDO.

![ldoota](resources/ldoota.png "ldoota")

<br>

[🔗 Schematics](ldoota_sch.pdf)<br>

# SPECIFICATIONS

## AC Open-Loop Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.315 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.33302799999999,10.0,56.527752,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.33302799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.527752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.869 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 91.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="94.51859519999998,10.0,121.336608,10.0" style="stroke:green;stroke-width:2" /><circle cx="94.51859519999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.336608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 101.089 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 10.323 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.646016,10.0,90.995376,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.646016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.995376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.111 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.268261818181816,10.0,26.03656727272727,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.268261818181816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.03656727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.684 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.185 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.866180000000014,10.0,57.09133199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.866180000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.09133199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.025 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 89.878 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.04961919999998,10.0,124.81651199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="89.04961919999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.81651199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.297 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.042 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.2118416,10.0,127.259616,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.2118416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.259616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.629 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.151 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.284218181818183,10.0,27.455621818181818,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.284218181818183" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.455621818181818" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.708 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.618799999999993,10.0,27.7513088,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.618799999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.7513088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.8 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 42.732 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="94.66816800000001,10.0,100.41304799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="94.66816800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.41304799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.53 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.105 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.168016,10.0,6.982255999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.168016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.982255999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.239 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.236 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.3029312,10.0,75.68119423200001,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.3029312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.68119423200001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.095 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.801 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.76604800000001,10.0,89.13287999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.76604800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.13287999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.963 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 28.016 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.716928,10.0,71.80536000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.716928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.80536000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.556 / 40 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 62.579 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.1139472,10.0,39.039024000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.1139472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.039024000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.027 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 40.706 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.08067999999999,10.0,117.51664800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.08067999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.51664800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 45.905 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.109 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1746239999999943,10.0,7.0342560000000045,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1746239999999943" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.0342560000000045" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.271 / 130 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.781 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.3796368,10.0,76.96719912,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.3796368" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.96719912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.273 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.616 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.43527200000003,10.0,90.784776,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.43527200000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.784776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.192 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 27.859 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.584655999999995,10.0,73.933608,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.584655999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="73.933608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.852 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

<br>


## Output Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -3 / -2.856 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.847039999999993,10.0,107.71296,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.847039999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.71296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.909 / -1.5 | V | 5/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.67139199999997,10.0,146.73302400000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.67139199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.73302400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 5/100.0%/0.0%/0.0% |  |

<br>


## Output Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -3 / -2.864 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.078079999999986,10.0,130.47072,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.078079999999986" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.47072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.672 / -1.5 | V | 1000/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.66707200000002,10.0,146.73936000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.66707200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.73936000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 1000/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.08768,10.0,95.27424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.08768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.27424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.039 / -1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.121 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.35808,10.0,95.86560000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.35808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.86560000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.033 / -1.5 | V | 1000/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Slew-Rate/Offset Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 14.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="128.99600400000003,10.0,137.271684,10.0" style="stroke:green;stroke-width:2" /><circle cx="128.99600400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.271684" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.298 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.293 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.032384,10.0,38.062152,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.032384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.062152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.461 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.182 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="125.72472,10.0,137.13258,10.0" style="stroke:green;stroke-width:2" /><circle cx="125.72472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.13258" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.548 / -2.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 13.231 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="122.63034,10.0,143.97474000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="122.63034" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="143.97474000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 19.16 / 20.0 | mV | 1000/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.118 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.82972,10.0,41.963304,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.82972" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="41.963304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.623 / 10.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.237 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.73184,10.0,138.43452,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.73184" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="138.43452" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.476 / -2.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.6334976,10.0,22.653622399999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.6334976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.653622399999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.226 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.4958776,10.0,13.941119839999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.4958776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.941119839999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.2846096,10.0,17.6246448,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.2846096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.6246448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.03 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.02 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.3861264,10.0,19.2428352,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.3861264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.2428352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.316 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.337815999999975,10.0,56.54776800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.337815999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.54776800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.874 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 85.212 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.61076159999999,10.0,95.34161279999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.61076159999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.34161279999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 92.063 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 10.043 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.62366399999999,10.0,88.193136,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.62366399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.193136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.916 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.154 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.336552727272725,10.0,24.75104,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.336552727272725" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="24.75104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.595 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.145 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.72210800000002,10.0,57.15685200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.72210800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.15685200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.044 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 83.902 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.83663680000001,10.0,101.6869728,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.83663680000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.6869728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.266 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 8.341 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.1087584,10.0,120.65203199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.1087584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.65203199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.17 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.074 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.161192727272727,10.0,26.03074909090909,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.161192727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.03074909090909" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.683 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.706 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.6166256,10.0,27.761446400000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.6166256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.761446400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.807 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 38.025 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.782448,10.0,63.827672,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.782448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.827672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 38.171 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.107 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1707520000000047,10.0,6.991872000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1707520000000047" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.991872000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.245 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.4922736,10.0,72.45070319999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.4922736" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.45070319999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.354 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.77980000000002,10.0,89.175792,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.77980000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.175792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.969 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 21.336 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.622511999999992,10.0,19.11216,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.622511999999992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.11216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 22.238 / 40 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 60.09 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.529340800000003,10.0,35.229864,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.529340800000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="35.229864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 72.382 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 37.127 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.31447199999999,10.0,69.49099199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.31447199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.49099199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 39.235 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 39.996 | <svg height="20" width="150"><polyline points="3.0071836416160966,3,3.0071836416160966,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.00359182080804,10.0,75.00359182080804,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,5.015771435402824,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="5.015771435402824" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 41.255 / 130 | dB | 1000/95.0%/5.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.974 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.9838232,10.0,74.32897152,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.9838232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.32897152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.093 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.459 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.307968,10.0,89.51772000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.307968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.51772000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.016 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 20.973 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.007472,10.0,21.527544000000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.007472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="21.527544000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 22.573 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10Hz":<br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:49 <br>
</details><br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,137.28385200000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.0" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.28385200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.301 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.064 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.53792,10.0,29.270832000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.53792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.270832000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.095 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -2.983 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="129.29916,10.0,139.42866,10.0" style="stroke:green;stroke-width:2" /><circle cx="129.29916" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="139.42866" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.421 / -2.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.117503059975521,17,5.117503059975521,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.05875152998776,10.0,4.05875152998776,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.05875152998776,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.05875152998776" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 49000.0 / 20.0 | mV | 1000/71.4%/28.6%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 3.931 | <svg height="20" width="150"><polyline points="4.6389787112603775,3,4.6389787112603775,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.8194893556302,10.0,75.8194893556302,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,34.20226156300208,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="34.20226156300208" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.246 / 10.0 | MV/s | 1000/90.0%/10.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -7.124 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,60.63071140610831,17,60.63071140610831,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.815355703054156,10.0,31.815355703054156,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.7206900557307,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="23.7206900557307" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 9.989 / -2.0 | MV/s | 1000/91.8%/8.2%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Input Offset":<br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:3 <br>

> **FAIL:** Specification violation for parameter "Slew-Rate (Positive)":<br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/hh_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/hh_mm/ldoota_tran_slew.csv Index:49 <br>

> **FAIL:** Specification violation for parameter "Slew-Rate (Negative)":<br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:20 <br>
</details><br>


## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.632158399999998,10.0,22.666308799999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.632158399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.666308799999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.227 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.49518784,10.0,13.946061919999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.49518784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.946061919999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.024 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.6973456,10.0,19.6052256,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.6973456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.6052256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.035 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.022 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.4919984,10.0,22.009252800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.4919984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.009252800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.04 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__fa85d0e9390d57bbdc389bd17fc02e0e](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__fa85d0e9390d57bbdc389bd17fc02e0e.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c5f514d011b9e91a00ee0092b42f5c48](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c5f514d011b9e91a00ee0092b42f5c48.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c5f514d011b9e91a00ee0092b42f5c48](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c5f514d011b9e91a00ee0092b42f5c48.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c5f514d011b9e91a00ee0092b42f5c48](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c5f514d011b9e91a00ee0092b42f5c48.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c5f514d011b9e91a00ee0092b42f5c48](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c5f514d011b9e91a00ee0092b42f5c48.png "") |
| :-- |
|  |
<br>

## CMRR/PSRR Performance<br>

| ![xyplot_frequencycmrrgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35](xyplot_frequencycmrrgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35](xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencypsrr_ngroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35](xyplot_frequencypsrr_ngroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35.png "") |
| :-- |
|  |
<br>

## CMRR/PSRR Performance (Monte Carlo)<br>

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e4fdabb14986de7e65c5b7fe20b3734e.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__72054206e042af3b89897168b5364ac6](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__72054206e042af3b89897168b5364ac6.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__72054206e042af3b89897168b5364ac6](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__72054206e042af3b89897168b5364ac6.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_neg_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f633d1e9aa2665c9693edd0b7840be00](histplot_neg_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f633d1e9aa2665c9693edd0b7840be00.png "") |
| :-- |
|  |
<br>

## Slew-Rate/Offset Performance<br>

| ![xyplot_timev(opout_10f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7ac8ac6694ffa6dd8e854fb95dac80b6](xyplot_timev(opout_10f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7ac8ac6694ffa6dd8e854fb95dac80b6.png "") |
| :-- |
|  |
<br>

| ![xyplot_timev(opout_500f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7ac8ac6694ffa6dd8e854fb95dac80b6](xyplot_timev(opout_500f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7ac8ac6694ffa6dd8e854fb95dac80b6.png "") |
| :-- |
|  |
<br>

## Slew-Rate/Offset Performance (Monte Carlo)<br>

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c4d28290f62faf20c82a1ebe8b5ec4ac](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c4d28290f62faf20c82a1ebe8b5ec4ac.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c4d28290f62faf20c82a1ebe8b5ec4ac](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c4d28290f62faf20c82a1ebe8b5ec4ac.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c4d28290f62faf20c82a1ebe8b5ec4ac](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c4d28290f62faf20c82a1ebe8b5ec4ac.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__452d3dc177265d4ca87b7a218428cdae](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__452d3dc177265d4ca87b7a218428cdae.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__aba305d89047bd26d3e005a67f6d9975](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__aba305d89047bd26d3e005a67f6d9975.png "") |
| :-- |
|  |
<br>
