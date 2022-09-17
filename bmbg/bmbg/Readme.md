17.09.2022, 22:12:03

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![bmbg](resources/bmbg.png "bmbg")

<br>

[🔗 Schematics](bmbg_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](bmbg_bmbg_netgen_comp.out)<br>

# SPECIFICATIONS

## Reference Voltage Curvature vs Temperature <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.80720000000001,10.0,82.40231999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.80720000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.40231999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.221 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.409 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.539336896,10.0,11.23349952,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.539336896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.23349952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.294 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.04569599999997,10.0,66.851328,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.04569599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.851328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -45.603 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.263796,10.0,76.5645348,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.263796" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.5645348" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.076 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.625 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.602879999999985,10.0,105.75456000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.602879999999985" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.75456000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 0.936 | <svg height="20" width="150"><polyline points="22.90635755859548,3,22.90635755859548,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="84.95317877929773,10.0,84.95317877929773,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,125.58081684640142,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="125.58081684640142" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.331 / 1.4 | V | 2436/99.6305%/0.3695%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.382 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,125.06886379318821,17,125.06886379318821,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.0344318965941,10.0,64.0344318965941,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1864929038995915,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.1864929038995915" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 294.916 / 250.0 | mV | 2422/99.8348%/0.1652%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.111 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.93264000000001,10.0,124.93235999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.93264000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.93235999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.339 / 1.4 | V | 2418/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -1722.49 | <svg height="20" width="150"><polyline points="28.74467662849146,3,28.74467662849146,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.87233831424572,10.0,87.87233831424572,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,135.87132164695174,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="135.87132164695174" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 974.143 / 1200.0 | uV/°C | 2500/96.72%/3.28%/0.0% |  |
| Max. Supply Current | -85.0 / -83.105 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.19008000000006,10.0,96.94175999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.19008000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.94175999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.214 / -70.0 | uA | 2418/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>
  
> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ss_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ss_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ss_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/tt_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ss_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/hh_mm/dc.csv Index:18 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/hh_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ss_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ff_mm/dc.csv Index:41 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ss_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ss_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ss_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/hh_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/hh_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/hh_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ll_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ss_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ss_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ss_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ss_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ff_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ff_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/hh_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/hh_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/hh_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/hh_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ss_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ss_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ff_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ff_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ff_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/hh_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/hh_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/hh_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/tt_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/tt_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ss_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/hh_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/tt_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ll_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ll_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ss_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ss_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/hh_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/hh_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/hh_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ll_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ll_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ss_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ss_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ss_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ss_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ff_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ff_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/hh_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ss_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ss_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ss_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ss_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ff_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/hh_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/tt_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/hh_mm/dc.csv Index:20 vsup:5.0 <br>
</details><br>


## Reference Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.201 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.49788000000004,10.0,82.18524000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.49788000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.18524000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.22 / 1.4 | V | 14/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.388 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.5156864,10.0,59.35991808,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.5156864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.35991808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.785 / 25.0 | mV | 14/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.198 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.960064,10.0,65.79609600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.960064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.79609600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.218 / 1.5 | V | 14/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.797 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.06801200000001,10.0,105.00939480000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.06801200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.00939480000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.336 / 20.0 | mV/V | 14/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.325 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,76.49101011011746,17,76.49101011011746,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.74550505505873,10.0,39.74550505505873,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.25066048344157,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="24.25066048344157" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -41.217 / -70.0 | uA | 15/93.3333%/6.6667%/0.0% |  |

<details><summary>Show specification violation details...</summary>
  
> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_0/hh/dc.csv Index:1 te:20.0 <br>
</details><br>


## Reference Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.103 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.16424000000002,10.0,134.90400000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.16424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="134.90400000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.366 / 1.4 | V | 2460/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.687 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.955450176,10.0,133.021632,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.955450176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="133.021632" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 22.573 / 25.0 | mV | 2460/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.103 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.25748000000003,10.0,132.73068,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.25748000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="132.73068" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.36 / 1.4 | V | 2461/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -3.82 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.247928,10.0,125.37782399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.247928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.37782399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.994 / 20.0 | mV/V | 2460/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -84.285 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.43104000000001,10.0,118.70544,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.43104000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="118.70544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.895 / -70.0 | uA | 2460/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 12.924 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.6109056,10.0,28.947014400000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.6109056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="28.947014400000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.019 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.61 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.755827136,10.0,7.134408896,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.755827136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.134408896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.741 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -65.127 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.542440000000006,10.0,66.24732,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.542440000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.24732" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.431 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.585 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.6091232,10.0,89.9685312,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.6091232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.9685312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.118 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -111.826 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.05427692307693,10.0,108.71948307692308,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.05427692307693" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.71948307692308" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -24.559 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.712 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.417024,10.0,93.2893248,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.417024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.2893248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.81 / 20 | dB | 2421/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.217 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.05772000000005,10.0,86.74068,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.05772000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.74068" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.233 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.056 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.336493888,10.0,8.516356607999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.336493888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.516356607999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.577 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.219 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.992224,10.0,69.849984,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.992224" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.849984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.232 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / 2.662 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.15973704000001,10.0,79.5568314,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.15973704000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.5568314" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 75.947 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.409 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.669760000000025,10.0,106.28064,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.669760000000025" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.28064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.242 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 0.812 | <svg height="20" width="150"><polyline points="19.42104640952699,3,19.42104640952699,17,54.44889446091138,17,54.44889446091138,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.934970435219185,10.0,36.934970435219185,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2.457 / 1.4 | V | 2359/98.4739%/1.5261%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.552 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,115.16616545007919,17,115.16616545007919,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.083082725039596,10.0,59.083082725039596,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.247728667553195,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.247728667553195" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 320.952 / 250.0 | mV | 2423/99.2571%/0.7429%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.105 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.66031999999998,10.0,131.14631999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.66031999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="131.14631999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.356 / 1.4 | V | 2339/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -1765.19 | <svg height="20" width="150"><polyline points="30.35061439221967,3,30.35061439221967,17,146.4911592378949,17,146.4911592378949,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.42088681505729,10.0,88.42088681505729,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1210.515 / 1200.0 | uV/°C | 2488/99.0354%/0.9646%/0.0% |  |
| Max. Supply Current | -85.0 / -28486.5 | <svg height="20" width="150"><polyline points="95.23306844739082,3,95.23306844739082,17,97.28283680563636,17,97.28283680563636,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="96.2579526265136,10.0,96.2579526265136,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 14914.57 / -70.0 | uA | 2495/90.6212%/9.3788%/0.0% |  |

