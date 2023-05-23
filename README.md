# BadOS-Docs
**THIS IS FOR A FLIPPER ZERO RUNNING BadKB or BadUSB**
-------------------------------------------------------------------------------------
# Usage 

A very simple usage for BadOS is:
Back To The Homescreen
```
DELAY 2000
GUI h
```
> The reason there is a Delay before anything is due to the Bluetooth connecting mode. Connecting Via Bluetooth works, yes. But, If I were to run it directly once Bluetooth is connected. The first lines of code **DO NOT** run correctly. So, by adding a DELAY before anything in the code ensures it will work with via BadOS and BadUSB (If using a USB is more suitable for you).

A Homescreen Usage for swiping on your lockscreen is
```
GUI LEFTARROW
```