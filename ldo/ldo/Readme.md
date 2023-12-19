19.12.2023, 20:08:05

# 1.8 V LDO

1.8 V linear regulator.

![ldo](resources/ldo.png "ldo")

<br>

[🔗 Schematics](ldo_sch.pdf)<br>

# LVS

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
| Mean LDO Voltage | 1.7 / 1.76 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.89544,10.0,66.53064000000009,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.89544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.53064000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.235 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.7113888,10.0,8.288852160000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.7113888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.288852160000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.182 / 250.0 | mV | 1000/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.759 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.43392000000008,10.0,65.36496000000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.43392000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.36496000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.787 / 1.9 | V | 800/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 4.722 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.39978168,10.0,110.3107368,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.39978168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.3107368" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.043 / 100.0 | uV/°C | 1000/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.76 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.84648000000003,10.0,66.61056000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.84648000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.61056000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 999/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.681 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.803136,10.0,88.216608,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.803136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.216608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.795 / 25.0 | mV | 999/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.759 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.280560000000065,10.0,65.98344000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.280560000000065" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.98344000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.787 / 1.9 | V | 999/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.101 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.762538,10.0,90.6198924,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.762538" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.6198924" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.339 / 20.0 | mV/V | 999/100.0%/0.0%/0.0% |  |

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
| Mean LDO Voltage | 1.7 / 1.767 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.952000000000005,10.0,69.65184000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.952000000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.65184000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.793 / 1.9 | V | 973/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.137 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.55189056,10.0,12.73158464,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.55189056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.73158464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.342 / 25.0 | mV | 973/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.767 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.155040000000085,10.0,69.84840000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.155040000000085" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.84840000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.793 / 1.9 | V | 973/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.621 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.927576,10.0,53.121216000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.927576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.121216000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.039 / 10 | V/A | 973/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -43.896 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.30025846153846,10.0,88.90829538461539,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.30025846153846" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.90829538461539" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.444 / 10 | dB | 992/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 1.465 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="122.75841399999999,10.0,126.06411,10.0" style="stroke:green;stroke-width:2" /><circle cx="122.75841399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.06411" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.553 / 20 | dB | 992/100.0%/0.0%/0.0% |  |

<br>


## Line Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.845 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.0326784,10.0,75.6149664,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.0326784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.6149664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.214 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Line Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 19.963 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.4943616,10.0,79.7414016,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.4943616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.7414016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.646 / 50.0 | mV | 989/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Load Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.938 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.581146239999999,10.0,11.97325184,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.581146239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.97325184" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.421 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## Load Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.292 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.72158784,10.0,10.44717888,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.72158784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.44717888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.586 / 50.0 | mV | 999/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## AC Loopgain PM Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.689 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.935146666666666,10.0,19.930133333333334,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.935146666666666" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.930133333333334" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 60.872 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Loopgain PM Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.368 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.592213333333333,10.0,20.25664,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.592213333333333" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.25664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.178 / 180 | deg | 1000/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.609 | <svg height="20" width="150"><polyline points="6.185180178712699,3,6.185180178712699,17,13.187038102263106,17,13.187038102263106,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.686109140487902,10.0,9.686109140487902,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.722 / 1.9 | V | 15/86.6667%/13.3333%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 4.834 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,22.47506056202861,17,22.47506056202861,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.737530281014305,10.0,12.737530281014305,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.376557073287899,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.376557073287899" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1848.518 / 250.0 | mV | 15/93.3333%/6.6667%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,10.183698392422993,17,10.183698392422993,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.591849196211497,10.0,6.591849196211497,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.557827649606134,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="5.557827649606134" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.709 / 1.9 | V | 15/93.3333%/6.6667%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 24.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,35.651780326984905,17,35.651780326984905,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.325890163492453,10.0,19.325890163492453,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.36897727141316,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="23.36897727141316" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 782.035 / 100.0 | uV/°C | 15/93.3333%/6.6667%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean LDO Voltage":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>
> **FAIL:** group:ll file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/ll/ldo_tran_temp.csv Index:2 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage Curvature":<br>
> **FAIL:** group:ll file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/ll/ldo_tran_temp.csv Index:2 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage at 20°C":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:hh file:work/sim/ldo/ldo_tb.1_ldo_ext/batch_0/hh/ldo_tran_temp.csv Index:1 <br>
</details><br>


