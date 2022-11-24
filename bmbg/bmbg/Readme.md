24.11.2022, 23:47:46

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
| Mean Reference Voltage | 1 / 0.969 | <svg height="20" width="150"><polyline points="13.257172133288666,3,13.257172133288666,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.12858606664433,10.0,80.12858606664433,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,128.84039883225796,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="128.84039883225796" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.346 / 1.4 | V | 2447/99.4687%/0.5313%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.531 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.3057790464,10.0,111.6323904,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.3057790464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.6323904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 188.598 / 250.0 | mV | 2423/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.06 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.474359999999965,10.0,129.07272,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.474359999999965" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="129.07272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.35 / 1.4 | V | 2423/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -1759.78 | <svg height="20" width="150"><polyline points="30.23456473116246,3,30.23456473116246,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.61728236558123,10.0,88.61728236558123,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,132.9716351891019,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="132.9716351891019" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 911.661 / 1200.0 | uV/°C | 2500/96.92%/3.08%/0.0% |  |
| Max. Supply Current | -85.0 / -83.051 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.71424000000004,10.0,99.14496000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.71424000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.14496000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.985 / -70.0 | uA | 2423/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/tt_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ll_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ss_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ss_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ss_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/tt_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/tt_mm/dc.csv Index:48 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ss_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ss_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ff_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ff_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/hh_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/hh_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/hh_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ll_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/tt_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ff_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ll_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ll_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ff_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/hh_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/tt_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ll_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ll_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ss_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ss_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/tt_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ll_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ll_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ll_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ll_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ss_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/hh_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/tt_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/tt_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ll_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ll_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ss_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ff_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/tt_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ll_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ll_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ss_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ff_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/hh_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/hh_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ss_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ff_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ff_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/hh_mm/dc.csv Index:33 vsup:5.0 <br>
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
| Mean Reference Voltage | 1 / 1.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.25120000000001,10.0,122.26548000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.25120000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.26548000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.331 / 1.4 | V | 2466/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.6258629120000005,10.0,118.7967936,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.6258629120000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="118.7967936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.104 / 25.0 | mV | 2465/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.1 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.96040000000002,10.0,121.34136000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.96040000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.34136000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.329 / 1.4 | V | 2465/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -3.057 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.996204,10.0,120.56095200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.996204" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.56095200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.656 / 20.0 | mV/V | 2465/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.3 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.1624,10.0,122.81183999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.1624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.81183999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.039 / -70.0 | uA | 2465/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -108.032 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.256861538461543,10.0,108.36712615384616,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.256861538461543" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.36712615384616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -24.877 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.674 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.2330304,10.0,94.5281856,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.2330304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.5281856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.068 / 20 | dB | 2418/100.0%/0.0%/0.0% |  |

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
| Mean Reference Voltage | 1 / 0.814 | <svg height="20" width="150"><polyline points="26.63835577799679,3,26.63835577799679,17,77.5368242024338,17,77.5368242024338,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="52.08758999021529,10.0,52.08758999021529,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.946 / 1.4 | V | 2373/98.4408%/1.5592%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.2 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,123.35899074974289,17,123.35899074974289,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.17949537487144,10.0,63.17949537487144,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.577493029208452,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.577493029208452" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 299.105 / 250.0 | mV | 2411/99.8756%/0.1244%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.125 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.87652000000001,10.0,136.11828,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.87652000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="136.11828" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.37 / 1.4 | V | 2360/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -1687.06 | <svg height="20" width="150"><polyline points="24.066362220021574,3,24.066362220021574,17,127.87137459642646,17,127.87137459642646,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.96886840822401,10.0,75.96886840822401,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1642.259 / 1200.0 | uV/°C | 2472/99.7977%/0.2023%/0.0% |  |
| Max. Supply Current | -85.0 / -82.937 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,129.9557653199168,17,129.9557653199168,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.4778826599584,10.0,66.4778826599584,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.46318870563898,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="20.46318870563898" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -67.986 / -70.0 | uA | 2281/99.8246%/0.1754%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ff_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/hh_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/tt_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_5/ll_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ll_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ss_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ss_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ss_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/hh_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/hh_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/hh_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/ss_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/ss_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/ff_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/ff_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_1/hh_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ll_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ll_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ss_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ff_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ff_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/ll_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/hh_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/tt_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ll_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ss_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_7/ss_mm/dc.csv Index:21 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/tt_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt_mm/dc.csv Index:27 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ff_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/hh_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt_mm/dc.csv Index:15 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_9/ll_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_2/ff_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/tt_mm/dc.csv Index:4 vsup:5.0 <br>
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
| Mean Reference Voltage | 1 / 1.125 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,137.97458681607603,17,137.97458681607603,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.48729340803801,10.0,70.48729340803801,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.25278209337146,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="45.25278209337146" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.427 / 1.4 | V | 2465/99.9594%/0.0406%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.91 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.241711168,10.0,145.2862848,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.241711168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="145.2862848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 24.702 / 25.0 | mV | 2465/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.126 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.21023999999998,10.0,128.64756000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.21023999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.64756000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.349 / 1.4 | V | 2468/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -4.681 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.147536,10.0,130.538316,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.147536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.538316" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 15.427 / 20.0 | mV/V | 2468/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.785 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.83151999999997,10.0,119.62559999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.83151999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.62559999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.703 / -70.0 | uA | 2464/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_7/ff_mm/dc.csv Index:15 te:20.0 <br>
</details><br>


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
| PSRR+ at 10 Hz | -120 / -109.492 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.639630769230765,10.0,135.9378957526154,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.639630769230765" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.9378957526154" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.013 / 10 | dB | 2498/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.58 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.38541120000001,10.0,101.36462399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.38541120000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.36462399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.493 / 20 | dB | 2400/100.0%/0.0%/0.0% |  |

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
