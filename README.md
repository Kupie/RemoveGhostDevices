# RemoveGhostDevices
Removes all past/hidden/ghost devices in Windows via powershell

I originally found this script in wayback machine, full credits to the person here:

https://web.archive.org/web/20210624041338/https://theorypc.ca/2017/06/28/remove-ghost-devices-natively-with-powershell/

Sadly the original site no longer loads for me, but this is the best script I've found that doesn't rely on any external tools/executables! Huge shoutouts to the original author. I originally used this because over time my Windows 10 became bloated with so many hidden devices in device manager, including some from old bluetooth dongles that wouldn't let me even remove the old Switch Pro controllers from my bluetooth settings and pair them with the new dongle I got.


  
Example usage:


. "removeGhosts.ps1" -listDevicesOnly

. "removeGhosts.ps1" -FilterByFriendlyName @("Citrix","Intel")
