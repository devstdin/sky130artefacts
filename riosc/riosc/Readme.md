20.08.2024, 21:11:07

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
| High Duration | 10.0 / 33.927 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.28320000000001,10.0,70.1408,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.28320000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.1408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.963 / 100.0 | ns | 500/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 72.511 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.008784,10.0,72.65512000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.008784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.65512000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 107.069 / 200.0 | ns | 500/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 46.229 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.85175200000001,10.0,81.85425599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.85175200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.85425599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 50.952 / 60 | % | 500/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>


## Tranisent Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 46.695 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.711999999999996,10.0,90.192,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.711999999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 64.495 / 100.0 | ns | 45/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 96.076 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.860775999999994,10.0,95.77224,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.860775999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.77224" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 135.965 / 200.0 | ns | 45/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 45.678 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.88361600000001,10.0,78.70202400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.88361600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.70202400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 50.514 / 60 | % | 45/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>


## Transient Specification (Monte Carlo, PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| High Duration | 10.0 / 43.339 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.342400000000005,10.0,81.4288,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.342400000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.4288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 59.018 / 100.0 | ns | 500/100.0%/0.0%/0.0% | Last period before oscillator disable |
| Period Duration | 20.0 / 88.919 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.13498400000001,10.0,83.8624,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.13498400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.8624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 121.078 / 200.0 | ns | 500/100.0%/0.0%/0.0% | First period after oscillator enable |
| Duty-Cycle | 40 / 44.035 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="32.05300799999999,10.0,88.67877600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="32.05300799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.67877600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.9 / 60 | % | 500/100.0%/0.0%/0.0% | First period after oscillator enable |

<br>


# PERFORMANCE CHARACTERISTICS

## Transient Performance<br>

| ![xyplot_timev(osc)group_('tt',_-2)__8b374d1792399df7627c2edbbac266ec](xyplot_timev(osc)group_('tt',_-2)__8b374d1792399df7627c2edbbac266ec.png "") |
| :-- |
|  |
<br>

## Transient Performance (Monte Carlo)<br>

| ![histplot_first_periodgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf2bc3329332c7b0e8d8077c1eb5d0bf](histplot_first_periodgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf2bc3329332c7b0e8d8077c1eb5d0bf.png "") |
| :-- |
|  |
<br>

| ![histplot_first_dutycyclegroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf2bc3329332c7b0e8d8077c1eb5d0bf](histplot_first_dutycyclegroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf2bc3329332c7b0e8d8077c1eb5d0bf.png "") |
| :-- |
|  |
<br>

| ![histplot_last_highgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf2bc3329332c7b0e8d8077c1eb5d0bf](histplot_last_highgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf2bc3329332c7b0e8d8077c1eb5d0bf.png "") |
| :-- |
|  |
<br>
