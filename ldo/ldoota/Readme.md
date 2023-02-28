28.02.2023, 13:57:19

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
| Open-Loop Gain | 60 / 72.163 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.785683999999996,10.0,56.97526799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.785683999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.97526799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.993 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 90.461 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.72840000000002,10.0,125.61484800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.72840000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.61484800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.575 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 8.848 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.4093568,10.0,116.61815999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.4093568" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="116.61815999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.89 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.159 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.409876363636364,10.0,27.384174545454545,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.409876363636364" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.384174545454545" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.776 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 61.479 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.529745600000005,10.0,32.698185599999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.529745600000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="32.698185599999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 70.624 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 41.333 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="84.59659199999997,10.0,104.75313599999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="84.59659199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.75313599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 44.132 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0742240000000036,10.0,7.002448000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.0742240000000036" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.002448000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.252 / 130 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.57 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.8987288,10.0,77.12821848,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.8987288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.12821848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.296 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.63 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.53564000000001,10.0,91.75900800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.53564000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.75900800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.328 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 27.744 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.75658400000001,10.0,72.29222399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.75658400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.29222399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.624 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

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
| Negative Output Bound | -3 / -2.863 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.16640000000001,10.0,96.65280000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.16640000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.65280000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.024 / -1.5 | V | 1000/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.665056,10.0,146.737344,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.665056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.737344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 1000/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.08768,10.0,95.27424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.08768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.27424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.039 / -1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.121 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.3456,10.0,96.48192,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.3456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.48192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.026 / -1.5 | V | 1000/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Slew-Rate/Offset Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 14.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="128.99600400000003,10.0,137.271684,10.0" style="stroke:green;stroke-width:2" /><circle cx="128.99600400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.271684" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.298 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.293 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.032408,10.0,38.062152,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.032408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.062152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.461 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.182 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="125.72472,10.0,137.13258,10.0" style="stroke:green;stroke-width:2" /><circle cx="125.72472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.13258" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.548 / -2.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 13.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,142.33634293383315,17,142.33634293383315,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.66817146691658,10.0,72.66817146691658,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="117.9540852883561,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="117.9540852883561" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 21.339 / 20.0 | mV | 1000/90.0%/10.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.144 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.4580400000000004,10.0,40.43544,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.4580400000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="40.43544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.56 / 10.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.179 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="125.78106,10.0,137.52408,10.0" style="stroke:green;stroke-width:2" /><circle cx="125.78106" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.52408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.526 / -2.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Input Offset":<br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_3/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_2/tt_mm/ldoota_tran_slew.csv Index:49 <br>
</details><br>


## Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.6334976,10.0,22.653622399999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.6334976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.653622399999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.226 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.49587904,10.0,13.941121279999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.49587904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.941121279999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.2846096,10.0,17.6246448,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.2846096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.6246448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.03 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.019 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.2328048,10.0,19.1658672,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.2328048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.1658672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.316 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.337815999999975,10.0,56.54776800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.337815999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.54776800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.874 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 86.889 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.44017599999998,10.0,107.76884159999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.44017599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.76884159999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.378 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.356 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.7293808,10.0,73.59526559999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.7293808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="73.59526559999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.902 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.158 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.39601454545455,10.0,24.83658181818182,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.39601454545455" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="24.83658181818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.601 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.181 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.85329200000002,10.0,57.013392,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.85329200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.013392" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.004 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 85.506 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.45794240000001,10.0,111.08775359999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.45794240000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.08775359999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 97.53 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 8.224 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.430870399999996,10.0,104.475504,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.430870399999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.475504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.047 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.09 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.394429090909092,10.0,26.152014545454545,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.394429090909092" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.152014545454545" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.692 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.706 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.6166256,10.0,27.761446400000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.6166256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.761446400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.807 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 44.153 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="104.90102400000002,10.0,109.064136,10.0" style="stroke:green;stroke-width:2" /><circle cx="104.90102400000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="109.064136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 44.731 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.107 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1707520000000047,10.0,6.991872000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1707520000000047" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.991872000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.245 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.944 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.2017888,10.0,70.80536640000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.2017888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.80536640000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.583 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.77980000000002,10.0,89.175792,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.77980000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.175792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.969 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 23.961 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.51934400000001,10.0,39.439271999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.51934400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.439271999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.061 / 40 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 60.434 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.0251328,10.0,35.770728000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.0251328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="35.770728000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 72.757 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 42.981 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="96.46428,10.0,127.73935200000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="96.46428" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.73935200000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 47.325 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 39.979 | <svg height="20" width="150"><polyline points="3.033912011837212,3,3.033912011837212,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.01695600591862,10.0,75.01695600591862,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,5.041551101296145,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="5.041551101296145" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 41.255 / 130 | dB | 1000/95.0%/5.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -1.441 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.622208,10.0,72.49760400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.622208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.49760400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.348 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.466 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.35700000000001,10.0,88.94827200000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.35700000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.94827200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.937 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 23.629 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.125344000000013,10.0,40.90044000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.125344000000013" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="40.90044000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.264 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10Hz":<br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ff_mm/ldoota_ac_cmrr_psrr.csv Index:49 <br>
</details><br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 14.986 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="128.95104,10.0,137.283528,10.0" style="stroke:green;stroke-width:2" /><circle cx="128.95104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.283528" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.301 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.084 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.013384,10.0,30.02892,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.013384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="30.02892" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.126 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -2.997 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="129.05544,10.0,139.29006,10.0" style="stroke:green;stroke-width:2" /><circle cx="129.05544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="139.29006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.428 / -2.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.117503059975521,17,5.117503059975521,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.05875152998776,10.0,4.05875152998776,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.05875152998776,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.05875152998776" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 49000.0 / 20.0 | mV | 1000/80.8%/19.2%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 3.847 | <svg height="20" width="150"><polyline points="6.582632126811185,3,6.582632126811185,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.7913160634056,10.0,76.7913160634056,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,38.18353736377768,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="38.18353736377768" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.35 / 10.0 | MV/s | 1000/95.0%/5.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.039 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,105.56983741612335,17,105.56983741612335,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.284918708061674,10.0,54.284918708061674,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.2426820160529,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="92.2426820160529" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.231 / -2.0 | MV/s | 1000/97.9%/2.1%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Input Offset":<br>
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
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:17 <br>
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
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:6 <br>

> **FAIL:** Specification violation for parameter "Slew-Rate (Positive)":<br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/hh_mm/ldoota_tran_slew.csv Index:49 <br>

> **FAIL:** Specification violation for parameter "Slew-Rate (Negative)":<br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:49 <br>
</details><br>


## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.632158399999998,10.0,22.666308799999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.632158399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.666308799999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.227 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.49519072,10.0,13.9460648,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.49519072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.9460648" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.024 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.3876448,10.0,19.1301696,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.3876448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.1301696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.2608208,10.0,22.644820799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.2608208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.644820799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.041 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

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
