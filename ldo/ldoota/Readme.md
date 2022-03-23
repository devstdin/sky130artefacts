23.03.2022, 22:53:11

# LDO OP

OpAmp used in LDO.

![ldoota](resources/ldoota.png "ldoota")

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
| Open-Loop Gain | 60 / 72.134 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.68074399999999,10.0,57.042624000000025,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.68074399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.042624000000025" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.012 / 100 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 90.496 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.82781759999997,10.0,123.94329600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.82781759999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.94329600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 101.994 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.116 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.2744176,10.0,124.230288,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.2744176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.230288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.419 / 15.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.161 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.434283636363638,10.0,27.756276363636363,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.434283636363638" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.756276363636363" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.802 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 60.753 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.483672,10.0,129.364032,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.483672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="129.364032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 137.753 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 41.816 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.07570400000003,10.0,109.41859200000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.07570400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="109.41859200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 44.78 / 50 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.014 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.022288000000003,10.0,5.074239999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.022288000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.074239999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.296 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.734 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.71831040000001,10.0,78.12164208,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.71831040000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.12164208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.434 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.678 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.880232,10.0,90.721632,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.880232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.721632" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.184 / 50 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 27.383 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.15716800000001,10.0,74.912232,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.15716800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.912232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.988 / 40 | dB | 2500/100.0%/0.0%/0.0% |  |

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
| Negative Output Bound | -3 / -2.864 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.102080000000015,10.0,133.23072000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.102080000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="133.23072000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.643 / -1.5 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.65987200000004,10.0,146.74310400000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.65987200000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.74310400000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 2500/100.0%/0.0%/0.0% |  |

<br>

## Input Range Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.08768,10.0,95.27424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.08768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.27424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.039 / -1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>

## Input Range Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.122 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.24768,10.0,95.94816,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.24768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.94816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.032 / -1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

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
| Input Offset | -20.0 / 10.136 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,142.90239864605567,17,142.90239864605567,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.95119932302784,10.0,72.95119932302784,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="108.4028868471343,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="108.4028868471343" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 21.172 / 20.0 | mV | 2500/98.0%/2.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.214 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.146799999999999,10.0,43.144128,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.146799999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="43.144128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.673 / 10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.265 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.2219,10.0,137.29548,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.2219" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.29548" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.539 / -2.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Input Offset":<br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.5_ldoota/batch_7/tt_mm/ldoota_tran_slew.csv Index:49 <br>

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
| THD | 0 / 0.019 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.948328,10.0,19.1321808,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.948328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.1321808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

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
