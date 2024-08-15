15.08.2024, 22:00:59

# Vth Current Reference

10 uA current reference with source- and sink-port.

![vthref](resources/vthref.png "vthref")

<br>

[🔗 Schematics](vthref_sch.pdf)<br>

# LVS

[🔗 LVS-report](vthref_vthref_netgen_comp.out)<br>

# SPECIFICATIONS

## Transient Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Startup Time | 0.0 / 0.742 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.34172104,10.0,126.027192,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.34172104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.027192" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.087 / 20.0 | ms | 20/100.0%/0.0%/0.0% |  |

<br>


## DC Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.183 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.280950400000002,10.0,53.8264128,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.280950400000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.8264128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.353 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.181 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.0441424,10.0,56.808508800000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.0441424" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.808508800000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.374 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |

<br>


## DC Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.19 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.4288464,10.0,49.5043536,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.4288464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="49.5043536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.323 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.192 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.7064784,10.0,48.3583008,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.7064784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="48.3583008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.315 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |

<br>


## DC Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.194 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.936936000000003,10.0,48.430300800000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.936936000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="48.430300800000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.315 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.168 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="27.2274384,10.0,55.3129968,10.0" style="stroke:green;stroke-width:2" /><circle cx="27.2274384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="55.3129968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.363 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |

<br>


## DC Specification (Monte Carlo, PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,33.70793301064414,17,33.70793301064414,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.35396650532207,10.0,18.35396650532207,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.924349471631627,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="8.924349471631627" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 4.689 / 1.0 | uA | 500/99.8%/0.2%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.2 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,34.19534721396303,17,34.19534721396303,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.597673606981516,10.0,18.597673606981516,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.247158396325187,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="9.247158396325187" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 4.616 / 1.0 | uA | 500/99.8%/0.2%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Sink)":<br>
> **FAIL:** group:ff_mm file:work/sim/vthref/vthref_tb.4_dcext/batch_1/ff_mm/dc.csv Index:13 <br>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Source)":<br>
> **FAIL:** group:ff_mm file:work/sim/vthref/vthref_tb.4_dcext/batch_1/ff_mm/dc.csv Index:13 <br>
</details><br>


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

| ![xyplot_temp-sweepi(viin)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(viin)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
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

| ![histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23bafb5ab45771cf23411b544f38b83c](histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23bafb5ab45771cf23411b544f38b83c.png "") |
| :-- |
|  |
<br>

| ![histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23bafb5ab45771cf23411b544f38b83c](histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23bafb5ab45771cf23411b544f38b83c.png "") |
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
