09.03.2022, 20:08:12

# 1.8 V LDO

1.8 V linear regulator.

![ldo](resources/ldo.png "ldo")

<br>

[🔗 Schematics](ldo_sch.pdf)<br>

# SPECIFICATIONS

## LDO Voltage Curvature vs Temperature<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.88967999999996,10.0,63.38136000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.88967999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.38136000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 4.837 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.785977216,10.0,8.604166656,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.785977216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.604166656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.729 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.27480000000003,10.0,62.155920000000116,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.27480000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.155920000000116" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 24.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.82978480000001,10.0,110.9438832,10.0" style="stroke:green;stroke-width:2" /><circle cx="92.82978480000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.9438832" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.922 / 100.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs Temperature (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.60704000000002,10.0,61.5964800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.60704000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.5964800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.781 / 1.9 | V | 2498/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.653 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.376262496,10.0,8.553431424,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.376262496" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.553431424" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.641 / 250.0 | mV | 2498/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.764 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.977040000000045,10.0,60.62231999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.977040000000045" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="60.62231999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.78 / 1.9 | V | 2000/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 0.946 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.68078088,10.0,112.2635136,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.68078088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="112.2635136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.755 / 100.0 | uV/°C | 2498/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs VDD<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.59736000000003,10.0,59.97216000000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.59736000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.97216000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.779 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 12.387 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.3511936,10.0,108.92519039999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.3511936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.92519039999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.39 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.10776000000002,10.0,59.05632000000011,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.10776000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.05632000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.778 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 3.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.692564,10.0,93.0824652,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.692564" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.0824652" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.023 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs VDD (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.766 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.45808000000003,10.0,63.585120000000046,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.45808000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.585120000000046" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 1.9 | V | 2499/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.66 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.6834432,10.0,88.20399359999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.6834432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.20399359999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.792 / 25.0 | mV | 2499/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.765 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.85904000000007,10.0,62.96736000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.85904000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.96736000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.783 / 1.9 | V | 2499/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.7374028,10.0,90.6198924,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.7374028" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.6198924" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.339 / 20.0 | mV/V | 2499/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs Load<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.766160000000006,10.0,66.37008000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.766160000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.37008000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.822 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.7352672,10.0,18.32400192,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.7352672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.32400192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.66 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.778 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.905840000000026,10.0,66.79631999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.905840000000026" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.79631999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -7.276 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.615104,10.0,59.260296000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.615104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.260296000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.186 / 10 | V/A | 15/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Curvature vs Load (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.90264000000002,10.0,69.15288000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.90264000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.15288000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.792 / 1.9 | V | 2439/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.126 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.483738240000001,10.0,12.69148352,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.483738240000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.69148352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.335 / 25.0 | mV | 2439/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.10640000000004,10.0,69.36024000000009,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.10640000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.36024000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.792 / 1.9 | V | 2439/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.603 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.055232000000004,10.0,53.36184,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.055232000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.36184" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.005 / 10 | V/A | 2439/100.0%/0.0%/0.0% |  |

<br>

## LDO Voltage Noise Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 1.789 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.57644224,10.0,7.76334704,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.57644224" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.76334704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.919 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2639068992,10.0,5.2809036512,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2639068992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.2809036512" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.098 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -43.785 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="133.37544000000003,10.0,137.65404,10.0" style="stroke:green;stroke-width:2" /><circle cx="133.37544000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.65404" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.596 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 1.732 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.3129808,10.0,62.526460799999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.3129808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.526460799999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.401 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -43.91 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.28486153846153,10.0,88.90707692307693,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.28486153846153" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.90707692307693" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.445 / 10 | dB | 2480/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 1.559 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="122.87052279999999,10.0,126.04860359999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="122.87052279999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.04860359999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.541 / 20 | dB | 2480/100.0%/0.0%/0.0% |  |

<br>

## Line Transient Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.781 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.848704,10.0,74.5833216,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.848704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.5833216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 24.855 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Line Transient Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 19.859 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.1935168,10.0,78.43324799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.1935168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.43324799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.192 / 50.0 | mV | 2458/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>

## Load Transient Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.931 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.56068096,10.0,11.86629728,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.56068096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.86629728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.384 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## Load Transient Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.324 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.81267936,10.0,10.31507328,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.81267936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.31507328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.54 / 50.0 | mV | 2492/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>

