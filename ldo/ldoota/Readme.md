27.02.2023, 15:07:43

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
| Open-Loop Gain | 60 / 72.189 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.878708,10.0,57.01043999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.878708" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.01043999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.003 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 90.618 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="91.17983999999998,10.0,125.24044799999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="91.17983999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.24044799999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.445 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.003 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.6442656,10.0,115.71628799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.6442656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="115.71628799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.828 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.163 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.462545454545456,10.0,27.187723636363636,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.462545454545456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.187723636363636" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.763 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 61.752 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.923067200000002,10.0,33.73785120000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.923067200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="33.73785120000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 71.346 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 41.883 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.55687999999999,10.0,106.94575199999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.55687999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.94575199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 44.437 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.026 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.042240000000004,10.0,5.068687999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.042240000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.068687999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.293 / 130 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.586 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.7838888,10.0,77.57128920000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.7838888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.57128920000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.357 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.469 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.37874400000001,10.0,89.839848,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.37874400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.839848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.061 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 27.754 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.827935999999994,10.0,74.96601600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.827935999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.96601600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.995 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

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
| Negative Output Bound | -3 / -2.858 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.59744000000002,10.0,132.26112,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.59744000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="132.26112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.654 / -1.5 | V | 1000/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.66390399999995,10.0,146.732736,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.66390399999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.732736" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 1000/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.08768,10.0,95.27424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.08768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.27424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.039 / -1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.124 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.08831999999998,10.0,95.86272,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.08831999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.86272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.033 / -1.5 | V | 1000/100.0%/0.0%/0.0% | Input transistor sat. |

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
| Input Offset | -20.0 / 14.139 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,146.13745370397984,17,146.13745370397984,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.56872685198992,10.0,74.56872685198992,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="125.16377310327965,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="125.16377310327965" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 20.241 / 20.0 | mV | 1000/95.0%/5.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.255 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.116712,10.0,41.715264,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.116712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="41.715264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.613 / 10.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.201 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="125.39082,10.0,137.8038,10.0" style="stroke:green;stroke-width:2" /><circle cx="125.39082" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.8038" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.511 / -2.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Input Offset":<br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_1/ff_mm/ldoota_tran_slew.csv Index:49 <br>
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
| THD | 0 / 0.019 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.1815888,10.0,19.9078656,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.1815888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.9078656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.035 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.316 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.337815999999975,10.0,56.54776800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.337815999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.54776800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.874 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 86.605 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.62124800000001,10.0,107.16968639999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.62124800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.16968639999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.17 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.328 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.3300112,10.0,73.12215359999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.3300112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="73.12215359999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.87 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.162 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.45426909090909,10.0,24.918167272727274,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.45426909090909" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="24.918167272727274" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.607 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.894656,10.0,56.977932,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.894656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.977932" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.994 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 85.237 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.68126399999998,10.0,109.5979296,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.68126399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="109.5979296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 97.013 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 8.209 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.2154464,10.0,97.00766399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.2154464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="97.00766399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.528 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.096 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.490036363636364,10.0,26.360785454545457,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.490036363636364" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.360785454545457" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.706 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.706 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.6166256,10.0,27.761446400000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.6166256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.761446400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.807 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 42.571 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="93.51055199999999,10.0,96.71512800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="93.51055199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.71512800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.016 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.107 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1707520000000047,10.0,6.991872000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1707520000000047" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.991872000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.245 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.97 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.01452400000001,10.0,70.6508328,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.01452400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.6508328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.604 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.77980000000002,10.0,89.175792,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.77980000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.175792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.969 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 23.891 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.017936000000013,10.0,39.441936,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.017936000000013" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.441936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.061 / 40 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 61.83 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.035516799999996,10.0,41.28909600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="20.035516799999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="41.28909600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 76.59 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 40.72 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.18119200000002,10.0,107.49100799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.18119200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.49100799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 44.513 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1497600000000032,10.0,7.015088000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1497600000000032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.015088000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.259 / 130 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -1.303 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.615736,10.0,72.8326776,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.615736" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.8326776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.301 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.671 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.82932800000002,10.0,90.73552800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.82932800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.73552800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.185 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 23.544 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="28.514999999999997,10.0,41.73549600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="28.514999999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="41.73549600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.38 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,137.283456,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.0" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.283456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.301 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.247984000000001,10.0,30.392904,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.247984000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="30.392904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.141 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -2.703 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,118.19999999999999,17,118.19999999999999,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.599999999999994,10.0,60.599999999999994,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="108.08054399999999,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="108.08054399999999" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 0.0 / -2.0 | MV/s | 5/80.0%/20.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Slew-Rate (Negative)":<br>
> **FAIL:** group:ll file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll/ldoota_tran_slew.csv Index:0 <br>
</details><br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.117503059975521,17,5.117503059975521,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.05875152998776,10.0,4.05875152998776,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.05875152998776,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.05875152998776" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 49000.0 / 20.0 | mV | 1000/81.6%/18.4%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 3.992 | <svg height="20" width="150"><polyline points="3.191457106771851,3,3.191457106771851,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.09572855338592,10.0,75.09572855338592,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,32.21707832971704,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="32.21707832971704" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.211 / 10.0 | MV/s | 1000/95.0%/5.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -2.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,118.19943552276594,17,118.19943552276594,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.59971776138297,10.0,60.59971776138297,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="107.01544232433261,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="107.01544232433261" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 0.0 / -2.0 | MV/s | 1000/80.0%/20.0%/0.0% |  |

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

> **FAIL:** Specification violation for parameter "Slew-Rate (Positive)":<br>
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
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:0 <br>
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
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_3/ll_mm/ldoota_tran_slew.csv Index:0 <br>
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
| THD | 0 / 0.024 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.488857600000001,10.0,19.311192000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.488857600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.311192000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.209979200000001,10.0,21.849072,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.209979200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="21.849072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.039 / 0.3 | % | 999/100.0%/0.0%/0.0% |  |

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
