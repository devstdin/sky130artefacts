02.01.2022, 16:23:57

# Vth Current Reference

10 uA current reference.

![placeholder](resources/img-placeholder.png "Placeholder")

<br>

[🔗 Schematics](vthref_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](vthref_vthref_netgen_comp.out)<br>

# SPECIFICATIONS

## DC Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.192 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.6333552,10.0,47.238412800000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.6333552" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="47.238412800000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.307 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.166 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="26.8474656,10.0,53.6856816,10.0" style="stroke:green;stroke-width:2" /><circle cx="26.8474656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.6856816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.352 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |

<br>

## DC Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.191 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.5025456,10.0,47.330688,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.5025456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="47.330688" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.308 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.798192,10.0,46.7762304,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.798192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="46.7762304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.304 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |

<br>

## DC Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.197 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.3522608,10.0,47.764776,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.3522608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="47.764776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.311 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.167 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="27.035543999999998,10.0,55.2124272,10.0" style="stroke:green;stroke-width:2" /><circle cx="27.035543999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="55.2124272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.363 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |

<br>

## DC Specification (Monte Carlo, PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.195 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.034064,10.0,46.0186464,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.034064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="46.0186464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.299 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.2 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.781495999999997,10.0,48.2197152,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.781495999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="48.2197152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.314 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |

<br>

# PERFORMANCE CHARACTERISTICS

## DC Performance<br>

| ![xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__906d63d15d9e4df2b46e34b20351f79c](xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__906d63d15d9e4df2b46e34b20351f79c.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__906d63d15d9e4df2b46e34b20351f79c](xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__906d63d15d9e4df2b46e34b20351f79c.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c](xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c](xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepv(x1.vs)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c](xyplot_temp-sweepv(x1.vs)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepv(x1.vp)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c](xyplot_temp-sweepv(x1.vp)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(_b.x1.xrsu.xsky130_fd_pr__res_xhigh_po_0p69.brend_i_)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c](xyplot_temp-sweepi(_b.x1.xrsu.xsky130_fd_pr__res_xhigh_po_0p69.brend_i_)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__906d63d15d9e4df2b46e34b20351f79c.png "") |
| :-- |
|  |
<br>

| ![occtplot_temp-sweep_('tt',_-2)__906d63d15d9e4df2b46e34b20351f79c](occtplot_temp-sweep_('tt',_-2)__906d63d15d9e4df2b46e34b20351f79c.png "") |
| :-- |
|  |
<br>

## DC Performance (Monte Carlo)<br>

| ![histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f74cff190629448d28eb1d4b1cdcd620](histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f74cff190629448d28eb1d4b1cdcd620.png "") |
| :-- |
|  |
<br>

| ![histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f74cff190629448d28eb1d4b1cdcd620](histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f74cff190629448d28eb1d4b1cdcd620.png "") |
| :-- |
|  |
<br>

## AC Noise<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4423b8805896b25202139a69247a66c2](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4423b8805896b25202139a69247a66c2.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4bb6032dbf720fbc2c0e904e0f8c4c0d](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4bb6032dbf720fbc2c0e904e0f8c4c0d.png "") |
| :-- |
|  |
<br>

## DC Performance (PEX)<br>

| ![xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__19012df5f9ad54199f1422249c8bc634](xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__19012df5f9ad54199f1422249c8bc634.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__19012df5f9ad54199f1422249c8bc634](xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__19012df5f9ad54199f1422249c8bc634.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__19012df5f9ad54199f1422249c8bc634](xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__19012df5f9ad54199f1422249c8bc634.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__19012df5f9ad54199f1422249c8bc634](xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__19012df5f9ad54199f1422249c8bc634.png "") |
| :-- |
|  |
<br>