## LDO Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.756 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.992399999999975,10.0,64.01280000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.992399999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="64.01280000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.785 / 1.9 | V | 994/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.631 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.363413952,10.0,8.37253344,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.363413952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.37253344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.327 / 250.0 | mV | 994/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.755 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.53232000000009,10.0,62.845679999999966,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.53232000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.845679999999966" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.783 / 1.9 | V | 796/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 1.015 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.73054584,10.0,110.94876479999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.73054584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.94876479999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.929 / 100.0 | uV/°C | 994/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.59448000000011,10.0,59.97648000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.59448000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.97648000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.779 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 12.375 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.280864,10.0,108.9486912,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.280864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.9486912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.394 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.1048800000001,10.0,59.06064000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.1048800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.06064000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.778 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 3.8 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.6783548,10.0,93.089046,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.6783548" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.089046" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.025 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.755 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.43871999999996,10.0,66.38016,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.43871999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.38016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 995/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.689 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.8471424,10.0,88.2788736,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.8471424" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.2788736" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.805 / 25.0 | mV | 995/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.754 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.8792800000001,10.0,65.71848000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.8792800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.71848000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.787 / 1.9 | V | 995/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.101 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.7625704,10.0,90.6207744,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.7625704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.6207744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.339 / 20.0 | mV/V | 995/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Load [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.758240000000015,10.0,66.37584000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.758240000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.37584000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.821 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.731390144,10.0,18.32383488,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.731390144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.32383488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.66 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.778 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.897920000000035,10.0,66.80207999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.897920000000035" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.80207999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -7.277 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.604160000000004,10.0,59.289816,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.604160000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.289816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.182 / 10 | V/A | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Load (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="52.25231999999998,10.0,69.75480000000009,10.0" style="stroke:green;stroke-width:2" /><circle cx="52.25231999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.75480000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.793 / 1.9 | V | 981/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.135 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.538988159999999,10.0,12.71668352,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.538988159999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.71668352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.34 / 25.0 | mV | 981/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.769 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="52.4647200000001,10.0,69.96215999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="52.4647200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.96215999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.793 / 1.9 | V | 983/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.685 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.467496000000004,10.0,53.162544,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.467496000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.162544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.033 / 10 | V/A | 991/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 1.789 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.57621904,10.0,7.765502720000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.57621904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.765502720000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.92 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2638836864,10.0,5.2810720448,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2638836864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.2810720448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.098 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -43.792 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="133.34844,10.0,137.6544,10.0" style="stroke:green;stroke-width:2" /><circle cx="133.34844" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.6544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.596 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 2.595 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.4556448,10.0,66.27693119999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.4556448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.27693119999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.183 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -43.909 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.28552615384615,10.0,88.8870276923077,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.28552615384615" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.8870276923077" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.463 / 10 | dB | 987/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 2.414 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="123.897004,10.0,126.96674519999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="123.897004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.96674519999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.306 / 20 | dB | 987/100.0%/0.0%/0.0% |  |

<br>


## Line Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 0.025 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.072260928,10.0,78.17946239999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.072260928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.17946239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.104 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Line Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.853 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.056121600000004,10.0,81.6886272,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.056121600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.6886272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 27.322 / 50.0 | mV | 965/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Load Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 2.087 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.01129728,10.0,12.39047744,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.01129728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.39047744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.566 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## Load Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.992 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.736320639999999,10.0,10.76069568,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.736320639999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.76069568" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.695 / 50.0 | mV | 987/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## AC Loopgain PM Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.304 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.523840000000003,10.0,18.743253333333335,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.523840000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.743253333333335" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 59.759 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Loopgain PM Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 28.0 | <svg height="20" width="150"><polyline points="19.105263157894736,3,19.105263157894736,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.05263157894737,10.0,83.05263157894737,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,33.68071578947368,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="33.68071578947368" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 60.385 / 180 | deg | 972/98.251%/1.749%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Loopgain PM":<br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:3 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:4 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:6 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:7 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:8 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:9 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:10 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:11 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:12 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:13 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:14 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:15 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_3/ff_mm/ldo_ac_loop.csv Index:16 <br>
</details><br>


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
