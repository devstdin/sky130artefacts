25.04.2023, 15:13:30

# Beta-Multiplier Bandgap OTA

OTA for Beta-Multiplier Bandgap.

![bmbgota](resources/bmbgota.png "bmbgota")

<br>

[🔗 Schematics](bmbgota_sch.pdf)<br>

# LVS

[🔗 LVS-report](bmbgota_bmbgota_netgen_comp.out)<br>

# SPECIFICATIONS

## AC Open-Loop Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.36 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.79120799999995,10.0,51.318248000000054,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.79120799999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.318248000000054" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.433 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 95.784 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="106.0578912,10.0,115.89335039999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="106.0578912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="115.89335039999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 99.199 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 62.415 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.38497129411763,10.0,107.37111529411764,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.38497129411763" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.37111529411764" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 86.608 / 110.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.439 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.928058181818181,10.0,11.683957818181819,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.928058181818181" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.683957818181819" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.56 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.282 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.232416,10.0,51.981872000000024,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.232416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.981872000000024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.525 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 93.224 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="98.68486080000001,10.0,126.714432,10.0" style="stroke:green;stroke-width:2" /><circle cx="98.68486080000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.714432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.956 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 57.284 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.69277552941176,10.0,129.73731388235294,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.69277552941176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="129.73731388235294" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 99.81 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.414 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.567776,10.0,10.07734109090909,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.567776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.07734109090909" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.587 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.297 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.4679536,10.0,65.15096,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.4679536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.15096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.772 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 67.323 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.6283810909091,10.0,106.96792145454545,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.6283810909091" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.96792145454545" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.71 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.54 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.263824,10.0,93.281952,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.263824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.281952" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.426 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 52.774 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.12813714285714,10.0,77.244384,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.12813714285714" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.244384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 53.046 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 40 / 84.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.053398,10.0,83.677854,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.053398" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.677854" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.821 / 120 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.985 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.8586112,10.0,67.851264,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.8586112" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.851264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.755 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 63.006 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.728438399999998,10.0,95.65161599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.728438399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.65161599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 114.341 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 60.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,134.5882603334167,17,134.5882603334167,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.79413016670836,10.0,68.79413016670836,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.27524675291013,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="63.27524675291013" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 95.188 / 90 | dB | 2500/98.0%/2.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 65.917 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.467712000000006,10.0,128.86223999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.467712000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.86223999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 118.664 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 51.04 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.99396571428571,10.0,85.56696685714284,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.99396571428571" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="85.56696685714284" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 55.068 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 83.061 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.01047999999999,10.0,84.03143314285714,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.01047999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.03143314285714" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 89.39 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.688 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.00741119999999,10.0,70.24896,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.00741119999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.24896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.005 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "CMRR at 10MHz":<br>
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
</details><br>


## Output Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -2.5 / -2.263 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.29056,10.0,74.09567999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.29056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.09567999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.253 / -2 | V | 5/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.086911999999984,10.0,38.59910399999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.086911999999984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.59910399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.124 / 2.5 | V | 5/100.0%/0.0%/0.0% |  |

<br>


