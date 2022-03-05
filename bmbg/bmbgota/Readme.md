05.03.2022, 14:43:36

# Beta-Multiplier Bandgap OTA

OTA for Beta-Multiplier Bandgap.

![bmbgota](resources/bmbgota.png "bmbgota")

<br>

[🔗 Schematics](bmbgota_sch.pdf)<br>

# SPECIFICATIONS

## AC Open-Loop Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.324 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.53107199999995,10.0,50.80841599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.53107199999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="50.80841599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.362 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 96.026 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="106.75413119999999,10.0,117.0209568,10.0" style="stroke:green;stroke-width:2" /><circle cx="106.75413119999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.0209568" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 99.591 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 61.392 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.65305788235294,10.0,104.15884799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.65305788235294" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.15884799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.712 / 110.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.438 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.922077090909092,10.0,11.669146181818181,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.922077090909092" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.669146181818181" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.559 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>

## AC Open-Loop Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.239 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.92044000000002,10.0,51.300752000000024,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.92044000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.300752000000024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.431 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 94.245 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="101.625456,10.0,125.63500799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="101.625456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.63500799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.582 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 55.598 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.83713694117647,10.0,124.38361411764706,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.83713694117647" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.38361411764706" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.65 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.419 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.636567272727273,10.0,10.081294545454547,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.636567272727273" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.081294545454547" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.587 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>

## CMRR/PSRR Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.211 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.3431488,10.0,65.1178832,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.3431488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.1178832" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.749 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 50 / 67.334 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.40135599999999,10.0,91.82852399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.40135599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.82852399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.675 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.522 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.23544,10.0,93.206208,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.23544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.206208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.379 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 40 / 52.711 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.01083200000002,10.0,67.50142399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.01083200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.50142399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 53.021 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 84.449 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.86713142857141,10.0,74.48345142857143,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.86713142857141" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.48345142857143" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.749 / 120 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.925 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.278531199999996,10.0,67.188864,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.278531199999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.188864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.686 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## CMRR/PSRR Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.421 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.206081599999997,10.0,73.45986239999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.206081599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="73.45986239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 98.93 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 50 / 61.322 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.75790400000001,10.0,138.031896,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.75790400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="138.031896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.509 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 61.608 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="37.57296,10.0,110.84832,10.0" style="stroke:green;stroke-width:2" /><circle cx="37.57296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.84832" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 107.405 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 40 / 50.951 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.56691199999999,10.0,70.98806400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.56691199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.98806400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 54.164 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.529 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.91675885714285,10.0,78.33851657142856,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.91675885714285" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.33851657142856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 86.623 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.784 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.9227904,10.0,69.13209599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.9227904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.13209599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.889 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<br>

## Output Range Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -2.5 / -2.267 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.04064,10.0,72.41951999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.04064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.41951999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.259 / -2 | V | 5/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.08633600000003,10.0,38.59852800000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.08633600000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.59852800000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.124 / 2.5 | V | 5/100.0%/0.0%/0.0% |  |

<br>

## Output Range Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -2.5 / -2.269 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.59424000000001,10.0,72.67295999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.59424000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.67295999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.258 / -2 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.095 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.256608000000057,10.0,39.940032000000045,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.256608000000057" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.940032000000045" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.128 / 2.5 | V | 2500/100.0%/0.0%/0.0% |  |

<br>

## Input Range Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.905 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.696582857142857,10.0,59.34555428571426,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.696582857142857" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.34555428571426" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.074 / 1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>

## Input Range Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.892 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.92711314285713,10.0,62.00626285714283,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.92711314285713" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.00626285714283" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.087 / 1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

<br>

## Slew-Rate/Offset Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.28975488,10.0,78.43071432,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.28975488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.43071432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.877 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.313103999999996,10.0,75.263088,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.313103999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.263088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.037 / 30.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -21.617 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.359759999999994,10.0,95.65896,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.359759999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.65896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -17.131 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>

## Slew-Rate/Offset Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -3.783 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.765712,10.0,112.2763944,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.765712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="112.2763944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.177 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.366 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.636784,10.0,80.02776,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.636784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.02776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.698 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -22.302 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.42776,10.0,98.31432,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.42776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="98.31432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -16.762 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>

## Noise Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 0.937 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.498163999999996,10.0,19.707627199999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.498163999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.707627199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.021 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.569180639999999,10.0,12.1278848,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.569180639999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.1278848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.049 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## THD Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.101 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.540576,10.0,65.67307199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.540576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.67307199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.131 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>

## THD Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.0969456,10.0,72.61843200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.0969456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.61843200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.145 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

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
