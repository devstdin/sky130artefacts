01.11.2023, 19:18:56

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
| Open-Loop Gain | 60 / 72.176 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.83338399999999,10.0,57.016523999999976,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.83338399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.016523999999976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.005 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 90.875 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="91.91945279999999,10.0,125.894496,10.0" style="stroke:green;stroke-width:2" /><circle cx="91.91945279999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.894496" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.672 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.22 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.773543999999994,10.0,115.256064,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.773543999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="115.256064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.796 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.342254545454544,10.0,27.613527272727275,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.342254545454544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.613527272727275" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.792 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 60.571 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.2224704,10.0,39.92724479999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.2224704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.92724479999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.644 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 41.551 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="86.16619200000001,10.0,104.20024800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="86.16619200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.20024800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 44.056 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.063 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.100608,10.0,7.084847999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.100608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.084847999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.303 / 130 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.923 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.3555376,10.0,77.93920200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.3555376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.93920200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.408 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.454 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.27175200000002,10.0,90.02143199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.27175200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.02143199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.086 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 27.582 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.586872000000014,10.0,72.610968,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.586872000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.610968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.668 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

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
| Negative Output Bound | -3 / -2.859 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.57632000000001,10.0,108.6336,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.57632000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.6336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.9 / -1.5 | V | 1000/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.66275200000007,10.0,146.74079999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.66275200000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.74079999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 1000/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.08768,10.0,95.27424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.08768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.27424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.039 / -1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.122 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.30720000000001,10.0,96.64799999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.30720000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.64799999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.025 / -1.5 | V | 1000/100.0%/0.0%/0.0% | Input transistor sat. |

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
| Input Offset | -20.0 / 12.834 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,145.35360933127907,17,145.35360933127907,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.17680466563954,10.0,74.17680466563954,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="119.85067551236178,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="119.85067551236178" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 20.463 / 20.0 | mV | 1000/95.0%/5.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.165 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.961512,10.0,42.936192,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.961512" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="42.936192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.664 / 10.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.252 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.45824,10.0,137.47152,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.45824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.47152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.529 / -2.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Input Offset":<br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_0/ll_mm/ldoota_tran_slew.csv Index:49 <br>
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
| THD | 0 / 0.02 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.4350624,10.0,19.6325376,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.4350624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.6325376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.035 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.316 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.337815999999975,10.0,56.54776800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.337815999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.54776800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.874 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 87.291 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.5987712,10.0,108.8347008,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.5987712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.8347008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.748 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.391 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.2336112,10.0,74.1942912,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.2336112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.1942912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.944 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.158 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.38890181818182,10.0,24.82669090909091,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.38890181818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="24.82669090909091" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.601 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.15 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.739928,10.0,57.00115200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.739928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.00115200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.0 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 86.253 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.61002239999999,10.0,111.37782720000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.61002239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.37782720000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 97.631 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 8.159 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.4830336,10.0,96.785472,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.4830336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.785472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.513 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.093 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.44178909090909,10.0,26.26461090909091,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.44178909090909" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.26461090909091" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.699 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.706 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.6166256,10.0,27.761446400000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.6166256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.761446400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.807 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 43.113 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="97.41079199999997,10.0,101.17984800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="97.41079199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.17984800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.636 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.107 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1707520000000047,10.0,6.991872000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1707520000000047" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.991872000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.245 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.911 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.4395832,10.0,71.0257152,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.4395832" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.0257152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.552 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.77980000000002,10.0,89.175792,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.77980000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.175792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.969 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 24.21 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="33.310704,10.0,41.321135999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="33.310704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="41.321135999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.322 / 40 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 62.265 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.661859200000002,10.0,35.6077776,10.0" style="stroke:green;stroke-width:2" /><circle cx="20.661859200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="35.6077776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 72.644 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 40.651 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.68914399999998,10.0,123.13012799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.68914399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.13012799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 46.685 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.067 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.106528000000003,10.0,7.02088,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.106528000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.02088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.263 / 130 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -1.434 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.67232,10.0,75.24722352,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.67232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.24722352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.43 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.09383999999999,10.0,89.604192,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.09383999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.604192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.028 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 23.802 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.372312,10.0,44.598144,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.372312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="44.598144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.778 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,137.2836,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.0" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.2836" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.301 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.084 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.013192,10.0,30.03108,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.013192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="30.03108" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.126 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -2.7 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,118.19999999999999,17,118.19999999999999,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.599999999999994,10.0,60.599999999999994,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="108.12273599999999,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="108.12273599999999" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 0.0 / -2.0 | MV/s | 5/80.0%/20.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Slew-Rate (Negative)":<br>
> **FAIL:** group:ll file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll/ldoota_tran_slew.csv Index:0 <br>
</details><br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.117503059975521,17,5.117503059975521,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.05875152998776,10.0,4.05875152998776,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.05875152998776,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.05875152998776" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 49000.0 / 20.0 | mV | 1000/80.9%/19.1%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 3.903 | <svg height="20" width="150"><polyline points="5.295285726891061,3,5.295285726891061,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.14764286344554,10.0,76.14764286344554,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,34.42561830982358,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="34.42561830982358" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.233 / 10.0 | MV/s | 1000/95.0%/5.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.068 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,107.05287764917091,17,107.05287764917091,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.026438824585455,10.0,55.026438824585455,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="93.1641596727537,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="93.1641596727537" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.071 / -2.0 | MV/s | 1000/97.8%/2.2%/0.0% |  |

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
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:15 <br>
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
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:48 <br>
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
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:23 <br>
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
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:48 <br>
</details><br>


## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.632158399999998,10.0,22.666308799999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.632158399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.666308799999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.227 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.49518928,10.0,13.9460648,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.49518928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.9460648" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.024 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.4150672,10.0,19.167657600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.4150672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.167657600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.234176,10.0,21.83328,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.234176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="21.83328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.039 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

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
