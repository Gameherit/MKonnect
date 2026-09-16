# MKonnect v2.0 is out !
[![MKonnect v2.0 - Official Trailer](https://github.com/user-attachments/assets/93c20d90-c246-4c26-bfd1-75bff430cb9e)](https://youtu.be/4Qju5RLwp6Q)


<img width="256" height="256" alt="logo" src="https://github.com/user-attachments/assets/c94a4e39-0706-4f24-8c1a-25cfc7fc58e6" />


# MKonnect
Account synchronization tool for WiiCompiled
## HOW TO USE
> Launch Dolphin, then go to File > Open user folder
> Then navigate to ./Load/Riivolution/WheelWizard/riivolution/save/RetroWFC/RMCP
> Once you are in /RMCP, you will see a rksys.dat, copy the file to the root of mkonnect.exe then execute it.

## COMMANDS

**List licenses:**
  
    mkonnect.exe licenses rksys.dat

**Inspect a license:**
  
    mkonnect.exe inspect rksys.dat --license 1

**Export:**
  
    mkonnect.exe export rksys.dat profile.json --license 1

**Import:**
  
    mkonnect.exe import rksys.dat profile.json --license 1

**Clone:**
  
    mkonnect.exe clone source.dat target.dat --source-license 1 --target-license 1

## How to use the same profile on multiple devices ?

1. Open WheelWizard on the source device
2. Export rksys.dat using mkonnect.exe export
3. Take the output JSON file
4. Download mkonnect.exe on the target device
5. Use mkconnect.exe import with the JSON you got from the source device
6. Finally, put the output rksys.dat back into ./Load/Riivolution/WheelWizard/riivolution/save/RetroWFC/RMCP
7. Replace the existing file

# WARNING, THIS WILL ERASE ALL THE EXISTING MARIO KART WII DATA FROM THE TARGET DEVICE

## ADDITIONNAL INFORMATIONS

In next versions, the process will be fully automated and synchronized on your Google Account. Your full data and progression will also be fully synchronized.
Updates are coming soon !
