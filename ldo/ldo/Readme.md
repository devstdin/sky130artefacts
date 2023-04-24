24.04.2023, 19:16:01

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
| Mean LDO Voltage | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.12535999999999,10.0,61.926960000000086,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.12535999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.926960000000086" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 999/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.489 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.8573771519999998,10.0,8.327903232,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.8573771519999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.327903232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.25 / 250.0 | mV | 999/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.822960000000094,10.0,60.68424,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.822960000000094" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="60.68424" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.78 / 1.9 | V | 800/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 5.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.15485072,10.0,110.509572,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.15485072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.509572" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.319 / 100.0 | uV/°C | 999/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.767 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.003120000000116,10.0,60.91320000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.003120000000116" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="60.91320000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.78 / 1.9 | V | 997/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.705 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.938784,10.0,88.0882752,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.938784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.0882752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.772 / 25.0 | mV | 997/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.766 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.43576000000011,10.0,60.33863999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.43576000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="60.33863999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.78 / 1.9 | V | 997/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.106 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.7821184,10.0,90.59079,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.7821184" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.59079" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.331 / 20.0 | mV/V | 997/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.79104000000009,10.0,66.17280000000011,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.79104000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.17280000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 970/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.141 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.57384768,10.0,12.677964800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.57384768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.677964800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.333 / 25.0 | mV | 970/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.98544000000008,10.0,66.38880000000009,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.98544000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.38880000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 970/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.598 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.096992,10.0,53.054256,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.096992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.054256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.048 / 10 | V/A | 970/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -43.876 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.32141538461539,10.0,88.86653538461539,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.32141538461539" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.86653538461539" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.482 / 10 | dB | 990/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 1.47 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="122.76377079999999,10.0,126.03743279999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="122.76377079999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.03743279999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.531 / 20 | dB | 990/100.0%/0.0%/0.0% |  |

<br>


## Line Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.845 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.0326784,10.0,75.6149664,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.0326784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.6149664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.214 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Line Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 19.828 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.1047264,10.0,79.69008,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.1047264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.69008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.628 / 50.0 | mV | 976/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Load Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.938 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.581146239999999,10.0,11.9730848,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.581146239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.9730848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.421 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## Load Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.294 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.72645792,10.0,10.63614432,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.72645792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.63614432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.651 / 50.0 | mV | 995/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## AC Loopgain PM Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.689 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.935146666666666,10.0,19.930133333333334,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.935146666666666" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.930133333333334" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 60.872 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Loopgain PM Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.061 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.265493333333332,10.0,20.652053333333335,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.265493333333332" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.652053333333335" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.549 / 180 | deg | 1000/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,10.160214269412009,17,10.160214269412009,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.5801071347060045,10.0,6.5801071347060045,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.580004206625885,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="5.580004206625885" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.722 / 1.9 | V | 15/93.3333%/6.6667%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 4.834 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.784289536,10.0,65.77104,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.784289536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.77104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 108.978 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,10.183676890186273,17,10.183676890186273,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.591838445093137,10.0,6.591838445093137,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.557819993519727,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="5.557819993519727" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.709 / 1.9 | V | 15/93.3333%/6.6667%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 24.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,35.65023671988466,17,35.65023671988466,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.32511835994233,10.0,19.32511835994233,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.368014331640016,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="23.368014331640016" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 782.076 / 100.0 | uV/°C | 15/93.3333%/6.6667%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean LDO Voltage":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage at 20°C":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>
</details><br>


## LDO Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.33488000000003,10.0,62.13648000000012,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.33488000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.13648000000012" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 997/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.743 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.003972608,10.0,8.4098352,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.003972608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.4098352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.392 / 250.0 | mV | 997/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.96696000000008,10.0,61.20408000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.96696000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.20408000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 1.9 | V | 799/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 7.151 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.1489612,10.0,111.28036800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.1489612" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.28036800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 50.389 / 100.0 | uV/°C | 997/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.59448000000011,10.0,59.97648000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.59448000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.97648000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.779 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 12.375 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.280864,10.0,108.9487488,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.280864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.9487488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.394 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.1048800000001,10.0,59.06064000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.1048800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.06064000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.778 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 3.8 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.6783548,10.0,93.089082,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.6783548" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.089082" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.025 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.11096000000006,10.0,62.11560000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.11096000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.11560000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 997/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.679 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.791616,10.0,88.2244992,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.791616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.2244992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.796 / 25.0 | mV | 997/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.763 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.50904000000002,10.0,61.49568000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.50904000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.49568000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 1.9 | V | 997/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.099 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.7573468,10.0,90.63664680000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.7573468" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.63664680000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.344 / 20.0 | mV/V | 997/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Load [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.758240000000015,10.0,66.37584000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.758240000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.37584000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.821 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.731390144,10.0,18.32385216,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.731390144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.32385216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.66 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.778 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.897920000000035,10.0,66.80207999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.897920000000035" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.80207999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -7.276 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.611072000000004,10.0,59.289816,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.611072000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.289816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.182 / 10 | V/A | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Load (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.788880000000105,10.0,66.21743999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.788880000000105" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.21743999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 981/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.134 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.529979520000001,10.0,12.81180416,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.529979520000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.81180416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.356 / 25.0 | mV | 981/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.992639999999966,10.0,66.41976000000011,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.992639999999966" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.41976000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 981/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.684 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.475775999999996,10.0,53.198328000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.475775999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.198328000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.028 / 10 | V/A | 993/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 1.789 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.57621904,10.0,7.76550416,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.57621904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.76550416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.92 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2638838304,10.0,5.2810721888,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2638838304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.2810721888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.098 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -43.792 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="133.34844,10.0,137.6544,10.0" style="stroke:green;stroke-width:2" /><circle cx="133.34844" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.6544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.596 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 2.679 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.86048159999999,10.0,66.56264639999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.86048159999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.56264639999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.242 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -43.904 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.29150769230769,10.0,88.84571076923078,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.29150769230769" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.84571076923078" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.5 / 10 | dB | 981/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 2.558 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.06920639999998,10.0,127.03222919999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.06920639999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.03222919999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.36 / 20 | dB | 981/100.0%/0.0%/0.0% |  |

