
# AC Open-Loop Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.324 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.53107199999995,10.0,50.80841599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.53107199999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="50.80841599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.362 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 96.026 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="132.692664,10.0,145.526196,10.0" style="stroke:green;stroke-width:2" /><circle cx="132.692664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="145.526196" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 99.591 / 100 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 61.392 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,63.28957080859367,17,63.28957080859367,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="33.14478540429684,10.0,33.14478540429684,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.76335941527155,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="90.76335941527155" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 84.712 / 50.0 | MHz | 5/0.0%/100.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.438 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.922077090909092,10.0,11.669146181818181,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.922077090909092" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.669146181818181" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.559 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Unity-Gain Bandwidth":<br>
> **FAIL:** group:ff file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_0/ff/ac_ol.csv Index:0 <br>
> **FAIL:** group:hh file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_0/hh/ac_ol.csv Index:0 <br>
> **FAIL:** group:tt file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_0/tt/ac_ol.csv Index:0 <br>
> **FAIL:** group:ll file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_0/ll/ac_ol.csv Index:0 <br>
> **FAIL:** group:ss file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_0/ss/ac_ol.csv Index:0 <br>

# AC Open-Loop Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.238 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.91468000000003,10.0,51.36584000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.91468000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.36584000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.44 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 94.195 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,137.4967928585939,17,137.4967928585939,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.24839642929695,10.0,70.24839642929695,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="117.97643270607081,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="117.97643270607081" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 102.826 / 100 | deg | 2500/91.88%/8.12%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 55.164 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,54.54849532090013,17,54.54849532090013,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="28.774247660450065,10.0,28.774247660450065,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.19643499197778,10.0,147.00000000000003,10.0" style="stroke:red;stroke-width:2" /><circle cx="65.19643499197778" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.00000000000003" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 94.837 / 50.0 | MHz | 2500/0.0%/100.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.417 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.609368727272727,10.0,10.091256727272729,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.609368727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.091256727272729" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.588 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Phase Margin":<br>
> **FAIL:** group:ff_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ff_mm/ac_ol.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:1 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:11 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:24 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:28 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:30 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:38 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:41 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/hh_mm/ac_ol.csv Index:47 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/tt_mm/ac_ol.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/hh_mm/ac_ol.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/hh_mm/ac_ol.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/hh_mm/ac_ol.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/hh_mm/ac_ol.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/hh_mm/ac_ol.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/hh_mm/ac_ol.csv Index:37 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/hh_mm/ac_ol.csv Index:39 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_5/hh_mm/ac_ol.csv Index:48 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:26 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:28 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:30 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:37 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_9/hh_mm/ac_ol.csv Index:49 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/tt_mm/ac_ol.csv Index:19 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/tt_mm/ac_ol.csv Index:29 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/ss_mm/ac_ol.csv Index:4 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/ss_mm/ac_ol.csv Index:12 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/ff_mm/ac_ol.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:26 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:34 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:38 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:41 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:46 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_2/hh_mm/ac_ol.csv Index:47 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/tt_mm/ac_ol.csv Index:5 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/tt_mm/ac_ol.csv Index:37 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/tt_mm/ac_ol.csv Index:39 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/tt_mm/ac_ol.csv Index:45 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/tt_mm/ac_ol.csv Index:46 <br>
> **FAIL:** group:ff_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/ff_mm/ac_ol.csv Index:22 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:39 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:40 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:44 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:48 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_6/hh_mm/ac_ol.csv Index:49 <br>
> **FAIL:** group:ss_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_1/ss_mm/ac_ol.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_1/hh_mm/ac_ol.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_1/hh_mm/ac_ol.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_1/hh_mm/ac_ol.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_1/hh_mm/ac_ol.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_1/hh_mm/ac_ol.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_1/hh_mm/ac_ol.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_1/hh_mm/ac_ol.csv Index:18 <br>

> **FAIL:** Specification violation for parameter "Unity-Gain Bandwidth":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:1 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:2 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:3 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:4 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:5 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:6 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:7 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:8 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:9 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:10 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:11 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:12 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:13 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:14 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:15 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:16 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:17 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:18 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:19 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:20 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:21 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:22 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:23 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:24 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:25 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:26 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:27 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:28 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:29 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:30 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:31 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:32 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:33 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:34 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:35 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:36 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:37 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:38 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:39 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:40 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:41 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:42 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:43 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:44 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:45 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:46 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:47 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:48 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/tt_mm/ac_ol.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.1_bmbgota/batch_8/ll_mm/ac_ol.csv Index:49 <br>

