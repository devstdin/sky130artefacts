24.11.2022, 23:44:30

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
| Open-Loop Gain | 90 / 96.281 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.22550399999996,10.0,51.863864000000014,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.22550399999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.863864000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.509 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 93.621 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="99.82778880000001,10.0,122.96726399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="99.82778880000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.96726399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 101.655 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 56.196 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.84964329411764,10.0,127.5693345882353,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.84964329411764" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.5693345882353" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 98.531 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.423 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.6928610909090915,10.0,10.128312727272728,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.6928610909090915" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.128312727272728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.59 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

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
| CMRR at 10Hz | 50 / 61.464 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.5076272,10.0,73.5616992,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.5076272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="73.5616992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 99.001 / 150 | dB | 2500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 59.861 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,142.18006772727034,17,142.18006772727034,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.59003386363517,10.0,72.59003386363517,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.91242726874933,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="65.91242726874933" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 91.905 / 90 | dB | 2500/98.0%/2.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 62.67 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="39.271983999999996,10.0,94.6244,10.0" style="stroke:green;stroke-width:2" /><circle cx="39.271983999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.6244" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 97.265 / 130 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 50.91 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="68.45808,10.0,86.55402514285714,10.0" style="stroke:green;stroke-width:2" /><circle cx="68.45808" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="86.55402514285714" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 55.308 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.373 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.595968,10.0,81.5560937142857,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.595968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.5560937142857" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 88.187 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.773 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.824160000000006,10.0,68.941536,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.824160000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.941536" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.869 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "CMRR at 10MHz":<br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota/batch_3/hh_mm/ac_cmrr_psrr.csv Index:49 <br>
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
| Negative Output Bound | -2.5 / -2.265 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.63967999999996,10.0,74.87615999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.63967999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.87615999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.25 / -2 | V | 2500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2 / 2.093 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.81798400000001,10.0,40.73232000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.81798400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="40.73232000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.131 / 2.5 | V | 2500/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.905 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.694916571428557,10.0,59.34514285714287,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.694916571428557" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.34514285714287" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.074 / 1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.8 / 0.894 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.275078857142837,10.0,61.55471999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.275078857142837" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.55471999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.085 / 1.5 | V | 2500/100.0%/0.0%/0.0% | Input transistor sat. |

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
| Input Offset | -10.0 / -1.972 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.798719999999996,10.0,104.6764416,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.798719999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.6764416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.122 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 15.501 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="42.604464,10.0,79.061448,10.0" style="stroke:green;stroke-width:2" /><circle cx="42.604464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.061448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 20.564 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -22.22 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.018879999999996,10.0,98.74776,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.018879999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="98.74776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -16.702 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

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
| THD | 0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.2797888,10.0,71.185344,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.2797888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.185344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.142 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.36 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.79127999999997,10.0,51.31831999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.79127999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.31831999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.433 / 110 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 86.895 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.45656319999999,10.0,97.02837120000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.45656319999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="97.02837120000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 92.649 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 46.919 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.132975058823526,10.0,61.603256470588235,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.132975058823526" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.603256470588235" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 59.592 / 110.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.416 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.596925090909091,10.0,11.153290181818182,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.596925090909091" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.153290181818182" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.523 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 96.25 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.00259200000001,10.0,51.93593599999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.00259200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="51.93593599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.519 / 110 | dB | 2500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 85.417 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.2004416,10.0,102.25358399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.2004416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="102.25358399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.463 / 110 | deg | 2500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 43.504 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="34.348630588235295,10.0,72.0576734117647,10.0" style="stroke:green;stroke-width:2" /><circle cx="34.348630588235295" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.0576734117647" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.763 / 110.0 | MHz | 2500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.4 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.360689454545454,10.0,9.548568727272727,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.360689454545454" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.548568727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.55 / 10.0 | kHz | 2500/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 91.297 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.468025600000004,10.0,65.1510176,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.468025600000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.1510176" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.772 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 55.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.603895272727264,10.0,79.14992290909093,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.603895272727264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.14992290909093" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 64.085 / 90 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 94.54 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.26388800000001,10.0,93.282,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.26388800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.282" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 96.426 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 49.406 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.26912457142856,10.0,70.1088137142857,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.26912457142856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.1088137142857" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.311 / 70 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 40 / 84.474 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.0532,10.0,83.67798,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.0532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.67798" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.821 / 120 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.486 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.06097280000001,10.0,61.43539200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.06097280000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.43539200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.087 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 66.46 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="26.702356799999997,10.0,108.261984,10.0" style="stroke:green;stroke-width:2" /><circle cx="26.702356799999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.261984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 123.099 / 150 | dB | 2450/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 53.265 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="50.82096,10.0,96.26725527272728,10.0" style="stroke:green;stroke-width:2" /><circle cx="50.82096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.26725527272728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 70.623 / 90 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 67.086 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,136.11271133953912,17,136.11271133953912,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.55635566976956,10.0,69.55635566976956,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.060699396370836,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="43.060699396370836" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 137.361 / 130 | dB | 2500/98.0%/2.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 48.759 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.608169142857136,10.0,74.63193599999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.608169142857136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.63193599999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 52.411 / 70 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 82.653 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.17133028571429,10.0,79.60822628571428,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.17133028571429" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.60822628571428" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 87.24 / 120 | dB | 2500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.182 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.1461248,10.0,64.277376,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.1461248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="64.277376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.383 / 20 | dB | 2500/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10Hz":<br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:20 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:21 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:22 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:23 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:24 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:25 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:26 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:27 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:28 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:29 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:30 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:31 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:32 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:33 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:34 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:35 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:36 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:37 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:38 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:39 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:40 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:41 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:42 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:43 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:44 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:45 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:46 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:47 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:48 <br>
> **FAIL:** group:hh_mm file:work/sim/bmbgota/bmbgota_tb.2_bmbgota_ext/batch_8/hh_mm/ac_cmrr_psrr.csv Index:49 <br>
</details><br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.2656824,10.0,78.41793936,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.2656824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.41793936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.427 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="34.87296,10.0,59.113704,10.0" style="stroke:green;stroke-width:2" /><circle cx="34.87296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.113704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.794 / 30.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -19.692 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.22048,10.0,104.4768,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.22048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.4768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -15.906 / -10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -2.683 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.684200000000004,10.0,101.7987384,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.684200000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.7987384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.722 / 10.0 | mV | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 13.679 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.490024,10.0,67.43776799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.490024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.43776799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.95 / 30.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -30.0 / -20.317 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.71831999999999,10.0,111.90576,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.71831999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.90576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -14.874 / -10.0 | MV/s | 2500/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 0.943 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.58140752,10.0,19.859806399999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.58140752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.859806399999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.032 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.046 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.61294944,10.0,12.20183312,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.61294944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.20183312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.05 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.122 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.647983999999994,10.0,78.76660799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.647983999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.76660799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.158 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.112 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.534927999999994,10.0,89.74252800000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.534927999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.74252800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.181 / 0.3 | % | 2500/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__90bcc125b5a8269ffd2b97e5c5e9c936.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__db308fabc59281ea0bf97f02c323ef89.png "") |
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

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c96c03573014e4674ecc6b518376c01b.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__7268da64711c9c5b18b48d467dd95411](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__7268da64711c9c5b18b48d467dd95411.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__7268da64711c9c5b18b48d467dd95411](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__7268da64711c9c5b18b48d467dd95411.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__d7804ec337891d79b9e125cf65f36757](histplot_pos_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__d7804ec337891d79b9e125cf65f36757.png "") |
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

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__4bc2051574084a6ad72cf8b38ff306eb.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7b5d2e34c0e088201bd8b54a9187c901.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b24c2ee304e43216830b82402f8d8537](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__b24c2ee304e43216830b82402f8d8537.png "") |
| :-- |
|  |
<br>