<br>


## Line Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 0.025 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0724472352,10.0,78.282048,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.0724472352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.282048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.14 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Line Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.909 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.216940799999996,10.0,81.4700928,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.216940799999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.4700928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 27.247 / 50.0 | mV | 959/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Load Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 2.072 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.967071999999998,10.0,12.372152,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.967071999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.372152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.56 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## Load Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.963 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.65351488,10.0,10.76367936,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.65351488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.76367936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.696 / 50.0 | mV | 988/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## AC Loopgain PM Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 46.982 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.114346666666665,10.0,17.753280000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.114346666666665" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.753280000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 58.831 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Loopgain PM Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 46.706 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.820160000000002,10.0,18.057066666666664,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.820160000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.057066666666664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 59.116 / 180 | deg | 1000/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## LDO Output Voltage vs Temperature<br>

| ![xyplot_temp-sweepv(vldo)v(vdd)_('tt',_-2)__744781268f63d499334ec11aa5b1bf9b](xyplot_temp-sweepv(vldo)v(vdd)_('tt',_-2)__744781268f63d499334ec11aa5b1bf9b.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Temperature (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ab6e706d3d9714665afc281d10c1522b](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ab6e706d3d9714665afc281d10c1522b.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ab6e706d3d9714665afc281d10c1522b](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ab6e706d3d9714665afc281d10c1522b.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ab6e706d3d9714665afc281d10c1522b](histplot_vldo_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ab6e706d3d9714665afc281d10c1522b.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ab6e706d3d9714665afc281d10c1522b](histplot_vldo_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ab6e706d3d9714665afc281d10c1522b.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs VDD<br>

| ![xyplot_v(v-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4a17ff07c51788f19fb3341308999003](xyplot_v(v-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4a17ff07c51788f19fb3341308999003.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs VDD (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__65f63a6d6e76101b43cae203d8132470](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__65f63a6d6e76101b43cae203d8132470.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__65f63a6d6e76101b43cae203d8132470](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__65f63a6d6e76101b43cae203d8132470.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__65f63a6d6e76101b43cae203d8132470](histplot_vldo_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__65f63a6d6e76101b43cae203d8132470.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__65f63a6d6e76101b43cae203d8132470](histplot_vldo_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__65f63a6d6e76101b43cae203d8132470.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Load Current<br>

| ![xyplot_i(i-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__d136f91180b00a3b70cbdba575b1ae03](xyplot_i(i-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__d136f91180b00a3b70cbdba575b1ae03.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Load Current (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__dfa29e09eb1f44b7f16935add67d5640](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__dfa29e09eb1f44b7f16935add67d5640.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__dfa29e09eb1f44b7f16935add67d5640](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__dfa29e09eb1f44b7f16935add67d5640.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__dfa29e09eb1f44b7f16935add67d5640](histplot_vldo_100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__dfa29e09eb1f44b7f16935add67d5640.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__dfa29e09eb1f44b7f16935add67d5640](histplot_vldo_tc100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__dfa29e09eb1f44b7f16935add67d5640.png "") |
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

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bda7dd5f5590d31fd94eeacc9fdb106a](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bda7dd5f5590d31fd94eeacc9fdb106a.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bda7dd5f5590d31fd94eeacc9fdb106a](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bda7dd5f5590d31fd94eeacc9fdb106a.png "") |
| :-- |
|  |
<br>

## Line Transient Performance<br>

| ![xyplot_timev(vout)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c6f1621216fbf421e184df6be2d356ef](xyplot_timev(vout)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c6f1621216fbf421e184df6be2d356ef.png "1V Line Transient") |
| :-- |
| 1V Line Transient |
<br>

## Line Transient Performance (Monte Carlo)<br>

| ![histplot_line_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__64e66fef8878ea36fd3a86403c75fdfd](histplot_line_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__64e66fef8878ea36fd3a86403c75fdfd.png "") |
| :-- |
|  |
<br>

## Load Transient Performance<br>

| ![xyplot_timev(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__03f831caf24373c04bd4aea9b49bca52](xyplot_timev(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__03f831caf24373c04bd4aea9b49bca52.png "200uA Load Transient") |
| :-- |
| 200uA Load Transient |
<br>

## Load Transient Performance (Monte Carlo)<br>

| ![histplot_load_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__15468dd1e7715d24da0b9e8aaceece39](histplot_load_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__15468dd1e7715d24da0b9e8aaceece39.png "") |
| :-- |
|  |
<br>

## AC Loopgain PM (Monte Carlo)<br>

| ![histplot_loop_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__58c110015b2b97d675ebb6c6cf99826b](histplot_loop_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__58c110015b2b97d675ebb6c6cf99826b.png "") |
| :-- |
|  |
<br>
