05.08.2022, 10:23:28

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
| Open-Loop Gain | 60 / 72.178 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.840188000000005,10.0,57.062532,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.840188000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="57.062532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.017 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 90.857 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="91.86873600000001,10.0,124.63104000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="91.86873600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.63104000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.233 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.332 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.37826559999999,10.0,115.07260799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.37826559999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="115.07260799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.783 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.159 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.401643636363637,10.0,27.51210181818182,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.401643636363637" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.51210181818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.785 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 62.432 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.902468800000005,10.0,39.94740480000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="20.902468800000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.94740480000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.658 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 41.3 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="84.35712,10.0,103.436544,10.0" style="stroke:green;stroke-width:2" /><circle cx="84.35712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.436544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.95 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.008 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0121920000000046,10.0,5.031679999999994,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.0121920000000046" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.031679999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.27 / 130 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.41 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.0491304,10.0,77.94161184000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.0491304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.94161184000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.409 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.465 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.34634400000002,10.0,89.38235999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.34634400000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.38235999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.998 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 28.064 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.058208,10.0,76.03636800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.058208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.03636800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 30.144 / 40 | dB | 1000/100.0%/0.0%/0.0% |  |

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
| Negative Output Bound | -3 / -2.865 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="15.977280000000007,10.0,117.2544,10.0" style="stroke:green;stroke-width:2" /><circle cx="15.977280000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.2544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.81 / -1.5 | V | 1000/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.667936,10.0,146.73417600000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.667936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.73417600000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 1000/100.0%/0.0%/0.0% |  |

<br>

## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.08768,10.0,95.27424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.08768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.27424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.039 / -1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>

## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.122 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.24384000000002,10.0,96.02208000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.24384000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.02208000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.031 / -1.5 | V | 1000/100.0%/0.0%/0.0% | Input transistor sat. |

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
| Input Offset | -20.0 / 11.599 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="116.75578800000001,10.0,142.002876,10.0" style="stroke:green;stroke-width:2" /><circle cx="116.75578800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="142.002876" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.612 / 20.0 | mV | 1000/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.305 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.312560000000001,10.0,41.313696,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.312560000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="41.313696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.596 / 10.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.239 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.70556,10.0,137.84484,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.70556" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.84484" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.509 / -2.0 | MV/s | 1000/100.0%/0.0%/0.0% |  |

<br>

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
| THD | 0 / 0.019 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.3350496,10.0,19.9110432,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.3350496" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.9110432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.035 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

<br>

## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.316 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.337815999999975,10.0,56.54776800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.337815999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.54776800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.874 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 78.495 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.26689600000001,10.0,84.85046399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.26689600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.85046399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 88.42 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 8.537 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.929876799999995,10.0,60.9552768,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.929876799999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="60.9552768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.025 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.145 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.19661090909091,10.0,24.554312727272727,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.19661090909091" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="24.554312727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.582 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>

## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.178 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.840943999999986,10.0,56.98686000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.840943999999986" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.98686000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.996 / 100 | dB | 1000/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 77.623 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.75320320000001,10.0,89.01091200000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.75320320000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.01091200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 89.865 / 110 | deg | 1000/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 7.738 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.427948799999996,10.0,77.89612799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.427948799999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.89612799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.201 / 15.0 | MHz | 1000/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.088 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.368014545454542,10.0,25.887956363636363,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.368014545454542" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="25.887956363636363" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.674 / 10.0 | kHz | 1000/100.0%/0.0%/0.0% |  |

<br>

## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.706 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.6166256,10.0,27.761446400000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.6166256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.761446400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.807 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 41.487 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.70402399999998,10.0,90.52975200000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.70402399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.52975200000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.157 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.107 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1707520000000047,10.0,6.991872000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1707520000000047" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.991872000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.245 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -1.766 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.28400800000001,10.0,65.157528,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.28400800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.157528" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.367 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.77980000000002,10.0,89.175792,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.77980000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.175792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.969 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 20.277 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.9911600000000025,10.0,11.429688000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.9911600000000025" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.429688000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 21.171 / 40 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 62.248 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.636616,10.0,37.576876799999994,10.0" style="stroke:green;stroke-width:2" /><circle cx="20.636616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="37.576876799999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.012 / 150 | dB | 1000/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 39.409 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.743648,10.0,100.21130400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.743648" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.21130400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.502 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.037 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0596319999999992,10.0,5.061584000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.0596319999999992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.061584000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.288 / 130 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -2.087 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.971872000000005,10.0,69.2796936,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.971872000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.2796936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.794 / 10 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.759 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.467824,10.0,90.177672,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.467824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.177672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.108 / 50 | dB | 1000/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 19.853 | <svg height="20" width="150"><polyline points="4.047768381646719,3,4.047768381646719,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.52388419082335,10.0,75.52388419082335,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,15.923596499457226,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="15.923596499457226" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 21.662 / 40 | dB | 1000/90.0%/10.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "PSRR- at 10MHz":<br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_2/ss_mm/ldoota_ac_cmrr_psrr.csv Index:49 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_3/ss_mm/ldoota_ac_cmrr_psrr.csv Index:49 <br>

## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,137.283312,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.0" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.283312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.301 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.004 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.106392,10.0,27.013344,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.106392" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.013344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.001 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -2.63 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,118.19999999999999,17,118.19999999999999,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.599999999999994,10.0,60.599999999999994,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="109.12396799999999,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="109.12396799999999" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 0.0 / -2.0 | MV/s | 5/80.0%/20.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Slew-Rate (Negative)":<br>
> **FAIL:** group:ll file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_0/ll/ldoota_tran_slew.csv Index:0 <br>

## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.117503059975521,17,5.117503059975521,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.05875152998776,10.0,4.05875152998776,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.05875152998776,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.05875152998776" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 49000.0 / 20.0 | mV | 1000/76.5%/23.5%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 3.84 | <svg height="20" width="150"><polyline points="6.737618435671841,3,6.737618435671841,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.86880921783592,10.0,76.86880921783592,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,30.142477358339868,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="30.142477358339868" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.001 / 10.0 | MV/s | 1000/95.0%/5.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -2.643 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,75.36087726257293,17,75.36087726257293,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.180438631286464,10.0,39.180438631286464,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.54270092627576,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="69.54270092627576" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.92 / -2.0 | MV/s | 1000/79.8%/20.2%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Input Offset":<br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ff_mm/ldoota_tran_slew.csv Index:34 <br>
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
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ff_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ff_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ff_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ff_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_1/ff_mm/ldoota_tran_slew.csv Index:4 <br>

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

> **FAIL:** Specification violation for parameter "Slew-Rate (Negative)":<br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ll_mm/ldoota_tran_slew.csv Index:49 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.5_ldoota_ext/batch_2/ff_mm/ldoota_tran_slew.csv Index:34 <br>
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

## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.632158399999998,10.0,22.666308799999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.632158399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.666308799999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.227 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.4951936,10.0,13.94606912,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.4951936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.94606912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.025 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="15.1267728,10.0,20.2219728,10.0" style="stroke:green;stroke-width:2" /><circle cx="15.1267728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.2219728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.036 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>

## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.023 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.9591008,10.0,22.4417232,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.9591008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.4417232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.041 / 0.3 | % | 1000/100.0%/0.0%/0.0% |  |

<br>

# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__fa85d0e9390d57bbdc389bd17fc02e0e](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__fa85d0e9390d57bbdc389bd17fc02e0e.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a46a4de390151646e4774131fbac640d](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a46a4de390151646e4774131fbac640d.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a46a4de390151646e4774131fbac640d](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a46a4de390151646e4774131fbac640d.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a46a4de390151646e4774131fbac640d](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a46a4de390151646e4774131fbac640d.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a46a4de390151646e4774131fbac640d](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a46a4de390151646e4774131fbac640d.png "") |
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

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a58239f7b3bfff0eb4aa728b02e2903e.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__72923b63b9e25e820ea35c02d808c241](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__72923b63b9e25e820ea35c02d808c241.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__72923b63b9e25e820ea35c02d808c241](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__72923b63b9e25e820ea35c02d808c241.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_neg_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__fe2d4c4159e8b2a17f5409a1ae68be42](histplot_neg_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__fe2d4c4159e8b2a17f5409a1ae68be42.png "") |
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

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8da56df253519e1d9c1b0d2dfbbf5209](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8da56df253519e1d9c1b0d2dfbbf5209.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8da56df253519e1d9c1b0d2dfbbf5209](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8da56df253519e1d9c1b0d2dfbbf5209.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8da56df253519e1d9c1b0d2dfbbf5209](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8da56df253519e1d9c1b0d2dfbbf5209.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__452d3dc177265d4ca87b7a218428cdae](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__452d3dc177265d4ca87b7a218428cdae.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8898fb89836f6a51ae81985662057d9f](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__8898fb89836f6a51ae81985662057d9f.png "") |
| :-- |
|  |
<br>
