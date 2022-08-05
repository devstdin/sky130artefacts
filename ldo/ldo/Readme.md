05.08.2022, 13:57:48

# 1.8 V LDO

1.8 V linear regulator.

![ldo](resources/ldo.png "ldo")

<br>

[🔗 Schematics](ldo_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](ldo_lvs_ldo_netgen_comp.out)<br>

# SPECIFICATIONS

## LDO Voltage Curvature vs Temperature <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.88967999999996,10.0,63.38136000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.88967999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.38136000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 4.837 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.785977216,10.0,8.604164352,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.785977216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.604164352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.729 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.27480000000003,10.0,62.155920000000116,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.27480000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.155920000000116" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 24.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.8332984,10.0,110.9534232,10.0" style="stroke:green;stroke-width:2" /><circle cx="92.8332984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.9534232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.935 / 100.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.763 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.508320000000076,10.0,62.70672000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.508320000000076" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.70672000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.783 / 1.9 | V | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.926 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.533160288,10.0,8.73994944,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.533160288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.73994944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.965 / 250.0 | mV | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.763 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.10584000000009,10.0,61.43808000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.10584000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.43808000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 1.9 | V | 800/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 2.589 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.8643104,10.0,113.5587504,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.8643104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="113.5587504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 53.554 / 100.0 | uV/°C | 1000/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.59736000000003,10.0,59.97216000000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.59736000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.97216000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.779 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 12.387 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.3511936,10.0,108.92519039999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.3511936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.92519039999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.39 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.10776000000002,10.0,59.05632000000011,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.10776000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.05632000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.778 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 3.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.6925532,10.0,93.082458,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.6925532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.082458" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.023 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.95696000000001,10.0,63.14736000000009,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.95696000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.14736000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 1.9 | V | 998/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.68 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.7957056,10.0,88.4610624,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.7957056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.4610624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.837 / 25.0 | mV | 998/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.392480000000084,10.0,62.57856000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.392480000000084" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.57856000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.783 / 1.9 | V | 998/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.1 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.761692,10.0,90.6748968,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.761692" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.6748968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.354 / 20.0 | mV/V | 998/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs Load <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.766160000000006,10.0,66.37008000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.766160000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.37008000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.822 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.735257984,10.0,18.3239328,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.735257984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.3239328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.66 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.778 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.905840000000026,10.0,66.79631999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.905840000000026" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.79631999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -7.274 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.626407999999998,10.0,59.262816,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.626407999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.262816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.186 / 10 | V/A | 15/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs Load (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.773 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.79832000000003,10.0,66.68472000000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.79832000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.68472000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 975/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.135 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.54041664,10.0,12.66872,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.54041664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.66872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.331 / 25.0 | mV | 975/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.774 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.0035200000001,10.0,66.89927999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.0035200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.89927999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 975/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.595 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.119240000000005,10.0,53.16888,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.119240000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.16888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.032 / 10 | V/A | 975/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 1.789 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.576443680000001,10.0,7.76334704,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.576443680000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.76334704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.919 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2639068704,10.0,5.2809036224,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2639068704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.2809036224" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.098 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -43.785 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="133.37544000000003,10.0,137.65404,10.0" style="stroke:green;stroke-width:2" /><circle cx="133.37544000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.65404" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.596 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 1.687 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.0980944,10.0,62.45923679999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.0980944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.45923679999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.387 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -43.886 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.31111384615384,10.0,88.86387692307692,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.31111384615384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.86387692307692" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.484 / 10 | dB | 993/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 1.521 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="122.82467439999999,10.0,125.97561959999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="122.82467439999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.97561959999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.48 / 20 | dB | 993/100.0%/0.0%/0.0% |  |

<br>

## Line Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.845 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.0326784,10.0,75.6149664,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.0326784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.6149664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.214 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Line Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 19.966 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.5028864,10.0,78.7482624,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.5028864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.7482624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.301 / 50.0 | mV | 985/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Load Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.938 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.581146239999999,10.0,11.9730848,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.581146239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.9730848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.421 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## Load Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.294 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.72663936,10.0,10.52537376,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.72663936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.52537376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.613 / 50.0 | mV | 999/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## AC Loopgain PM Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.689 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.935146666666666,10.0,19.930133333333334,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.935146666666666" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.930133333333334" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 60.872 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>

