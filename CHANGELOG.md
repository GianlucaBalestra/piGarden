## 0.3.1 - 13/05/2017
Add experimental support for monostable solenoid valve:
- define in your config file the variable EV_MONOSTABLE and assign value 1
- if the solenoid valves close instead of opening and vice versa, reverse the values of the RELE_GPIO_CLOSE and RELE_GPIO_OPEN variables in your configuration file

## 0.3.0 - 07/05/2017
Add command "open_in" for scheduling on the fly the opens/close a solenoid
Add command "del_cron_open_in" for delete scheduling the fly the opens/close a solenoid
Add api in socket server for command open_in and delete_cron_open_in
Fix minor bug on command "open"
Changed the path of some temporary files to prevent sd card faults

## 0.2.2 - 25/04/2017
Fix bug: if it's reining, the solenoid valves were also closed even if they were pushed open in "force" mode

## 0.2.1 - 22/04/2017
Add installation instructions in README.md file  

## 0.2 (Easter egg) - 17/04/2017
Implementation of socket server for communicate with piGardenWeb  
Implementation of messages (error, warning, success) passed to piGardenWeb  
Added many information in json status to be passed to piGardenWeb  
Added management cron for scheduling open and closed solenoid, for initialize control unit, for rain control  

## 0.1.1 - 24/12/2015 - BugFix
Fix the problem for 'av_status' parameter

## 0.1 - 18/12/2015 - First release
First release to piGarden 

