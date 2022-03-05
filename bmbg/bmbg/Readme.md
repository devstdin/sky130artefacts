05.03.2022, 14:43:36

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![bmbg](resources/bmbg.png "bmbg")

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
| Mean Reference Voltage | 1 / 1.106 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.03039999999999,10.0,132.48660000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.03039999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="132.48660000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.36 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.517 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2977097472,10.0,109.6341312,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2977097472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="109.6341312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 185.129 / 250.0 | mV | 2499/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.103 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.19952,10.0,130.46411999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.19952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.46411999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.354 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -927.732 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.336079999999995,10.0,130.96299600000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.336079999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.96299600000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 932.717 / 1200.0 | uV/°C | 2500/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.716 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.92735999999999,10.0,98.03135999999994,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.92735999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="98.03135999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -75.101 / -70.0 | uA | 2499/100.0%/0.0%/0.0% |  |

<br>

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
| Mean Reference Voltage | 1 / 1.108 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.050639999999994,10.0,127.60392000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.050639999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.60392000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.346 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.714 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.114158336,10.0,107.7534336,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.114158336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.7534336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.186 / 25.0 | mV | 2499/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.11 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.43692000000003,10.0,126.73812000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.43692000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.73812000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.344 / 1.4 | V | 2500/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -3.996 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.613608000000006,10.0,117.465672,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.613608000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.465672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.796 / 20.0 | mV/V | 2500/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.839 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.57135999999998,10.0,117.21408000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.57135999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.21408000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -76.205 / -70.0 | uA | 2499/100.0%/0.0%/0.0% |  |

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
| PSRR+ at 10 Hz | -120 / -109.692 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.418092307692316,10.0,88.70071384615385,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.418092307692316" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.70071384615385" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.631 / 10 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.993 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.7668944,10.0,94.536264,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.7668944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.536264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.07 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

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
