26.04.2022, 16:30:28

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
| High Duration | 10.0 / 35.65 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.04,10.0,67.68159999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.04" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.68159999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 50.426 / 100.0 | ns | 45/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 73.855 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.084095999999995,10.0,72.23487999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.084095999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.23487999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 106.544 / 200.0 | ns | 45/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 45.229 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.64707200000001,10.0,74.639784,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.64707200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.639784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.95 / 60 | % | 45/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>

## Transient Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 33.927 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.28320000000001,10.0,70.1408,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.28320000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.1408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.963 / 100.0 | ns | 500/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 72.511 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.008784,10.0,72.65512000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.008784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.65512000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 107.069 / 200.0 | ns | 500/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 46.229 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.85175200000001,10.0,81.85425599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.85175200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.85425599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 50.952 / 60 | % | 500/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>

## Tranisent Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 60.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="84.2288,10.0,119.456,10.0" style="stroke:green;stroke-width:2" /><circle cx="84.2288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 82.785 / 100.0 | ns | 45/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 123.898 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="86.11880000000001,10.0,125.62376,10.0" style="stroke:green;stroke-width:2" /><circle cx="86.11880000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.62376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 173.28 / 200.0 | ns | 45/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 46.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.673911999999994,10.0,83.02800000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.673911999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.02800000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.115 / 60 | % | 45/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>

## Transient Specification (Monte Carlo, PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 57.243 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.58879999999999,10.0,117.7936,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.58879999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.7936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 81.746 / 100.0 | ns | 500/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 122.491 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="84.99271999999999,10.0,117.96968,10.0" style="stroke:green;stroke-width:2" /><circle cx="84.99271999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.96968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 163.712 / 200.0 | ns | 500/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 46.049 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.55380800000001,10.0,96.32380800000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.55380800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.32380800000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 52.962 / 60 | % | 500/100.0%/0.0%/0.0% | First period after oscillator enable |

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