## AC Loopgain PM Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.57 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.807786666666667,10.0,20.853866666666665,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.807786666666667" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.853866666666665" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.738 / 180 | deg | 1000/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.64 | <svg height="20" width="150"><polyline points="5.1511338690275394,3,5.1511338690275394,17,12.27810557173284,17,12.27810557173284,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.71461972038019,10.0,8.71461972038019,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.681 / 1.9 | V | 15/80.0%/20.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 4.835 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,22.47323809116829,17,22.47323809116829,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.736619045584145,10.0,12.736619045584145,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.3766311189917624,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.3766311189917624" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1848.691 / 250.0 | mV | 15/80.0%/20.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,10.470588448913883,17,10.470588448913883,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.735294224456942,10.0,6.735294224456942,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.65997772312028,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="5.65997772312028" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.555 / 1.9 | V | 15/86.6667%/13.3333%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 24.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,9.574429850833493,17,9.574429850833493,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.287214925416746,10.0,6.287214925416746,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.1012894283168,10.0,147.00000000000003,10.0" style="stroke:red;stroke-width:2" /><circle cx="7.1012894283168" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.00000000000003" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 4280.608 / 100.0 | uV/°C | 15/86.6667%/13.3333%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Mean LDO Voltage":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>
> **FAIL:** group:tt file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/tt/ldo_tran_temp.csv Index:1 <br>
> **FAIL:** group:ll file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/ll/ldo_tran_temp.csv Index:2 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage Curvature":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>
> **FAIL:** group:tt file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/tt/ldo_tran_temp.csv Index:1 <br>
> **FAIL:** group:ll file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/ll/ldo_tran_temp.csv Index:2 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage at 20°C":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>
> **FAIL:** group:tt file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/tt/ldo_tran_temp.csv Index:1 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>
> **FAIL:** group:tt file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/tt/ldo_tran_temp.csv Index:1 <br>

## LDO Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.97848000000009,10.0,63.223680000000044,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.97848000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.223680000000044" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 1.9 | V | 993/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.607 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.925896384,10.0,8.386440384,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.925896384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.386440384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.351 / 250.0 | mV | 993/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.77112000000004,10.0,59.754720000000056,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.77112000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.754720000000056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.779 / 1.9 | V | 793/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 6.481 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.66614864,10.0,110.7783408,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.66614864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.7783408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.692 / 100.0 | uV/°C | 993/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.59448000000011,10.0,59.977920000000076,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.59448000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.977920000000076" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.779 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 12.375 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.280864,10.0,108.9538176,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.280864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.9538176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.395 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.1048800000001,10.0,59.06208000000012,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.1048800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.06208000000012" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.778 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 3.8 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.6783548,10.0,93.08983080000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.6783548" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.08983080000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.025 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.766 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.43935999999997,10.0,62.51664000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.43935999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.51664000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.783 / 1.9 | V | 998/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.677 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.77796479999999,10.0,88.1018112,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.77796479999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.1018112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.775 / 25.0 | mV | 998/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.792079999999984,10.0,61.85928000000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.792079999999984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.85928000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 998/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.754456,10.0,90.6037536,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.754456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.6037536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.334 / 20.0 | mV/V | 998/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs Load [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.758240000000015,10.0,66.37728000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.758240000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.37728000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.821 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.731389568,10.0,18.3250848,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.731389568" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.3250848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.661 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.778 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.897920000000035,10.0,66.80352000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.897920000000035" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.80352000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -7.277 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.603008000000003,10.0,59.289816,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.603008000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.289816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.182 / 10 | V/A | 15/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs Load (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.773 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.25832000000001,10.0,71.70312,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.25832000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.70312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.795 / 1.9 | V | 980/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.137 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.55051392,10.0,13.01785664,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.55051392" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.01785664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.392 / 25.0 | mV | 975/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.773 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.4613600000001,10.0,68.106,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.4613600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.106" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.79 / 1.9 | V | 979/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.685 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.467136,10.0,53.123592,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.467136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.123592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.038 / 10 | V/A | 988/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 1.789 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.57621904,10.0,7.76445152,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.57621904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.76445152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.92 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2638840032,10.0,5.2809663488,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2638840032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.2809663488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.098 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -43.792 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="133.34844,10.0,137.6544,10.0" style="stroke:green;stroke-width:2" /><circle cx="133.34844" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.6544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.596 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 3.872 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.5871312,10.0,73.2536192,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.5871312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="73.2536192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.22 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -43.886 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.31144615384615,10.0,88.86708923076924,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.31144615384615" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.86708923076924" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.481 / 10 | dB | 993/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 3.692 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="125.42994399999999,10.0,128.3769168,10.0" style="stroke:green;stroke-width:2" /><circle cx="125.42994399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.3769168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.481 / 20 | dB | 993/100.0%/0.0%/0.0% |  |

<br>

## Line Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 22.03 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.4456224,10.0,78.9780288,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.4456224" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.9780288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.381 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Line Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 21.026 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.554159999999996,10.0,82.5631392,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.554159999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.5631392" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 27.626 / 50.0 | mV | 975/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Load Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 2.235 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.43639392,10.0,12.5992256,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.43639392" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.5992256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.639 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## Load Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 2.129 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.130151999999999,10.0,13.0114112,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.130151999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.0114112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.782 / 50.0 | mV | 987/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## AC Loopgain PM Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 42.144 | <svg height="20" width="150"><polyline points="5.983389200768045,3,5.983389200768045,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.49169460038402,10.0,76.49169460038402,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,15.539719316011405,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="15.539719316011405" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 54.149 / 180 | deg | 5/80.0%/20.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Loopgain PM":<br>
> **FAIL:** group:ll file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_0/ll/ldo_ac_loop.csv Index:0 <br>

