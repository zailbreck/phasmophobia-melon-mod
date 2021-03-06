# Phasmophobia MelonLoader Mod - Only works with an bypass

Just an private project to learn some basic programming of Unity Engine Mods with the help of MelonLoader.  
Place the generated DLL into the MelonLoader Mods folder.   


**Features**  
\- Simple Box ESP  
\- Bone/OuijaBoard/FuseBox/EMF ESP  
\- Player ESP  
\- Fullbright mode  
\- Basic ghost informations (Ghost Name/Type/State, responds to)  
\- Revealed evidence  
\- Own sanity  
\- Show active and completed missions  
\- Console window for logging (MelonLoader)  
\- Ghost actions: Hunt/Idle/Appear/Disappear/Interact  
\- Add/Remove XP/Money  
\- Close/Open all exit or room doors  
\- Lock/Unlock all exit or room doors  
\- Change player name  
\- Troll hotkey toggle  
\- Random light use  
\- All lights On/Off  
\- Blinking lights  


**Hotkeys**  
Insert | Delete | Right Ctrl: Open GUI  
↑ key: Toggle ESP  
← key: Toggle basic informations  
↓ key: Toggle fullbright  
H key: Force ghost to hunt  
I key: Force ghost to interact with Door/Book/Objects  
O key: Force ghost to appear  
P key: Force ghost to stop hunting / appearing  
L key: Lock all exit doors  
U key: Unlock all exit doors  


**Screenshots**  
\- [Mod v.7.2](Images/v7.2.png)  
\- [Mod v.7.0](Images/v7.0_HAC-Edition.jpg)  
\- [Mod v.6.1](Images/v6.1.png)  
\- [Mod v.5](Images/v5.png)  
\- [Mod v.4.3](Images/v4.3.png)  
\- [Mod v.4.2](Images/v4.2.png)  
\- [Mod v.4](Images/v4.png)  
\- [Mod v.3](Images/v3.png)  
\- [Mod v.2](Images/v2.png)  
\- [Mod v.1](Images/v1.png)  


# How to build
1. [Install MelonLoader](https://melonwiki.xyz/#/README)
2. Start the game without Mod, only with MelonLoader. ML will download stuff do handle the IL2CPP from Phasmophobia
3. Modify `PhasmoMelonMod.csproj` and edit all  
```<Reference Include="Assembly-CSharp"><HintPath>**.dll</HintPath></Reference>```  
to link to your Steams Phasmophobia directory
4. Compile (Release) and move the `obj\Release\PhasmoMelonMod.dll` to the Mod folder inside your Phasmophobia directory

This mod only works with an MelonLoader Bypass or the game will crash because of MelonLoader detection.



# Credits
**Fullbright:** `ShieldSupporter` for sharing the code from `Plagues`  
**2D Box ESP idea:** `EBro912`  
**Others:** `HYPExMon5ter`, `Martin951`, `tecnocat`


# License
**GNU General Public License 3**
