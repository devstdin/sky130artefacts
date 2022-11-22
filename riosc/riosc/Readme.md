22.11.2022, 08:17:59

# Ring Oscillator

Ring oscillator with enable pin.

![riosc](resources/riosc.png "riosc")

<br>

[🔗 Schematics](riosc_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](riosc_riosc_netgen_comp.out)<br>

# SPECIFICATIONS

## Tranisent Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 35.648 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.03680000000001,10.0,67.6832,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.03680000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.6832" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 50.427 / 100.0 | ns | 45/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 73.855 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.084095999999995,10.0,72.23487999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.084095999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.23487999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 106.544 / 200.0 | ns | 45/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 45.229 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.64707200000001,10.0,74.639784,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.64707200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.639784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.95 / 60 | % | 45/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>


## Transient Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 35.524 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.8384,10.0,59.793600000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.8384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.793600000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 45.496 / 100.0 | ns | 500/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 74.468 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.57432,10.0,61.828632000000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.57432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.828632000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 93.536 / 200.0 | ns | 500/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 46.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.696808,10.0,74.00942400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.696808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.00942400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.862 / 60 | % | 500/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>


## Tranisent Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 48.108 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.9728,10.0,93.3664,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.9728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.3664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 66.479 / 100.0 | ns | 45/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 99.14 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.312256,10.0,99.16136,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.312256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.16136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 140.202 / 200.0 | ns | 45/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 45.391 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.812248000000025,10.0,77.80296,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.812248000000025" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.80296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 50.389 / 60 | % | 45/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>


## Transient Specification (Monte Carlo, PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 48.332 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.3312,10.0,83.8608,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.3312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.8608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 60.538 / 100.0 | ns | 500/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 100.347 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.27752000000001,10.0,87.49008,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.27752000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.49008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 125.613 / 200.0 | ns | 500/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 46.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.610927999999994,10.0,76.31961600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.610927999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.31961600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 50.183 / 60 | % | 500/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>


# PERFORMANCE CHARACTERISTICS

## Transient Performance<br>

| ![xyplot_timev(osc)group_('tt',_-2)__8b374d1792399df7627c2edbbac266ec](xyplot_timev(osc)group_('tt',_-2)__8b374d1792399df7627c2edbbac266ec.png "") |
| :-- |
|  |
<br>

## Transient Performance (Monte Carlo)<br>

| ![histplot_first_periodgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6b9428f7b38ec188bb1fe80983653d60](histplot_first_periodgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6b9428f7b38ec188bb1fe80983653d60.png "") |
| :-- |
|  |
<br>

| ![histplot_first_dutycyclegroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6b9428f7b38ec188bb1fe80983653d60](histplot_first_dutycyclegroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6b9428f7b38ec188bb1fe80983653d60.png "") |
| :-- |
|  |
<br>

| ![histplot_last_highgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6b9428f7b38ec188bb1fe80983653d60](histplot_last_highgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6b9428f7b38ec188bb1fe80983653d60.png "") |
| :-- |
|  |
<br>