## AC Loopgain PM Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 41.003 | <svg height="20" width="150"><polyline points="7.140866349633445,3,7.140866349633445,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.07043317481671,10.0,77.07043317481671,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,17.038956236465538,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="17.038956236465538" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 54.554 / 180 | deg | 1000/80.0%/20.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Loopgain PM":<br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_2/ll_mm/ldo_ac_loop.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:49 <br>

# PERFORMANCE CHARACTERISTICS

## LDO Output Voltage vs Temperature<br>

| ![xyplot_temp-sweepv(vldo)v(vdd)_('tt',_-2)__744781268f63d499334ec11aa5b1bf9b](xyplot_temp-sweepv(vldo)v(vdd)_('tt',_-2)__744781268f63d499334ec11aa5b1bf9b.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Temperature (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__039ad239ed89ffb7ad1e14935c65285b](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__039ad239ed89ffb7ad1e14935c65285b.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__039ad239ed89ffb7ad1e14935c65285b](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__039ad239ed89ffb7ad1e14935c65285b.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__039ad239ed89ffb7ad1e14935c65285b](histplot_vldo_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__039ad239ed89ffb7ad1e14935c65285b.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__039ad239ed89ffb7ad1e14935c65285b](histplot_vldo_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__039ad239ed89ffb7ad1e14935c65285b.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs VDD<br>

| ![xyplot_v(v-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4a17ff07c51788f19fb3341308999003](xyplot_v(v-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4a17ff07c51788f19fb3341308999003.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs VDD (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__481a75f3b02fc6069e365a8181e104d0](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__481a75f3b02fc6069e365a8181e104d0.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__481a75f3b02fc6069e365a8181e104d0](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__481a75f3b02fc6069e365a8181e104d0.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__481a75f3b02fc6069e365a8181e104d0](histplot_vldo_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__481a75f3b02fc6069e365a8181e104d0.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__481a75f3b02fc6069e365a8181e104d0](histplot_vldo_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__481a75f3b02fc6069e365a8181e104d0.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Load Current<br>

| ![xyplot_i(i-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__d136f91180b00a3b70cbdba575b1ae03](xyplot_i(i-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__d136f91180b00a3b70cbdba575b1ae03.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Load Current (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5f00a1fcec72f5cdbf91a05536ac9143](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5f00a1fcec72f5cdbf91a05536ac9143.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5f00a1fcec72f5cdbf91a05536ac9143](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5f00a1fcec72f5cdbf91a05536ac9143.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5f00a1fcec72f5cdbf91a05536ac9143](histplot_vldo_100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5f00a1fcec72f5cdbf91a05536ac9143.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5f00a1fcec72f5cdbf91a05536ac9143](histplot_vldo_tc100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5f00a1fcec72f5cdbf91a05536ac9143.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__520cd1a858bc5d1a4c1e1d95f8ef7de5](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__520cd1a858bc5d1a4c1e1d95f8ef7de5.png "") |
| :-- |
|  |
<br>

## PSRR+ Performance<br>

| ![xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__277b066cc3d6ff8a4a7d32220f2eff36](xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__277b066cc3d6ff8a4a7d32220f2eff36.png "") |
| :-- |
|  |
<br>

## PSRR+ Performance (Monte Carlo)<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__392f500d8788f9d4e8760ff426f44a9c](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__392f500d8788f9d4e8760ff426f44a9c.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__392f500d8788f9d4e8760ff426f44a9c](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__392f500d8788f9d4e8760ff426f44a9c.png "") |
| :-- |
|  |
<br>

## Line Transient Performance<br>

| ![xyplot_timev(vout)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c6f1621216fbf421e184df6be2d356ef](xyplot_timev(vout)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c6f1621216fbf421e184df6be2d356ef.png "1V Line Transient") |
| :-- |
| 1V Line Transient |
<br>

## Line Transient Performance (Monte Carlo)<br>

| ![histplot_line_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__522930be35cfd93d67b8c468646c5f01](histplot_line_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__522930be35cfd93d67b8c468646c5f01.png "") |
| :-- |
|  |
<br>

## Load Transient Performance<br>

| ![xyplot_timev(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__03f831caf24373c04bd4aea9b49bca52](xyplot_timev(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__03f831caf24373c04bd4aea9b49bca52.png "200uA Load Transient") |
| :-- |
| 200uA Load Transient |
<br>

## Load Transient Performance (Monte Carlo)<br>

| ![histplot_load_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__d0cf471d977850a0faff327311efb42c](histplot_load_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__d0cf471d977850a0faff327311efb42c.png "") |
| :-- |
|  |
<br>

## AC Loopgain PM (Monte Carlo)<br>

| ![histplot_loop_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5c6f459cdabbaff086d0ac42698ea4d0](histplot_loop_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5c6f459cdabbaff086d0ac42698ea4d0.png "") |
| :-- |
|  |
<br>
