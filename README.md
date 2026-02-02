## 🇺🇦 Ukraine Longitudinal Study
_WIP. This repo will be routinely updated to host the analytic pipeline for Ukraine Longitudinal Study (ULS) estimates of prevalence and models of direct war exposure as a driver of psychiatric morbidity among children, adolescents, and families across Ukraine._ 

Hosts proof-of-concept code for Bellingcat OSINT [Civilian Harm in Ukraine](https://ukraine.bellingcat.com/) (level-2: oblast) &rarr; Ukraine Longitudinal Survey (ULS; level 1: individual) 1:n merge. ULS data are secure and confidential.

`uls_scratchpad.py` derives `d_uls_lvl2.csv` indexed by oblast.<br>
`uls_scratchpad.do` merges `d_uls_lvl2.csv` to the ULS .dta file.
