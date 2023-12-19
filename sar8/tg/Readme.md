19.12.2023, 20:08:05

# ADC Transmission Gate / Sample Switch

Sample switch / transmission gate for 8-bit ADC.

![tg](resources/tg.png "tg")

<br>

[🔗 Schematics](tg_sch.pdf)<br>

# SPECIFICATIONS

## Tranisent Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Charge Injection Switch Close | -0.005 / -0.0023 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.851200000000006,10.0,91.29505440000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.851200000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.29505440000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0011 / 0.005 | V | 315/100.0%/0.0%/0.0% | Voltage injected to 10pF capacitor at switch close |

<br>


# PERFORMANCE CHARACTERISTICS

## Transient Performance<br>

| ![xyplot_v_swv_cigroup_('tt',_-2),_('ff',_-2),_('ss',_-2),_('ll',_-2),_('hh',_-2)__6d938d2a28ef851612412a8146e392bf](xyplot_v_swv_cigroup_('tt',_-2),_('ff',_-2),_('ss',_-2),_('ll',_-2),_('hh',_-2)__6d938d2a28ef851612412a8146e392bf.png "Voltage injected to 10pF capacitor at switch close.") |
| :-- |
| Voltage injected to 10pF capacitor at switch close. |
<br>
