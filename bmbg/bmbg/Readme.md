14.03.2022, 00:39:23

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
| Reference Voltage Curvature | 0.0 / 4.408 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.538945216,10.0,11.2331136,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.538945216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.2331136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.294 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.04569599999997,10.0,66.851328,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.04569599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.851328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -45.604 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.263778,10.0,76.564494,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.263778" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.564494" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.075 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.625 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.602879999999985,10.0,105.75456000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.602879999999985" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.75456000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.002 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.6282000000000387,10.0,128.71452000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.6282000000000387" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.71452000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.349 / 1.4 | V | 2478/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.346 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1992803328,10.0,127.9776576,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1992803328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.9776576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 216.975 / 250.0 | mV | 2472/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.106 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.28852000000002,10.0,129.35352,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.28852000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="129.35352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.351 / 1.4 | V | 2472/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -1714.11 | <svg height="20" width="150"><polyline points="28.40461410173261,3,28.40461410173261,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.70230705086631,10.0,87.70230705086631,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,144.4378949319003,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="144.4378949319003" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1148.151 / 1200.0 | uV/°C | 2499/98.9196%/1.0804%/0.0% |  |
| Max. Supply Current | -85.0 / -84.563 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.199040000000097,10.0,100.53887999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.199040000000097" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.53887999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.84 / -70.0 | uA | 2472/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ss_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ll_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/hh_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ss_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/hh_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/hh_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/ff_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/hh_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/hh_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ff_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/hh_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_3/ss_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/tt_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ll_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ll_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/hh_mm/dc.csv Index:12 vsup:5.0 <br>

## Reference Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.201 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.49824000000001,10.0,82.18524000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.49824000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.18524000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.22 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.388 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.51627968,10.0,59.36051136,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.51627968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.36051136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.785 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.198 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.96035199999998,10.0,65.79609600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.96035199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.79609600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.218 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.796 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.06487639999999,10.0,105.0094272,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.06487639999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.0094272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.336 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.325 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.639040000000016,10.0,126.37728,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.639040000000016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.37728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.101 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.397800000000004,10.0,128.71956,10.0" style="stroke:green;stroke-width:2" /><circle cx="39.397800000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.71956" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.349 / 1.4 | V | 2488/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.859 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.946549184,10.0,119.7132672,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.946549184" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.7132672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.263 / 25.0 | mV | 2486/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.1 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.936280000000004,10.0,126.77448000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.936280000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.77448000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.344 / 1.4 | V | 2488/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -5.11 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.603712,10.0,122.766744,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.603712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.766744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.269 / 20.0 | mV/V | 2487/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -84.432 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.72495999999998,10.0,119.10431999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.72495999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.10431999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.812 / -70.0 | uA | 2486/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 12.924 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.6109056,10.0,28.947000000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.6109056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="28.947000000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.019 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.61 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.755826272,10.0,7.134408032,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.755826272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.134408032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.741 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -65.128 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.537760000000006,10.0,66.23904000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.537760000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.23904000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.434 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.696 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.1427968,10.0,90.41487839999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.1427968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.41487839999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.211 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -110.054 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.017107692307691,10.0,108.41752615384615,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.017107692307691" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.41752615384615" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -24.831 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.797 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.8254848,10.0,93.72301920000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.8254848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.72301920000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.901 / 20 | dB | 2478/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 0.501 | <svg height="20" width="150"><polyline points="35.956064302023506,3,35.956064302023506,17,62.37635078874875,17,62.37635078874875,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.16620754538613,10.0,49.16620754538613,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2.681 / 1.4 | V | 15/20.0%/80.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 252.6 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.789774237519829,17,5.789774237519829,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.394887118759915,10.0,4.394887118759915,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.81878454186095,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="5.81878454186095" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 12904.27 / 250.0 | mV | 15/0.0%/100.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 0.121 | <svg height="20" width="150"><polyline points="36.14837062889865,3,36.14837062889865,17,55.005877570621955,17,55.005877570621955,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.5771240997603,10.0,45.5771240997603,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.939 / 1.5 | V | 15/26.6667%/73.3333%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -4435020.0 | <svg height="20" width="150"><polyline points="79.20133162837868,3,79.20133162837868,17,81.24366153710481,17,81.24366153710481,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.22249658274174,10.0,80.22249658274174,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3729420.0 / 1200.0 | uV/°C | 15/0.0%/100.0%/0.0% |  |
| Max. Supply Current | -85.0 / -858.089 | <svg height="20" width="150"><polyline points="119.103254421578,3,119.103254421578,17,121.3559689425758,17,121.3559689425758,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="120.2296116820769,10.0,120.2296116820769,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 100.754 / -70.0 | uA | 15/6.6667%/93.3333%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:2 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:2 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 20°C":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:1 vsup:4.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:2 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ff/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/hh/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/tt/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ll/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:0 vsup:3.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:1 vsup:4.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/ss/dc.csv Index:2 vsup:5.0 <br>

## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / -2.349 | <svg height="20" width="150"><polyline points="68.38443034916065,3,68.38443034916065,17,76.19472056923998,17,76.19472056923998,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.28957545920031,10.0,72.28957545920031,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.026 / 1.4 | V | 2437/27.8211%/72.1789%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 15.758 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.644357806162137,17,5.644357806162137,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.322178903081069,10.0,4.322178903081069,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.040614542654518,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.040614542654518" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 55869.58 / 250.0 | mV | 2444/0.0818%/99.9182%/0.0% |  |
| Reference Voltage at 20°C | 1 / -14.746 | <svg height="20" width="150"><polyline points="87.77530509691313,3,87.77530509691313,17,89.92893036611628,17,89.92893036611628,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.85211773151471,10.0,88.85211773151471,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 12.0 / 1.4 | V | 2445/14.9284%/85.0716%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -8404520.0 | <svg height="20" width="150"><polyline points="76.54754733856608,3,76.54754733856608,17,78.5691238242423,17,78.5691238242423,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.55833558140418,10.0,77.55833558140418,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 7612917.0 / 1200.0 | uV/°C | 2448/1.5523%/98.4477%/0.0% |  |
| Max. Supply Current | -85.0 / -63.139 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.3127403467479635,17,5.3127403467479635,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.156370173373982,10.0,4.156370173373982,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.455796121093062,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.455796121093062" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 6821.688 / -70.0 | uA | 2436/0.0%/100.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:38 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:0 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 20°C":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:16 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ss_mm/dc.csv Index:0 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:3 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:7 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:10 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:11 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:12 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:17 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:20 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:22 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:34 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:35 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:39 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:40 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 vsup:5.0 <br>

## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / -1.62 | <svg height="20" width="150"><polyline points="107.34398800865057,3,107.34398800865057,17,123.27345586486501,17,123.27345586486501,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="115.30872193675779,10.0,115.30872193675779,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.996 / 1.4 | V | 15/0.0%/100.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 89.924 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.202613716948637,17,5.202613716948637,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.101306858474318,10.0,4.101306858474318,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.728794813088846,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.728794813088846" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 17767.8 / 25.0 | mV | 15/0.0%/100.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 0.549 | <svg height="20" width="150"><polyline points="26.861234334548797,3,26.861234334548797,17,53.315464713198125,17,53.315464713198125,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.08834952387346,10.0,40.08834952387346,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.271 / 1.5 | V | 15/6.6667%/93.3333%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -38966.3 | <svg height="20" width="150"><polyline points="89.4125098371572,3,89.4125098371572,17,91.50331436527635,17,91.50331436527635,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.45791210121678,10.0,90.45791210121678,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 24466.66 / 20.0 | mV/V | 15/6.6667%/93.3333%/0.0% |  |
| Max. Supply Current | -100.0 / -179.711 | <svg height="20" width="150"><polyline points="81.62720048443366,3,81.62720048443366,17,111.21930213330283,17,111.21930213330283,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="96.42325130886825,10.0,96.42325130886825,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -33.726 / -70.0 | uA | 15/40.0%/60.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:2 te:140.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:2 te:140.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 3.3V":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:2 te:140.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 3.3V":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:2 te:140.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ff/dc.csv Index:2 te:140.0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:tt file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/tt/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ll file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ll/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:0 te:-40.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/ss/dc.csv Index:2 te:140.0 <br>

## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / -0.854 | <svg height="20" width="150"><polyline points="60.37759172024895,3,60.37759172024895,17,72.7559570883334,17,72.7559570883334,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.56677440429118,10.0,66.56677440429118,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.799 / 1.4 | V | 2494/49.0778%/50.9222%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 41.546 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.142608088017711,17,5.142608088017711,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.071304044008856,10.0,4.071304044008856,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2369891439592995,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.2369891439592995" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 25244.01 / 25.0 | mV | 2489/0.0%/100.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / -0.942 | <svg height="20" width="150"><polyline points="66.54261323288841,3,66.54261323288841,17,79.6314786759431,17,79.6314786759431,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.08704595441576,10.0,73.08704595441576,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.459 / 1.4 | V | 2492/12.3596%/87.6404%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -18543.4 | <svg height="20" width="150"><polyline points="60.33701626580741,3,60.33701626580741,17,62.46083158322388,17,62.46083158322388,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.39892392451564,10.0,61.39892392451564,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 27977.5 / 20.0 | mV/V | 2483/7.5312%/92.4688%/0.0% |  |
| Max. Supply Current | -100.0 / -84.606 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,36.19691603723803,17,36.19691603723803,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.598458018619016,10.0,19.598458018619016,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.034112213414367,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="20.034112213414367" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 30.133 / -70.0 | uA | 2461/6.9484%/93.0516%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ff_mm/dc.csv Index:49 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 3.3V":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:5 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 3.3V":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:20 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:22 te:20.0 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:18 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:19 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:27 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:40 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:43 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/tt_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:16 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:17 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:21 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:23 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:24 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:25 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:26 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:28 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:29 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:30 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:31 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:32 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:33 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:34 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:35 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:36 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:37 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:38 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:39 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:41 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:42 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:44 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:45 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:46 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:47 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:48 te:20.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ll_mm/dc.csv Index:49 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:0 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:1 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:2 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:3 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:4 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:5 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:6 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:7 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:8 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:9 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:10 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:11 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:12 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:13 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:14 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:15 te:20.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_8/ss_mm/dc.csv Index:16 te:20.0 <br>

## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 19.272 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.75096,10.0,60.1277232,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.75096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="60.1277232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 39.672 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.769 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.213423424,10.0,8.86938368,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.213423424" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.86938368" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.344 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -65.54 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.056720000000006,10.0,66.72756000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.056720000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.72756000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.298 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 9.308 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="95.6806032,10.0,103.197696,10.0" style="stroke:green;stroke-width:2" /><circle cx="95.6806032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.197696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.875 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -112.086 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.766276923076925,10.0,133.64930584615385,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.766276923076925" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="133.64930584615385" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.053 / 10 | dB | 2490/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.261 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.8510384,10.0,110.151264,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.8510384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.151264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.323 / 20 | dB | 2490/100.0%/0.0%/0.0% |  |

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
