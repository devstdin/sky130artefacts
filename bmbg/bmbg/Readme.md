13.03.2022, 22:42:21

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
| Mean Reference Voltage | 1 / 0.969 | <svg height="20" width="150"><polyline points="13.5094444568047,3,13.5094444568047,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.25472222840236,10.0,80.25472222840236,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,139.56991567846578,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="139.56991567846578" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.378 / 1.4 | V | 2485/99.9598%/0.0402%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.78 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.449282592,10.0,106.5198144,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.449282592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.5198144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 179.722 / 250.0 | mV | 2481/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.099 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.53127999999999,10.0,135.15276000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.53127999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.15276000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.367 / 1.4 | V | 2481/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -1704.19 | <svg height="20" width="150"><polyline points="27.999521381176855,3,27.999521381176855,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.49976069058843,10.0,87.49976069058843,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,134.80606558110867,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="134.80606558110867" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 954.073 / 1200.0 | uV/°C | 2500/99.24%/0.76%/0.0% |  |
| Max. Supply Current | -85.0 / -83.457 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.81376000000001,10.0,96.64896000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.81376000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.64896000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.245 / -70.0 | uA | 2481/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh_mm/dc.csv Index:5 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ff_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ss_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/hh_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ss_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/hh_mm/dc.csv Index:27 vsup:5.0 <br>

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
| Mean Reference Voltage | 1 / 1.105 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.833840000000016,10.0,122.85228000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.833840000000016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.85228000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.333 / 1.4 | V | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.844 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.85906976,10.0,124.9364352,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.85906976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.9364352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 21.17 / 25.0 | mV | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.104 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.26504000000004,10.0,121.22616000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.26504000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.22616000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.328 / 1.4 | V | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -6.065 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.164416,10.0,123.53516400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.164416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.53516400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.482 / 20.0 | mV/V | 2489/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.51 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.15248,10.0,119.98031999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.15248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.98031999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.629 / -70.0 | uA | 2489/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -111.371 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.55827692307693,10.0,108.3644676923077,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.55827692307693" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.3644676923077" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -24.879 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.927 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.4517024,10.0,94.2775584,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.4517024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.2775584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.016 / 20 | dB | 2488/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.80720000000001,10.0,82.40231999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.80720000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.40231999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.221 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.408 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.538945216,10.0,11.2331136,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.538945216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.2331136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.294 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.04569599999997,10.0,66.851328,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.04569599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.851328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -45.604 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.263778,10.0,76.564494,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.263778" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.564494" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.075 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.625 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.602879999999985,10.0,105.75456000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.602879999999985" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.75456000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 0.969 | <svg height="20" width="150"><polyline points="13.5094444568047,3,13.5094444568047,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.25472222840236,10.0,80.25472222840236,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,139.56991567846578,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="139.56991567846578" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.378 / 1.4 | V | 2485/99.9598%/0.0402%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.78 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.449282592,10.0,106.5198144,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.449282592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.5198144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 179.722 / 250.0 | mV | 2481/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.099 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.53127999999999,10.0,135.15276000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.53127999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.15276000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.367 / 1.4 | V | 2481/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -1704.19 | <svg height="20" width="150"><polyline points="27.999521381176855,3,27.999521381176855,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.49976069058843,10.0,87.49976069058843,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,134.80606558110867,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="134.80606558110867" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 954.073 / 1200.0 | uV/°C | 2500/99.24%/0.76%/0.0% |  |
| Max. Supply Current | -85.0 / -83.457 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.81376000000001,10.0,96.64896000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.81376000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.64896000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.245 / -70.0 | uA | 2481/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh_mm/dc.csv Index:5 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Sensitivity at 20°C":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ff_mm/dc.csv Index:5 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:4 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/tt_mm/dc.csv Index:37 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ss_mm/dc.csv Index:26 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/ff_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/hh_mm/dc.csv Index:24 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ll_mm/dc.csv Index:32 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ll_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:13 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/ff_mm/dc.csv Index:43 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ss_mm/dc.csv Index:18 vsup:5.0 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/ff_mm/dc.csv Index:21 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/hh_mm/dc.csv Index:19 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/ll_mm/dc.csv Index:16 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/hh_mm/dc.csv Index:27 vsup:5.0 <br>

## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.201 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.49824000000001,10.0,82.18524000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.49824000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.18524000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.22 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.388 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.51627968,10.0,59.36051136,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.51627968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.36051136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.785 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.198 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.96035199999998,10.0,65.79609600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.96035199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.79609600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.218 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.796 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.06487639999999,10.0,105.0094272,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.06487639999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.0094272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.336 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.325 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.639040000000016,10.0,126.37728,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.639040000000016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.37728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.105 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.833840000000016,10.0,122.85228000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.833840000000016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.85228000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.333 / 1.4 | V | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.844 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.85906976,10.0,124.9364352,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.85906976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.9364352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 21.17 / 25.0 | mV | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.104 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.26504000000004,10.0,121.22616000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.26504000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.22616000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.328 / 1.4 | V | 2489/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -6.065 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.164416,10.0,123.53516400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.164416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.53516400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.482 / 20.0 | mV/V | 2489/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.51 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.15248,10.0,119.98031999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.15248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.98031999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.629 / -70.0 | uA | 2489/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 12.924 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.6109056,10.0,28.947000000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.6109056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="28.947000000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.019 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.61 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.755826272,10.0,7.134408032,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.755826272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.134408032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.741 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -65.128 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.537760000000006,10.0,66.23904000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.537760000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.23904000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.434 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.696 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.1427968,10.0,90.41487839999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.1427968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.41487839999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.211 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -111.371 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.55827692307693,10.0,108.3644676923077,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.55827692307693" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.3644676923077" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -24.879 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.927 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.4517024,10.0,94.2775584,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.4517024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.2775584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.016 / 20 | dB | 2488/100.0%/0.0%/0.0% |  |

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
