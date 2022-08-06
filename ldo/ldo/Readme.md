06.08.2022, 15:44:52

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
| Mean LDO Voltage | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.396080000000104,10.0,62.76936000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.396080000000104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.76936000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.783 / 1.9 | V | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.443 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.830923776,10.0,8.555196864,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.830923776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.555196864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.644 / 250.0 | mV | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.103760000000015,10.0,61.66488000000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.103760000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.66488000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 1.9 | V | 800/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 4.891 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.52130184,10.0,112.2539448,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.52130184" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="112.2539448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.742 / 100.0 | uV/°C | 1000/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.766 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.38896000000012,10.0,62.225759999999966,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.38896000000012" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.225759999999966" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.702 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.92208000000001,10.0,88.50650879999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.92208000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.50650879999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.845 / 25.0 | mV | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.78848000000012,10.0,61.615199999999994,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.78848000000012" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.615199999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 1.9 | V | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.104 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.7756708,10.0,90.66240839999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.7756708" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.66240839999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.351 / 20.0 | mV/V | 1000/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.86727999999998,10.0,66.94824000000011,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.86727999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.94824000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 975/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.135 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.53493312,10.0,12.63523712,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.53493312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.63523712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.326 / 25.0 | mV | 975/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.069599999999966,10.0,67.15272000000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.069599999999966" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.15272000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 975/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.58 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.221984,10.0,53.190048,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.221984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.190048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.029 / 10 | V/A | 975/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -43.943 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.24819692307693,10.0,88.8927876923077,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.24819692307693" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.8927876923077" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.458 / 10 | dB | 987/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 1.55 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="122.8594804,10.0,125.99161319999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="122.8594804" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.99161319999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.493 / 20 | dB | 987/100.0%/0.0%/0.0% |  |

<br>

## Line Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.845 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.0326784,10.0,75.6149664,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.0326784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.6149664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.214 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Line Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.732019199999996,10.0,79.450752,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.732019199999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.450752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.545 / 50.0 | mV | 984/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Load Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.938 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.581146239999999,10.0,11.9730848,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.581146239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.9730848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.421 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## Load Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.848 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.32299168,10.0,10.491024,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.32299168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.491024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.601 / 50.0 | mV | 995/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## AC Loopgain PM Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.689 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.935146666666666,10.0,19.930133333333334,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.935146666666666" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.930133333333334" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 60.872 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>

## AC Loopgain PM Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.342 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.564693333333336,10.0,20.28597333333333,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.564693333333336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.28597333333333" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.206 / 180 | deg | 1000/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.766 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.252160000000025,10.0,61.425119999999964,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.252160000000025" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.425119999999964" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 1.9 | V | 994/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.278 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.735905088,10.0,8.18266944,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.735905088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.18266944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.998 / 250.0 | mV | 994/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.795680000000004,10.0,60.28752000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.795680000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="60.28752000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.78 / 1.9 | V | 795/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 4.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.43924992,10.0,109.4865312,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.43924992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="109.4865312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 47.898 / 100.0 | uV/°C | 994/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.58328000000005,10.0,61.97232000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.58328000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.97232000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 999/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.664 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.7072896,10.0,88.2925248,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.7072896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.2925248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.808 / 25.0 | mV | 999/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.012320000000024,10.0,61.362480000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.012320000000024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.362480000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 1.9 | V | 999/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.097 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.7483252,10.0,90.6451464,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.7483252" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.6451464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.346 / 20.0 | mV/V | 999/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.611040000000024,10.0,67.75392000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.611040000000024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.75392000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.79 / 1.9 | V | 976/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.126 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.48801792,10.0,12.68917376,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.48801792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.68917376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.335 / 25.0 | mV | 974/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.81480000000005,10.0,67.9512000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.81480000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.9512000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.79 / 1.9 | V | 976/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.685 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.46692,10.0,53.14728,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.46692" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.14728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.035 / 10 | V/A | 992/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 1.789 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.57621904,10.0,7.76550416,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.57621904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.76550416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.92 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2638838304,10.0,5.2810722176,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2638838304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.2810722176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.098 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -43.792 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="133.34844,10.0,137.6544,10.0" style="stroke:green;stroke-width:2" /><circle cx="133.34844" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.6544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.596 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 2.704 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.980404799999995,10.0,66.7056048,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.980404799999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.7056048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.272 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -43.911 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.28364307692308,10.0,88.87107692307694,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.28364307692308" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.87107692307694" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.478 / 10 | dB | 990/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 2.562 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.07390199999999,10.0,127.03329839999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.07390199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.03329839999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.361 / 20 | dB | 990/100.0%/0.0%/0.0% |  |

<br>

## Line Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 21.686 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.4569472,10.0,78.01752,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.4569472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.01752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.048 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Line Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.529 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.1245856,10.0,81.4176192,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.1245856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.4176192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 27.228 / 50.0 | mV | 978/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Load Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 2.064 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.945474879999999,10.0,12.352835840000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.945474879999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.352835840000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.553 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## Load Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.965 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.65929504,10.0,10.74756576,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.65929504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.74756576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.69 / 50.0 | mV | 987/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## AC Loopgain PM Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 46.727 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.841706666666664,10.0,17.536746666666666,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.841706666666664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.536746666666666" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 58.628 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>

## AC Loopgain PM Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 46.309 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.396053333333331,10.0,17.77461333333333,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.396053333333331" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.77461333333333" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 58.851 / 180 | deg | 1000/100.0%/0.0%/0.0% |  |

<br>

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
