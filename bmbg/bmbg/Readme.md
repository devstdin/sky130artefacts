23.02.2022, 19:07:27

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
| Reference Voltage Curvature | 0.0 / 4.419 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.545247807999999,10.0,11.27693568,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.545247807999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.27693568" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.37 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.03216,10.0,66.84671999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.03216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.84671999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -45.96 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.242406,10.0,76.5584442,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.242406" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.5584442" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.974 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.624 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.60768000000006,10.0,105.75935999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.60768000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.75935999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs Temperature (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.104 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.52927999999997,10.0,129.57888,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.52927999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="129.57888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.352 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.333 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.1918422144,10.0,108.1612992,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.1918422144" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.1612992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 182.572 / 250.0 | mV | 2498/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.109 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.135960000000004,10.0,133.39020000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.135960000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="133.39020000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.362 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -827.674 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.339559999999995,10.0,132.156708,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.339559999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="132.156708" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 952.612 / 1200.0 | uV/°C | 2500/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -85.003 | <svg height="20" width="150"><polyline points="3.033592161828785,3,3.033592161828785,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.01679608091439,10.0,75.01679608091439,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,100.41918885593351,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="100.41918885593351" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -74.853 / -70.0 | uA | 2498/99.96%/0.04%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_9/ll_mm/dc.csv Index:21 vsup:5.0 <br>

## Reference Voltage Curvature vs VDD<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.201 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.4644,10.0,82.17876,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.4644" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.17876" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.22 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 3.393 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.541283840000002,10.0,59.46062016,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.541283840000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.46062016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.802 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.198 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.929823999999996,10.0,65.79091199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.929823999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.79091199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.218 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.798 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.0741896,10.0,105.05442000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.0741896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.05442000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.348 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.322 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.652960000000014,10.0,126.37967999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.652960000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.37967999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.296 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>

## Reference Voltage Curvature vs VDD (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.099 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.73071999999997,10.0,124.53240000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.73071999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.53240000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.338 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.899 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.176275839999999,10.0,115.47949440000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.176275839999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="115.47949440000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 19.528 / 25.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.460000000000015,10.0,122.43611999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="38.460000000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.43611999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.332 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -3.681 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.74919200000001,10.0,120.793224,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.74919200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.793224" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.72 / 20.0 | mV/V | 2500/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -84.202 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.83039999999997,10.0,119.27327999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.83039999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.27327999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.776 / -70.0 | uA | 2500/100.0%/0.0%/0.0% |  |

<br>

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
| PSRR+ at 10 Hz | -120 / -112.734 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.048492307692314,10.0,135.80678806153847,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.048492307692314" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.80678806153847" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.105 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.132 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.43135840000001,10.0,94.1596992,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.43135840000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.1596992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.992 / 20 | dB | 2497/100.0%/0.0%/0.0% |  |

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