# CMRR/PSRR Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.211 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="99.905248,10.0,103.196472,10.0" style="stroke:green;stroke-width:2" /><circle cx="99.905248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.196472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.749 / 110 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 50 / 67.334 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.40135599999999,10.0,91.82852399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="65.40135599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.82852399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.675 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.522 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.23544,10.0,93.206208,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.23544" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.206208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.379 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 40 / 52.711 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.01083200000002,10.0,67.50142399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.01083200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.50142399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 53.021 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 90 / 84.449 | <svg height="20" width="150"><polyline points="25.4834053900486,3,25.4834053900486,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="86.2417026950243,10.0,86.2417026950243,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,6.213545724838098,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="6.213545724838098" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 84.749 / 120 | dB | 5/0.0%/100.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.925 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.278531199999996,10.0,67.188864,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.278531199999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.188864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.686 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "PSRR- at 10Hz":<br>
> **FAIL:** group:ff file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_0/ff/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:hh file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_0/hh/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:tt file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_0/tt/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ll file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_0/ll/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ss file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_0/ss/ac_cmrr_psrr.csv Index:0 <br>

# CMRR/PSRR Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 61.92 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.607952000000004,10.0,137.66616,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.607952000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.66616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 106.111 / 110 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 50 / 60.63 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.26954799999999,10.0,144.985836,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.26954799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="144.985836" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 89.441 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 64.443 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.10924800000001,10.0,121.34143999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.10924800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.34143999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 113.963 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 40 / 51.015 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.870223999999986,10.0,81.221136,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.870223999999986" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.221136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 56.296 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 90 / 82.837 | <svg height="20" width="150"><polyline points="30.754190701788307,3,30.754190701788307,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.87709535089415,10.0,88.87709535089415,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,23.39400978886586,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="23.39400978886586" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 88.101 / 120 | dB | 2500/0.0%/100.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.8560224,10.0,69.51868799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.8560224" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.51868799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.929 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "PSRR- at 10Hz":<br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:tt_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/tt_mm/ac_cmrr_psrr.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_8/ll_mm/ac_cmrr_psrr.csv Index:49 <br>

# Output Range Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -2.5 / -2.267 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.04064,10.0,72.41951999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.04064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.41951999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.259 / -2 | V | 5/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.08633600000003,10.0,38.59852800000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.08633600000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.59852800000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.124 / 2.5 | V | 5/100.0%/0.0%/0.0% |  |

<br>

# Output Range Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -2.5 / -2.268 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.68639999999998,10.0,72.68160000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.68639999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.68160000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.258 / -2 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.096 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.537695999999954,10.0,40.31155200000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.537695999999954" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="40.31155200000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.13 / 2.5 | V | 2500/100.0%/0.0%/0.0% |  |

<br>

# Input Range Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.905 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.696582857142857,10.0,59.34555428571426,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.696582857142857" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.34555428571426" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.074 / 1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>

# Input Range Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.89 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.43738971428571,10.0,61.64893714285714,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.43738971428571" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.64893714285714" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.085 / 1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

<br>

# Slew-Rate/Offset Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.28975488,10.0,78.43071432,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.28975488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.43071432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.877 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,146.47573964732868,17,146.47573964732868,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.73786982366434,10.0,74.73786982366434,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.3181096274214,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="87.3181096274214" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 20.037 / 20.0 | MV/s | 5/80.0%/20.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -21.617 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.359759999999994,10.0,95.65896,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.359759999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.65896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -17.131 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Slew-Rate (Positive)":<br>
> **FAIL:** group:ll file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_0/ll/tran_slew.csv Index:0 <br>

# Slew-Rate/Offset Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -3.313 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.147552000000005,10.0,99.4811664,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.147552000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.4811664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.4 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.418 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,139.64326334478037,17,139.64326334478037,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.32163167239018,10.0,71.32163167239018,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.0323635773586,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="77.0323635773586" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 20.538 / 20.0 | MV/s | 2500/90.0%/10.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -22.34 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.149119999999996,10.0,97.78439999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.149119999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="97.78439999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -16.836 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>

> **FAIL:** Specification violation for parameter "Slew-Rate (Positive)":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_8/ll_mm/tran_slew.csv Index:49 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.5_bmbgota/batch_5/ll_mm/tran_slew.csv Index:49 <br>

# Noise Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 0.937 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.498163999999996,10.0,19.707627199999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.498163999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.707627199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.021 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.569180639999999,10.0,12.1278848,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.569180639999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.1278848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.049 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>

# THD Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.101 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.540576,10.0,65.67307199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.540576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.67307199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.131 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>

# THD Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.111376,10.0,72.020064,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.111376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.020064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.144 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>