## AC Loopgain PM Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.492 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.7246933333333345,10.0,19.02549333333333,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.7246933333333345" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.02549333333333" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 60.024 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>

## AC Loopgain PM Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 47.43 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.591786666666667,10.0,19.760746666666666,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.591786666666667" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.760746666666666" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 60.713 / 180 | deg | 2500/100.0%/0.0%/0.0% |  |

<br>

# PERFORMANCE CHARACTERISTICS

## LDO Output Voltage vs Temperature<br>

| ![xyplot_temp-sweepv(vldo)v(vdd)_('tt',_-2)__744781268f63d499334ec11aa5b1bf9b](xyplot_temp-sweepv(vldo)v(vdd)_('tt',_-2)__744781268f63d499334ec11aa5b1bf9b.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Temperature (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ae53fa2d3f56aeeee5ce4452f595422e](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ae53fa2d3f56aeeee5ce4452f595422e.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ae53fa2d3f56aeeee5ce4452f595422e](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ae53fa2d3f56aeeee5ce4452f595422e.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ae53fa2d3f56aeeee5ce4452f595422e](histplot_vldo_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ae53fa2d3f56aeeee5ce4452f595422e.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ae53fa2d3f56aeeee5ce4452f595422e](histplot_vldo_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ae53fa2d3f56aeeee5ce4452f595422e.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs VDD<br>

| ![xyplot_v(v-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4a17ff07c51788f19fb3341308999003](xyplot_v(v-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4a17ff07c51788f19fb3341308999003.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs VDD (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__39a7f9a99a76d9dbd988333b6201ee79](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__39a7f9a99a76d9dbd988333b6201ee79.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__39a7f9a99a76d9dbd988333b6201ee79](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__39a7f9a99a76d9dbd988333b6201ee79.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__39a7f9a99a76d9dbd988333b6201ee79](histplot_vldo_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__39a7f9a99a76d9dbd988333b6201ee79.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__39a7f9a99a76d9dbd988333b6201ee79](histplot_vldo_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__39a7f9a99a76d9dbd988333b6201ee79.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Load Current<br>

| ![xyplot_i(i-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__d136f91180b00a3b70cbdba575b1ae03](xyplot_i(i-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__d136f91180b00a3b70cbdba575b1ae03.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Load Current (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c05801f555119425d7dd4135b53e043d](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c05801f555119425d7dd4135b53e043d.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c05801f555119425d7dd4135b53e043d](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c05801f555119425d7dd4135b53e043d.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c05801f555119425d7dd4135b53e043d](histplot_vldo_100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c05801f555119425d7dd4135b53e043d.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c05801f555119425d7dd4135b53e043d](histplot_vldo_tc100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c05801f555119425d7dd4135b53e043d.png "") |
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

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b0743347b5143280687942db8ca617cf](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b0743347b5143280687942db8ca617cf.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b0743347b5143280687942db8ca617cf](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b0743347b5143280687942db8ca617cf.png "") |
| :-- |
|  |
<br>

## Line Transient Performance<br>

| ![xyplot_timev(vout)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c6f1621216fbf421e184df6be2d356ef](xyplot_timev(vout)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c6f1621216fbf421e184df6be2d356ef.png "1V Line Transient") |
| :-- |
| 1V Line Transient |
<br>

## Line Transient Performance (Monte Carlo)<br>

| ![histplot_line_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__485627f2bf0e421caa5a67c531d96337](histplot_line_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__485627f2bf0e421caa5a67c531d96337.png "") |
| :-- |
|  |
<br>

## Load Transient Performance<br>

| ![xyplot_timev(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__03f831caf24373c04bd4aea9b49bca52](xyplot_timev(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__03f831caf24373c04bd4aea9b49bca52.png "200uA Load Transient") |
| :-- |
| 200uA Load Transient |
<br>

## Load Transient Performance (Monte Carlo)<br>

| ![histplot_load_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__d16a8b3a8f921dca57d0790e6dce5749](histplot_load_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__d16a8b3a8f921dca57d0790e6dce5749.png "") |
| :-- |
|  |
<br>

## AC Loopgain PM (Monte Carlo)<br>

| ![histplot_loop_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3e5f693a84fb06986f0aa112e1ad27a1](histplot_loop_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3e5f693a84fb06986f0aa112e1ad27a1.png "") |
| :-- |
|  |
<br>