<details><summary>Show specification violation details...</summary>
  
> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/hh_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/hh_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ss_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/hh_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ll_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ss_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/hh_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/hh_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/ff_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/hh_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ss_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ss_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/ll_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/ss_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/ff_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/ff_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/tt_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ll_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ss_mm/dc.csv Index:5 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ss_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ss_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ff_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/ss_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/hh_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ff_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/ff_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/tt_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ff_mm/dc.csv Index:19 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/hh_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/hh_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/hh_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ff_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ff_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/ss_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/ss_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/tt_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/hh_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/hh_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/tt_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ff_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/hh_mm/dc.csv Index:34 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/hh_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/hh_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/hh_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/tt_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/tt_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ss_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ff_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/hh_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/hh_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/hh_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/hh_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/hh_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/hh_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/tt_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ll_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ll_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ss_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/hh_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/hh_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/hh_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ll_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/hh_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/hh_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/hh_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/hh_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/tt_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/tt_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/tt_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ll_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ll_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ll_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ll_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_6/ss_mm/dc.csv Index:3 vsup:5.0 <br>
</details><br>


## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.54227999999999,10.0,86.21868000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.54227999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.21868000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.231 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.512 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.2300128,10.0,62.1818112,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.2300128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.1818112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.275 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.214 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.744608,10.0,68.74895999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.744608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.74895999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.228 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.896 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.42598880000001,10.0,106.36532760000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.42598880000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.36532760000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.713 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.245 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.02447999999998,10.0,126.64031999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.02447999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.64031999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.242 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.36027999999999,10.0,135.94727999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.36027999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.94727999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.369 / 1.4 | V | 2455/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.928 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.3461872,10.0,115.091616,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.3461872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="115.091616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 19.46 / 25.0 | mV | 2453/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.099 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.69976000000004,10.0,121.12032,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.69976000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.12032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.328 / 1.4 | V | 2455/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -4.388 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.2032,10.0,118.98476400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.2032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="118.98476400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.218 / 20.0 | mV/V | 2455/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -84.028 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.66416000000001,10.0,117.72623999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.66416000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.72623999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -76.099 / -70.0 | uA | 2463/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.179 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.9778752,10.0,29.5149504,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.9778752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.5149504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.413 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.62 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.785829824,10.0,7.176235999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.785829824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.176235999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.756 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -65.097 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.651880000000006,10.0,66.27072000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.651880000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.27072000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.425 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 8.303 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.8534976,10.0,97.6213056,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.8534976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="97.6213056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.713 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -112.01 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.850461538461534,10.0,130.6900836923077,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.850461538461534" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.6900836923077" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -4.724 / 10 | dB | 2443/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.626 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.6062928,10.0,101.16235200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.6062928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.16235200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.45 / 20 | dB | 2416/100.0%/0.0%/0.0% |  |

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

## Voltage Curvature vs Temperature Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4f40e5d2c3374a33215709ccd8d638c6](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4f40e5d2c3374a33215709ccd8d638c6.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4f40e5d2c3374a33215709ccd8d638c6](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4f40e5d2c3374a33215709ccd8d638c6.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4f40e5d2c3374a33215709ccd8d638c6](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4f40e5d2c3374a33215709ccd8d638c6.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4f40e5d2c3374a33215709ccd8d638c6](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4f40e5d2c3374a33215709ccd8d638c6.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cb8538a5b18f9753da10bdfa881fc54a](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cb8538a5b18f9753da10bdfa881fc54a.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cb8538a5b18f9753da10bdfa881fc54a](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cb8538a5b18f9753da10bdfa881fc54a.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cb8538a5b18f9753da10bdfa881fc54a](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cb8538a5b18f9753da10bdfa881fc54a.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cb8538a5b18f9753da10bdfa881fc54a](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cb8538a5b18f9753da10bdfa881fc54a.png "") |
| :-- |
|  |
<br>
