
# Tranisent Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Rising Output Delay | 50.0 / 94.4865 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.53653985882353,10.0,136.85143905882353,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.53653985882353" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="136.85143905882353" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 840.0953 / 900.0 | ns | 225/100.0%/0.0%/0.0% | Positive threshold cross to output high delay |
| Max. supply current | 300.0 / 370.0463 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,107.77499932696614,17,107.77499932696614,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.38749966348307,10.0,55.38749966348307,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="27.463670117854907,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="27.463670117854907" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 712.3121 / 600.0 | uA | 225/71.5556%/28.4444%/0.0% | Maximum supply current for output switch |
| Mean supply current | 50.0 / 62.1762 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.53367039999999,10.0,111.52113600000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="20.53367039999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.52113600000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 125.3619 / 150.0 | uA | 225/100.0%/0.0%/0.0% | Mean supply current |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Max. supply current":<br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:0 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:1 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:2 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:3 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:4 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:5 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:6 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:7 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:8 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:9 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:10 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:11 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:12 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:13 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:14 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:17 vin_p_diff:0.001 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:18 vin_p_diff:0.01 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:19 vin_p_diff:0.005 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:20 vin_p_diff:0.001 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:21 vin_p_diff:0.01 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:22 vin_p_diff:0.005 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:23 vin_p_diff:0.001 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:24 vin_p_diff:0.01 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:25 vin_p_diff:0.005 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:ff file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ff/cmp_tran_speed_rising.csv Index:26 vin_p_diff:0.001 temp:20.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:0 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:1 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:2 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:3 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:4 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:5 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:6 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:7 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:8 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:9 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:10 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:11 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:hh file:work/sim/cmp/cmp_tb.1_cmp/batch_0/hh/cmp_tran_speed_rising.csv Index:14 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:0 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:1 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:2 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:3 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:4 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:5 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:6 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:7 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:8 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:9 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:10 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:11 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:tt file:work/sim/cmp/cmp_tb.1_cmp/batch_0/tt/cmp_tran_speed_rising.csv Index:14 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:0 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:1 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:2 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:3 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:4 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:5 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:6 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:7 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:8 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:9 vin_p_diff:0.01 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:10 vin_p_diff:0.005 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:11 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
> **FAIL:** group:ll file:work/sim/cmp/cmp_tb.1_cmp/batch_0/ll/cmp_tran_speed_rising.csv Index:14 vin_p_diff:0.001 temp:-40.0 v_sup:5.0 <br>
</details><br>

