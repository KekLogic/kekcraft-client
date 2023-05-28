# KekCraft Modded Minecraft Client

## How to run
1. Download and install [Java 8](https://www.java.com/en/download/)
2. Download and install [Prism Launcher](https://prismlauncher.org/download/)
3. Log into your Microsoft/Mojang account
4. Navigate to ~/AppData/Roaming/PrismLauncher/instances and clone this repo there
4. For Prism Launcher to recognize the modpack, create a `instance.cfg` file in the root directory with the following contents:
```
InstanceType=OneSix
JoinServerOnLaunch=false
LogPrePostOutput=true
MCLaunchMethod=LauncherPart
ManagedPack=false
ManagedPackID=
ManagedPackName=
ManagedPackType=
ManagedPackVersionID=
ManagedPackVersionName=
OverrideCommands=false
OverrideConsole=false
OverrideGameTime=false
OverrideJavaArgs=false
OverrideJavaLocation=false
OverrideMCLaunchMethod=false
OverrideMemory=false
OverrideMiscellaneous=false
OverrideNativeWorkarounds=false
OverridePerformance=false
OverrideWindow=false
iconKey=technic_453902
name=KekCraft 1.7.10
notes=
```
5. Restart PrismLauncher for the modpack to appear in the list
6. Launch Minecraft