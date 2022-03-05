05.03.2022, 13:28:15

# LDO OP

OpAmp used in LDO.

![placeholder](resources/img-placeholder.png "Placeholder")

<br>

[🔗 Schematics](ldoota_sch.pdf)<br>

# SPECIFICATIONS

## AC Open-Loop Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.315 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.33302799999999,10.0,56.527752,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.33302799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.527752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.869 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 91.621 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="94.06911359999998,10.0,119.61868799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="94.06911359999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.61868799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 100.493 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 10.395 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.690592,10.0,92.2584,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.690592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="92.2584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.198 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.233 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.48506181818182,10.0,26.335272727272727,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.48506181818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.335272727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.704 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>

## AC Open-Loop Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.143 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.716167999999975,10.0,57.10807199999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.716167999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.10807199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.03 / 100 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 90.311 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.29544959999998,10.0,124.59475199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.29544959999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.59475199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.22 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.078 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.7279664,10.0,131.07316799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.7279664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="131.07316799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.894 / 15.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.167 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.519505454545452,10.0,27.874749090909088,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.519505454545452" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.874749090909088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.81 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>

## CMRR/PSRR Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.708 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.618799999999993,10.0,27.7513088,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.618799999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.7513088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.8 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 42.746 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="94.767744,10.0,100.50405600000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="94.767744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.50405600000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.542 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.105 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.168016,10.0,6.982255999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.168016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.982255999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.239 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.202 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.5435264,10.0,75.93379752,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.5435264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.93379752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.13 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.801 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.76604800000001,10.0,89.13287999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.76604800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.13287999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.963 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 28.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.60302399999999,10.0,71.698872,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.60302399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.698872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.542 / 40 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## CMRR/PSRR Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 62.352 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.7868656,10.0,37.96458239999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="20.7868656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="37.96458239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.281 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 41.543 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="86.10679200000003,10.0,110.68903199999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="86.10679200000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.68903199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 44.957 / 50 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.043 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0690240000000015,10.0,5.079776000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.0690240000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.079776000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.3 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.418 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.9900328,10.0,79.80595536000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.9900328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.80595536000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.667 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.643 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.6278,10.0,93.13442400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.6278" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.13442400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.519 / 50 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 27.713 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.530144000000014,10.0,76.279656,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.530144000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.279656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 30.178 / 40 | dB | 2500/100.0%/0.0%/0.0% |  |

<br>

## Output Range Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -3 / -2.857 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.729919999999993,10.0,93.30431999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.729919999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.30431999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.059 / -1.5 | V | 5/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.67168000000004,10.0,146.73302400000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.67168000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.73302400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 5/100.0%/0.0%/0.0% |  |

<br>

## Output Range Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -3 / -2.867 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="15.744000000000014,10.0,123.1728,10.0" style="stroke:green;stroke-width:2" /><circle cx="15.744000000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.1728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.748 / -1.5 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.663328,10.0,146.73907199999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.663328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.73907199999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 2500/100.0%/0.0%/0.0% |  |

<br>

## Input Range Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.08768,10.0,95.27424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.08768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.27424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.039 / -1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>

## Input Range Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.125 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.01055999999998,10.0,96.19871999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.01055999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.19871999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.029 / -1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

<br>

## Slew-Rate/Offset Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 14.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="128.995968,10.0,137.271648,10.0" style="stroke:green;stroke-width:2" /><circle cx="128.995968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.271648" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.298 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.369 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.858232000000001,10.0,38.58324,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.858232000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.58324" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.483 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.194 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="125.51700000000001,10.0,136.3773,10.0" style="stroke:green;stroke-width:2" /><circle cx="125.51700000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="136.3773" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.59 / -2.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>

## Slew-Rate/Offset Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 13.053 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="121.99105200000001,10.0,143.522724,10.0" style="stroke:green;stroke-width:2" /><circle cx="121.99105200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="143.522724" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 19.034 / 20.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.206 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.9443600000000005,10.0,50.267904,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.9443600000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="50.267904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.969 / 10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.268 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.17798,10.0,137.52102,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.17798" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.52102" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.527 / -2.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>

## Noise Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.6334976,10.0,22.653622399999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.6334976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.653622399999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.226 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.49587904,10.0,13.941122720000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.49587904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.941122720000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## THD Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.228867200000002,10.0,17.2348992,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.228867200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.2348992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.03 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>

## THD Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.019 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.3341664,10.0,19.215504,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.3341664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.215504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>

# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__fa85d0e9390d57bbdc389bd17fc02e0e](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__fa85d0e9390d57bbdc389bd17fc02e0e.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0c4d3f4b2844ed0d2092b49ccebd0f67](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0c4d3f4b2844ed0d2092b49ccebd0f67.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0c4d3f4b2844ed0d2092b49ccebd0f67](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0c4d3f4b2844ed0d2092b49ccebd0f67.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0c4d3f4b2844ed0d2092b49ccebd0f67](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0c4d3f4b2844ed0d2092b49ccebd0f67.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0c4d3f4b2844ed0d2092b49ccebd0f67](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0c4d3f4b2844ed0d2092b49ccebd0f67.png "") |
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

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0cd43187be4232c17f0d97b8c5c4a553.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__29cf4e18105d8127d193643acb44425f](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__29cf4e18105d8127d193643acb44425f.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__29cf4e18105d8127d193643acb44425f](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__29cf4e18105d8127d193643acb44425f.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_neg_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__47a910469d8bcef86e1a5d2c08556695](histplot_neg_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__47a910469d8bcef86e1a5d2c08556695.png "") |
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

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4ed39a545bd77b4fbc085c8e4c9f1b2c](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4ed39a545bd77b4fbc085c8e4c9f1b2c.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4ed39a545bd77b4fbc085c8e4c9f1b2c](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4ed39a545bd77b4fbc085c8e4c9f1b2c.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4ed39a545bd77b4fbc085c8e4c9f1b2c](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4ed39a545bd77b4fbc085c8e4c9f1b2c.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__452d3dc177265d4ca87b7a218428cdae](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__452d3dc177265d4ca87b7a218428cdae.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__9f61d6b2437fe1c0f04fe46a41a7a912](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__9f61d6b2437fe1c0f04fe46a41a7a912.png "") |
| :-- |
|  |
<br>
