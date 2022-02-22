22.02.2022, 19:07:36

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![placeholder](resources/img-placeholder.png "Placeholder")

<br>

[🔗 Schematics](bmbg_sch.pdf)<br>

# SPECIFICATIONS

## Reference Voltage Curvature vs Temperature<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.78452000000003,10.0,82.39512000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.78452000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.39512000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.221 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.419 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.18155976,10.0,13.3461696,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.18155976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.3461696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.37 / 200.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.03216,10.0,66.84671999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.03216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.84671999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -20.0 / -45.96 | <svg height="20" width="150"><polyline points="28.611319273307256,3,28.611319273307256,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.80565963665363,10.0,87.80565963665363,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,73.96806506444578,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="73.96806506444578" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 25.974 / 100.0 | uV/°C | 15/73.3333%/26.6667%/0.0% |  |
| Max. Supply Current | -75.0 / -79.624 | <svg height="20" width="150"><polyline points="25.47773104421387,3,25.47773104421387,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="86.23886552210693,10.0,86.23886552210693,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,28.90028422708459,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="28.90028422708459" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -74.296 / -50.0 | uA | 15/26.6667%/73.3333%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt/dc.csv Index:0 vsup:3.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ll/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ll/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ll/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ss/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ss/dc.csv Index:2 vsup:5.0 <br>

## Reference Voltage Curvature vs Temperature (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.104 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.47275999999998,10.0,131.48508,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.47275999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="131.48508" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.357 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.759 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,133.99739506221692,17,133.99739506221692,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.49869753110846,10.0,68.49869753110846,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.496890018134952,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.496890018134952" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 219.852 / 200.0 | mV | 2499/99.92%/0.08%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.11 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.46932,10.0,130.61604000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.46932" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.61604000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.354 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1000.0 / -1070.3 | <svg height="20" width="150"><polyline points="7.540915880556037,3,7.540915880556037,17,136.72771191344484,17,136.72771191344484,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.13431389700044,10.0,72.13431389700044,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1159.03 / 1000.0 | uV/°C | 2500/99.92%/0.08%/0.0% |  |
| Max. Supply Current | -75.0 / -82.969 | <svg height="20" width="150"><polyline points="37.806846410730095,3,37.806846410730095,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.40342320536504,10.0,92.40342320536504,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,37.084861279197824,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="37.084861279197824" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -75.165 / -50.0 | uA | 2499/0.0%/100.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ss_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ss_mm/dc.csv Index:17 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ss_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ss_mm/dc.csv Index:18 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:49 vsup:5.0 <br>

## Reference Voltage Curvature vs VDD<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.201 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.4644,10.0,82.17876,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.4644" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.17876" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.22 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.393 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.8532096,10.0,144.1515504,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.8532096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="144.1515504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.802 / 10.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.198 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.929823999999996,10.0,65.79091199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.929823999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.79091199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.218 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.798 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.0741896,10.0,105.05442000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.0741896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.05442000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.348 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -75.0 / -91.322 | <svg height="20" width="150"><polyline points="59.879970379189956,3,59.879970379189956,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="103.43998518959498,10.0,103.43998518959498,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,62.333618893430426,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="62.333618893430426" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -74.296 / -50.0 | uA | 15/26.6667%/73.3333%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/ff/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/ff/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/hh/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/hh/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/tt/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/tt/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/ll/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/ll/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/ll/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/ss/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/ss/dc.csv Index:2 te:140.0 <br>

## Reference Voltage Curvature vs VDD (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.870240000000024,10.0,132.6414,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.870240000000024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="132.6414" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.36 / 1.4 | V | 2499/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,139.2682743799557,17,139.2682743799557,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.13413718997785,10.0,71.13413718997785,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.472582274336427,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="8.472582274336427" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 21.135 / 20.0 | mV | 2499/99.96%/0.04%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.78384000000002,10.0,131.30076,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.78384000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="131.30076" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.356 / 1.4 | V | 2499/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -4.047 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.43188,10.0,122.612736,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.43188" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.612736" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.226 / 20.0 | mV/V | 2499/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -75.0 / -83.213 | <svg height="20" width="150"><polyline points="38.608707433836194,3,38.608707433836194,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.80435371691809,10.0,92.80435371691809,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,33.856399602565254,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="33.856399602565254" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -76.096 / -50.0 | uA | 2499/0.0%/100.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_6/ss_mm/dc.csv Index:42 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_8/ll_mm/dc.csv Index:49 te:20.0 <br>

## Reference Voltage Noise Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 12.889 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.5604768,10.0,28.875057599999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.5604768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="28.875057599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.969 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.608 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.750366944,10.0,7.126168064,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.750366944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.126168064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.738 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -65.174 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.374320000000004,10.0,65.98416,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.374320000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.98416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.504 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.781 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.55031199999999,10.0,90.7532976,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.55031199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.7532976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.282 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -111.552 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.357784615384608,10.0,135.81469476923078,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.357784615384608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.81469476923078" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.098 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.928 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.4560416,10.0,93.839928,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.4560416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.839928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.925 / 20 | dB | 2499/100.0%/0.0%/0.0% |  |

<br>

# PERFORMANCE CHARACTERISTICS

## Voltage Curvature vs Temperature Performance<br>

| ![xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59](xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0eccd662f62d96a198841ede934596fa](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0eccd662f62d96a198841ede934596fa.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0eccd662f62d96a198841ede934596fa](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0eccd662f62d96a198841ede934596fa.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0eccd662f62d96a198841ede934596fa](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0eccd662f62d96a198841ede934596fa.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0eccd662f62d96a198841ede934596fa](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0eccd662f62d96a198841ede934596fa.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance<br>

| ![xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6](xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__898df9bf3c115f457deb7bdf2c2a827a](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__898df9bf3c115f457deb7bdf2c2a827a.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__898df9bf3c115f457deb7bdf2c2a827a](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__898df9bf3c115f457deb7bdf2c2a827a.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__898df9bf3c115f457deb7bdf2c2a827a](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__898df9bf3c115f457deb7bdf2c2a827a.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__898df9bf3c115f457deb7bdf2c2a827a](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__898df9bf3c115f457deb7bdf2c2a827a.png "") |
| :-- |
|  |
<br>
