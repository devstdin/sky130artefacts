23.01.2024, 09:30:37

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![bmbg](resources/bmbg.png "bmbg")

<br>

[🔗 Schematics](bmbg_sch.pdf)<br>

# LVS

[🔗 LVS-report](bmbg_bmbg_netgen_comp.out)<br>

# SPECIFICATIONS

## Reference Voltage Curvature vs Temperature <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.80720000000001,10.0,82.40231999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.80720000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.40231999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.221 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.409 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.53933632,10.0,11.23349952,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.53933632" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.23349952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.294 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.04569599999997,10.0,66.851328,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.04569599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.851328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -45.603 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.263796,10.0,76.5645348,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.263796" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.5645348" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.076 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.625 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.602879999999985,10.0,105.75456000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.602879999999985" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.75456000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 0.921 | <svg height="20" width="150"><polyline points="26.86364523734438,3,26.86364523734438,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="86.93182261867219,10.0,86.93182261867219,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,142.05638900151675,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="142.05638900151675" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.384 / 1.4 | V | 2407/99.7092%/0.2908%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.645 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.523588544,10.0,20.59113216,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.523588544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.59113216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 30.54 / 250.0 | mV | 2393/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.107 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.417760000000015,10.0,140.45520000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.417760000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="140.45520000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.382 / 1.4 | V | 2396/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -160.513 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.36922000000001,10.0,84.960618,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.36922000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.960618" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 166.01 / 1200.0 | uV/°C | 2395/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -84.224 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.45152000000007,10.0,98.77343999999994,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.45152000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="98.77343999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.024 / -70.0 | uA | 2393/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_8/ll_mm/dc.csv Index:2 vsup:5.0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_4/ll_mm/dc.csv Index:6 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/tt_mm/dc.csv Index:49 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/tt_mm/dc.csv Index:9 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_6/hh_mm/dc.csv Index:41 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/tt_mm/dc.csv Index:29 vsup:5.0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/tt_mm/dc.csv Index:2 vsup:5.0 <br>
</details><br>


## Reference Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.201 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.49788000000004,10.0,82.18524000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.49788000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.18524000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.22 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.388 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.5156864,10.0,59.35991808,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.5156864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.35991808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.785 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.198 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.960064,10.0,65.79609600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.960064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.79609600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.218 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.797 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.06801200000001,10.0,105.00939480000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.06801200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.00939480000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.336 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.325 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.639040000000016,10.0,126.37728,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.639040000000016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.37728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.044 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.986159999999984,10.0,122.37744000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.986159999999984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.37744000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.332 / 1.4 | V | 2455/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.845 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.869338112,10.0,135.4528128,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.869338112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.4528128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 22.995 / 25.0 | mV | 2451/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.102 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.86112000000002,10.0,120.56448,10.0" style="stroke:green;stroke-width:2" /><circle cx="39.86112000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.56448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.327 / 1.4 | V | 2453/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -3.087 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.88824000000001,10.0,127.12321200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.88824000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.12321200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.479 / 20.0 | mV/V | 2452/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.487 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.26048000000002,10.0,118.34063999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.26048000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="118.34063999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.971 / -70.0 | uA | 2451/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -112.41 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.40738461538462,10.0,108.50038153846155,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.40738461538462" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.50038153846155" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -24.757 / 10 | dB | 2499/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.737 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.5374608,10.0,93.97531199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.5374608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.97531199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.953 / 20 | dB | 2410/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.217 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.95728,10.0,86.64528000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.95728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.64528000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.232 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.057 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.336667264000001,10.0,8.407310592,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.336667264000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.407310592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.388 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.92627199999998,10.0,69.78777600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.92627199999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.78777600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.232 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / 1.38 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.08278104,10.0,79.48157220000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.08278104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.48157220000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.693 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.087 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.768640000000055,10.0,108.73535999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.768640000000055" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.73535999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -73.986 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.113 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,122.7385707871148,17,122.7385707871148,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.8692853935574,10.0,62.8692853935574,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.96534233589994,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="36.96534233589994" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.481 / 1.4 | V | 2432/99.9178%/0.0822%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.107 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.2133728,10.0,30.994078079999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.2133728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="30.994078079999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 48.601 / 250.0 | mV | 2429/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.118 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.34067999999999,10.0,126.86016,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.34067999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.86016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.344 / 1.4 | V | 2434/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -153.848 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.76912,10.0,94.237932,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.76912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.237932" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 320.632 / 1200.0 | uV/°C | 2474/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.423 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="27.743039999999983,10.0,145.17983999999993,10.0" style="stroke:green;stroke-width:2" /><circle cx="27.743039999999983" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="145.17983999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -70.19 / -70.0 | uA | 2366/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_4/ff_mm/dc.csv Index:23 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_3/hh_mm/dc.csv Index:46 vsup:5.0 <br>
</details><br>


## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.38568000000001,10.0,86.07036,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.38568000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.07036" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.231 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.518 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.26492416,10.0,62.144313600000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.26492416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.144313600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.268 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.214 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.61961599999998,10.0,68.686464,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.61961599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.686464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.228 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.9 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.44138600000001,10.0,106.36421879999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.44138600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.36421879999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.712 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -90.648 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.88816000000002,10.0,127.86767999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.88816000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.86767999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -73.986 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.128 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,126.18905670546266,17,126.18905670546266,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.59452835273133,10.0,64.59452835273133,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.3277983805772,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="42.3277983805772" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.468 / 1.4 | V | 2446/99.9182%/0.0818%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.937 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.395973183999999,10.0,126.5783808,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.395973183999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.5783808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 21.455 / 25.0 | mV | 2440/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.125 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.05040000000002,10.0,136.41204000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.05040000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="136.41204000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.371 / 1.4 | V | 2447/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -3.612 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.997196,10.0,123.892608,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.997196" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.892608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.581 / 20.0 | mV/V | 2445/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -84.062 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.50383999999998,10.0,118.78464000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.50383999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="118.78464000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.878 / -70.0 | uA | 2457/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_3/ff_mm/dc.csv Index:22 te:20.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg_ext/batch_0/hh_mm/dc.csv Index:31 te:20.0 <br>
</details><br>


## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.039881599999998,10.0,29.6575824,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.039881599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.6575824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.512 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.622 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.791591840000001,10.0,7.1858891840000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.791591840000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.1858891840000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.759 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -64.987 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.045360000000024,10.0,66.55980000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.045360000000024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.55980000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.344 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.964 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.22942719999999,10.0,95.65082400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="89.22942719999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.65082400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.302 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -112.32 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.507076923076932,10.0,135.93690745846155,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.507076923076932" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.93690745846155" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.012 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.146 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.2996144,10.0,99.70008,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.2996144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.70008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.146 / 20 | dB | 2432/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## Voltage Curvature vs Temperature Performance<br>

| ![xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59](xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0f9911cc5bffe01da79395090502359d.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance<br>

| ![xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6](xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__55c71def2269771b3e4ae33d001eeeb3.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__562fe08e23b59c67c92ef8a1d2c1902b.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__3efffb6e1c44a0e9d5c28a35bb88ea0f.png "") |
| :-- |
|  |
<br>