## Output Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -2.5 / -2.265 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.73759999999996,10.0,74.58527999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.73759999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.58527999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.251 / -2 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.95363200000004,10.0,39.118944,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.95363200000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="39.118944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.125 / 2.5 | V | 2500/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.905 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.694916571428557,10.0,59.34514285714287,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.694916571428557" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.34514285714287" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.074 / 1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.893 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.147515428571428,10.0,61.80445714285714,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.147515428571428" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.80445714285714" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.086 / 1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Slew-Rate/Offset Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.265902,10.0,78.41806176,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.265902" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.41806176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.989 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.121088,10.0,76.42286399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.121088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.42286399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.198 / 30.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -21.782 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.166,10.0,94.80792,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.166" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.80792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -17.249 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -2.773 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.032312000000005,10.0,124.37075999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.032312000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.37075999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 6.857 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.534 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.8448,10.0,79.372776,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.8448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.372776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.607 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -22.305 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.403999999999996,10.0,98.14872,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.403999999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="98.14872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -16.785 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 0.943 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.5813816,10.0,19.859777599999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.5813816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.859777599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.032 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.61293648,10.0,12.20181872,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.61293648" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.20181872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.05 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.1 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.143471999999996,10.0,65.18803199999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.143471999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.18803199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.13 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.094 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.892316799999996,10.0,72.10128,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.892316799999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.10128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.144 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.36 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.79127999999997,10.0,51.31831999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.79127999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.31831999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.433 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 89.8 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.82270399999999,10.0,104.76272640000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.82270399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.76272640000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 95.334 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 48.441 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.71204894117647,10.0,65.62233035294118,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.71204894117647" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.62233035294118" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.965 / 110.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.416 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.592082909090909,10.0,11.145637818181818,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.592082909090909" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.145637818181818" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.523 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.273 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.16603200000001,10.0,51.92960000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.16603200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.92960000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.518 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 88.285 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="84.459792,10.0,110.60382720000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="84.459792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.60382720000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 97.362 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 44.481 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.003326117647056,10.0,77.218464,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.003326117647056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.218464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 68.81 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.398 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.339746909090909,10.0,9.445016727272728,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.339746909090909" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.445016727272728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.543 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.297 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.468025600000004,10.0,65.1510176,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.468025600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.1510176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.772 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 54.317 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.57586327272727,10.0,71.9142109090909,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.57586327272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.9142109090909" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.321 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.54 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.26388800000001,10.0,93.282,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.26388800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.282" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.426 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 52.898 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.63728,10.0,87.30986057142856,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.63728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.30986057142856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 55.492 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 40 / 84.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.0532,10.0,83.67798,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.0532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.67798" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.821 / 120 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.495 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.15001279999999,10.0,61.57824,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.15001279999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.57824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.102 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.907 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.906151999999995,10.0,98.87015999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.906151999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="98.87015999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 116.576 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 51.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.39611345454545,10.0,91.50606545454546,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.39611345454545" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.50606545454546" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 68.804 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 64.923 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,127.00786531367962,17,127.00786531367962,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.00393265683981,10.0,65.00393265683981,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="37.34028561996757,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="37.34028561996757" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 144.51 / 130 | dB | 2500/98.0%/2.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 51.588 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.24966399999998,10.0,100.52169599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.24966399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.52169599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 58.703 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.536 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.93068571428569,10.0,80.398272,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.93068571428569" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.398272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.624 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.148 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.817708800000005,10.0,63.371711999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.817708800000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.371711999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.289 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10Hz":<br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:ll_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_6/ll_mm/ac_cmrr_psrr.csv Index:49 <br>
</details><br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.26579904,10.0,78.41811360000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.26579904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.41811360000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.685 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="36.734159999999996,10.0,61.808519999999994,10.0" style="stroke:green;stroke-width:2" /><circle cx="36.734159999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.808519999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.168 / 30.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -19.87 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.93599999999999,10.0,103.64663999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="75.93599999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.64663999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -16.021 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -2.802 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.822504,10.0,106.38273360000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.822504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.38273360000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.359 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.259 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="33.665088,10.0,66.59039999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="33.665088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.59039999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.832 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -20.603 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.65912,10.0,105.11543999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.65912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.11543999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -15.817 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 0.943 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.58140464,10.0,19.859806399999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.58140464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.859806399999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.032 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.61294656,10.0,12.201831680000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.61294656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.201831680000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.05 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.117 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.955184,10.0,75.040416,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.955184" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.040416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.15 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.106 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.008160000000004,10.0,83.667264,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.008160000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.667264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.168 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__e2583834dc2babc449c3ee617250153a.png "") |
| :-- |
|  |
<br>

## CMRR/PSRR Performance<br>

| ![xyplot_frequencycmrrgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3](xyplot_frequencycmrrgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3](xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencypsrr_ngroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3](xyplot_frequencypsrr_ngroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__071c8bf9ae95dbcb9ba7cf960ae389c3.png "") |
| :-- |
|  |
<br>

## CMRR/PSRR Performance (Monte Carlo)<br>

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f7f1f530af17b77be8feec7459e3fbf0.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__876ab014c98c6dbdee6eb52835fbccf8](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__876ab014c98c6dbdee6eb52835fbccf8.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__876ab014c98c6dbdee6eb52835fbccf8](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__876ab014c98c6dbdee6eb52835fbccf8.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__aed52ce6bc208f67eab947c3b90b8203](histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__aed52ce6bc208f67eab947c3b90b8203.png "") |
| :-- |
|  |
<br>

## Slew-Rate/Offset Performance<br>

| ![xyplot_timev(opout_10f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__257c10c66e943eee42eeaaf7527daa22](xyplot_timev(opout_10f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__257c10c66e943eee42eeaaf7527daa22.png "") |
| :-- |
|  |
<br>

| ![xyplot_timev(opout_500f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__257c10c66e943eee42eeaaf7527daa22](xyplot_timev(opout_500f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__257c10c66e943eee42eeaaf7527daa22.png "") |
| :-- |
|  |
<br>

## Slew-Rate/Offset Performance (Monte Carlo)<br>

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__819a259eadb283f6d100d75659b19240.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6d55a1dcf0deaaffc578b64172ae3518](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6d55a1dcf0deaaffc578b64172ae3518.png "") |
| :-- |
|  |
<br>
