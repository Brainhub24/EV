## Soon...
> [!NOTE]
> This is a useful powershell program that can manage your windows energy settings.
```
  _____ _                        _  __     ___       _ _             _
 | ____| |_ ___ _ __ _ __   __ _| | \ \   / (_) __ _(_) | __ _ _ __ | |_
 |  _| | __/ _ \ '__| '_ \ / _` | |  \ \ / /| |/ _` | | |/ _` | '_ \| __|
 | |___| ||  __/ |  | | | | (_| | |   \ V / | | (_| | | | (_| | | | | |_
 |_____|\__\___|_|  |_| |_|\__,_|_|    \_/  |_|\__, |_|_|\__,_|_| |_|\__|
                                               |___/
Power configurations to keep display and system active.
Elapsed Time: 01:36:05

Script stopped...
```
```
PS C:\Users\lab\Documents\GitHub\Worker_Control> .\DEV-TEST_Eternal_Vigilant.ps1 -r
Power settings reset with custom values.
Monitor Timeout AC: 15
Standby Timeout AC: 30
Monitor Timeout DC: 10
Standby Timeout DC: 20
```
```
Usage: .\Eternal_Vigilant.ps1 [-t time] [-r] [-s] [-e] [-h] [-v]
Flags:
  -t, --time      Hold display active for a specific time and then close
  -r, --reset     Reset power settings with custom values
  -s, --separate  Start in a separate PowerShell window
  -e, --batteryEnergy  Open energy and battery settings
  -h, --help      Display help information
  -v, --version   Display version information and changelog
```
