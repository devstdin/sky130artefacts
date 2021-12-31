31.12.2021, 18:04:17

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
| Output Current Curvature (Sink) | 0.0 / 0.191 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.509183999999998,10.0,47.270208,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.509183999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="47.270208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.307 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.7766208,10.0,46.9751376,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.7766208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="46.9751376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.305 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |

<br>

# PERFORMANCE CHARACTERISTICS

## DC Performance<br>

| ![xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__8bde3970a962e2580e028ad19849a3af](xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__8bde3970a962e2580e028ad19849a3af.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__8bde3970a962e2580e028ad19849a3af](xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__8bde3970a962e2580e028ad19849a3af.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af](xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af](xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepv(x1.vs)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af](xyplot_temp-sweepv(x1.vs)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepv(x1.vp)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af](xyplot_temp-sweepv(x1.vp)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(_b.x1.xrsu.xsky130_fd_pr__res_xhigh_po_0p69.brend_i_)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af](xyplot_temp-sweepi(_b.x1.xrsu.xsky130_fd_pr__res_xhigh_po_0p69.brend_i_)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__8bde3970a962e2580e028ad19849a3af.png "") |
| :-- |
|  |
<br>

| ![occtplot_temp-sweep_('tt',_-2)__8bde3970a962e2580e028ad19849a3af](occtplot_temp-sweep_('tt',_-2)__8bde3970a962e2580e028ad19849a3af.png "") |
| :-- |
|  |
<br>

## DC Performance (Monte Carlo)<br>

| ![histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bf8d5960147c361c103b5feb760fa26f](histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bf8d5960147c361c103b5feb760fa26f.png "") |
| :-- |
|  |
<br>

| ![histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bf8d5960147c361c103b5feb760fa26f](histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__bf8d5960147c361c103b5feb760fa26f.png "") |
| :-- |
|  |
<br>

## AC Noise<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__125d9a1e8cbe2421d7e4a60e48fa607b](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__125d9a1e8cbe2421d7e4a60e48fa607b.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__12afb12094ce8b829618fc3614404747](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__12afb12094ce8b829618fc3614404747.png "") |
| :-- |
|  |
<br>
