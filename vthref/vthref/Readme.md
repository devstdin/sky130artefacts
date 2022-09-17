17.09.2022, 20:08:27

# Vth Current Reference

10 uA current reference with source- and sink-port.

![vthref](resources/vthref.png "vthref")

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
| Output Current Curvature (Source) | 0.0 / 0.166 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="26.8474656,10.0,53.6857536,10.0" style="stroke:green;stroke-width:2" /><circle cx="26.8474656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.6857536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.352 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |

<br>

## DC Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.191 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.5239152,10.0,47.3101824,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.5239152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="47.3101824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.308 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.194 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.8981712,10.0,47.3664432,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.8981712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="47.3664432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.308 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |

<br>

## DC Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.195 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.0297296,10.0,47.418787200000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.0297296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="47.418787200000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.308 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.164 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="26.686214399999997,10.0,54.868555199999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="26.686214399999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="54.868555199999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.36 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |

<br>

## DC Specification (Monte Carlo, PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.819777600000002,10.0,45.772464,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.819777600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="45.772464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.297 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.196 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.170936,10.0,47.9622432,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.170936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="47.9622432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.312 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |

<br>

# PERFORMANCE CHARACTERISTICS

## DC Performance<br>

| ![xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepv(x1.vs)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepv(x1.vs)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepv(x1.vp)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepv(x1.vp)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(_b.x1.xrsu.xsky130_fd_pr__res_xhigh_po_0p69.brend_i_)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(_b.x1.xrsu.xsky130_fd_pr__res_xhigh_po_0p69.brend_i_)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![occtplot_temp-sweep_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9](occtplot_temp-sweep_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

## DC Performance (Monte Carlo)<br>

| ![histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ac80e060dd6c1296effc32574138f0ba](histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ac80e060dd6c1296effc32574138f0ba.png "") |
| :-- |
|  |
<br>

| ![histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ac80e060dd6c1296effc32574138f0ba](histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__ac80e060dd6c1296effc32574138f0ba.png "") |
| :-- |
|  |
<br>

## AC Noise<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__07d296c7c9ff73db4dc3ee4d86457f8c](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__07d296c7c9ff73db4dc3ee4d86457f8c.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c0c96b36b0d28d09473c62b512f759e6](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c0c96b36b0d28d09473c62b512f759e6.png "") |
| :-- |
|  |
<br>

## DC Performance (PEX)<br>

| ![xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__b4be906a43536e413e158af68407b680](xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__b4be906a43536e413e158af68407b680.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__b4be906a43536e413e158af68407b680](xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__b4be906a43536e413e158af68407b680.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__b4be906a43536e413e158af68407b680](xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__b4be906a43536e413e158af68407b680.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__b4be906a43536e413e158af68407b680](xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__b4be906a43536e413e158af68407b680.png "") |
| :-- |
|  |
<br>
