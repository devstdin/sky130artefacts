20.02.2022, 16:35:24

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![placeholder](resources/img-placeholder.png "Placeholder")

<br>

[🔗 Schematics](bmbg_sch.pdf)<br>

# SPECIFICATIONS

## Reference Voltage Curvature vs Temperature<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.213 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.58388000000004,10.0,84.78011999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.58388000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.78011999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.227 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.827 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.75514336,10.0,8.539924079999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.75514336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.539924079999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 7.694 / 200.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.215 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.85779200000002,10.0,68.45203199999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.85779200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.45203199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.227 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -20.0 / -10.723 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.1324,10.0,90.950196,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.1324" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.950196" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 53.292 / 100.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -75.0 / -59.984 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.49331199999999,10.0,120.14227199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="89.49331199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.14227199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -54.663 / -50.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs Temperature (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.085 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,103.53900075404246,17,103.53900075404246,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.26950037702123,10.0,53.26950037702123,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.321054542407904,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="24.321054542407904" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.573 / 1.4 | V | 2498/99.9199%/0.0801%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.863 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,96.29657621002097,17,96.29657621002097,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.64828810501049,10.0,49.64828810501049,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.402753995717428,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.402753995717428" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 308.693 / 200.0 | mV | 2492/99.9599%/0.0401%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.096 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,112.11157416177302,17,112.11157416177302,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.55578708088651,10.0,57.55578708088651,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.301072172759998,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="29.301072172759998" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.528 / 1.4 | V | 2498/99.96%/0.04%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1000.0 / -817.261 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.157208,10.0,146.72598960000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.157208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.72598960000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 996.194 / 1000.0 | uV/°C | 2495/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -75.0 / -63.091 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.59584000000001,10.0,116.88268799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.59584000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="116.88268799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -55.229 / -50.0 | uA | 2491/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_2/ff_mm/dc.csv Index:14 vsup:5.0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_1/hh_mm/dc.csv Index:39 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_7/tt_mm/dc.csv Index:45 vsup:5.0 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 20°C":<br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_5/hh_mm/dc.csv Index:23 vsup:5.0 <br>

## Reference Voltage Curvature vs VDD<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.212 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.39812000000005,10.0,84.33912000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.39812000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.33912000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.226 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.889 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.6081376,10.0,112.4058432,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.6081376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="112.4058432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 7.598 / 10.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.209 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.31612799999998,10.0,67.616832,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.31612799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.616832" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.224 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.456 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.8416468,10.0,99.501366,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.8416468" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.501366" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 6.806 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -75.0 / -72.084 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.79615999999999,10.0,120.14227199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.79615999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.14227199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -54.663 / -50.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs VDD (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.097 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="37.84188000000003,10.0,124.49856000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="37.84188000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.49856000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.337 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.743 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,137.08077156035102,17,137.08077156035102,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.04038578017551,10.0,70.04038578017551,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.9782742408025475,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="7.9782742408025475" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 21.48 / 20.0 | mV | 2499/99.96%/0.04%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.097 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="37.848000000000006,10.0,123.27600000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="37.848000000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.27600000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.334 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -4.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.83570400000001,10.0,124.64662799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.83570400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.64662799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.791 / 20.0 | mV/V | 2500/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -75.0 / -64.471 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.644160000000014,10.0,113.112192,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.644160000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="113.112192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -55.883 / -50.0 | uA | 2499/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Reference Voltage Curvature":<br>
> **FAIL:** group:hh_mm file:work/sim/bmbg/bmbg_tb.4_bmbg/batch_7/hh_mm/dc.csv Index:31 te:20.0 <br>

## Reference Voltage Noise Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 12.872 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.5356512,10.0,28.797168,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.5356512" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="28.797168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.915 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.607 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.749090816,10.0,7.121944544,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.749090816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.121944544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.737 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -60.541 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.05348,10.0,78.78756000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.05348" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.78756000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -58.948 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 8.665 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.5913472,10.0,102.81105600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="92.5913472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="102.81105600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.794 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

## PSRR+ Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -110.94 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.03569230769231,10.0,135.8110836923077,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.03569230769231" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.8110836923077" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.101 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 7.866 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.75895039999999,10.0,107.497584,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.75895039999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.497584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.77 / 20 | dB | 2498/100.0%/0.0%/0.0% |  |

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
