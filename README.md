# DayZ


### Get-DayZServer
Queries an API for DayZ server info.

Has a switch that gives stripped down data. Accessable via -StrippedDownData


### DayZSound
Uses the https://github.com/frgnca/AudioDeviceCmdlets module to quickly switch between sound sources causing wind sounds to bug out and no longer play.
Follow the instructions to install from AudioDeviceCmdlets module.
You may have to tweak the sound device it switches between by using "Get-AudioDevice -list" and updating the indexes in the function accordingly
