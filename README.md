# How to install Battle for Middle Earth II / Rise of The Witch King in 2025


## Prerequisites

### If you have a Mac (Intel or Apple Silicon / M-chip)

- A Windows licence (key)

### If you have a Windows machine

- Nothing else


## Installation steps

### Part 0 (Mac only!): Install Windows

#### On Apple Silicon

_Note: You can skip this part if you already have a Windows partition running, either in VMWare Fusion or Parallels Desktop. This guide uses VMWare Fusion because it's available for free (personal use only!)._

1. Create a free Broadcom user account [here](https://access.broadcom.com/).
2. Download VMWare Fusion Pro [here](https://support.broadcom.com/group/ecx/productdownloads?subfamily=VMware+Fusion)
3. Install VMWare Fusion Pro and start it up. Choose "Get Windows from Microsoft" and create a new virtual machine.
4. During the Windows setup process, enter your Windows licence key.
5. Once Windows is running, head to the VMWare Fusion menu bar (in macOS, not Windows) and click: Virtual Machine > Install VMWare Tools.
6. A "DVD" will appear to be mounted in your Windows virtual machine. Click on the popup and run the AutoRun executable. Follow the install steps.
7. Restart your virtual machine.
8. Now, right click the Windows desktop and choose Display Settings. You'll now be able to change the display setting to your actual screen resolution. Change the Scaling as needed.
9. Bring up the macOS toolbar above the Windows virtual machine and click on the Settings ("wrench") icon. Choose "Display". Select "Resize the virtual machine and the window" for _Single Window_ and "Center the virtual machine in the screen" for _Full Screen_ for the best experience.
    - **Note:** If you have trouble gettng your mouse cursor to exit the Virtual Machine, just press Control+Command.
10. At this point, if you haven't done so already, I recommend using fullscreen mode (click fullscreen on the macOS window bar). 
10. Congrats! You can now proceed with the installation. For files you download from the internet, if you do so from your macOS, simply drag and drop them into the virtual machine. 

#### On Intel Macs

You're in luck! You can just install Windows directly on your machine using Bootcamp. Follow the guide [here](https://support.apple.com/en-us/102622). 


### Part 1: Install and patch BFME2
1. Install BFME2 base
    1. Download The Battle for Middle-earth™ II, original unmodified version: [Main](https://www.mediafire.com/download/4heo0ipvahha2yd/tBfMe_II.iso) / [Mirror 1](https://mega.nz/file/bQUhDCKA#gT92BtDHBnuMYxBVekjBUt-9Szpq2geZSw0XLiQ1yPk)
    3. **If running Parallels Desktop: Move the download out of the shared Downloads folder and directly onto the Windows partition, e.g. into C:\\.**
    4. Mount `tBfMe.iso` by double-clicking.
    5. Open the disk and run the `AutoRun.exe` contain within.
    6. Follow the default setup steps and install the game. Use one of these CD keys:
       <details><summary>BFME2 licence keys</summary>
       <ul>
        <li>HNB3-GRYM-GLUS-HKTU-Y9V8</li>
        <li>XLWW-55XX-5MB8-Q6QJ-5JAP</li>
        <li>42FP-FQES-GW72-MT37-MCGQ</li>
        <li>QJXX-3TVM-EE2V-NUYU-SWDW</li>
        <li>3QWW-QZQ7-USET-Z8NQ-WUYB</li>
        <li>HZKB-QJTS-W5E3-83PJ-K9AA</li>
        <li>ATK3-5TTF-9HJH-3TRW-2F8F</li>
        <li>M9NN-6NWW-5VRB-5KLN-EVV3</li>
       </ul>
       </details>
    8. Close the installer, do not yet run the game. 
1. Install the patch switcher + patch the game
    1. Download the patch switcher program [here](https://www.gamereplays.org/battleformiddleearth2/portals.php?show=page&name=bfme2-patch-1.09-version-3.0-live).
    2. **If running Parallels Desktop: Move the download out of the shared Downloads folder and directly onto the Windows partition, e.g. into C:\\.**
    3. Run the installer and install per default setup steps. Choose "run the patch switcher" at the end.
        - **Note:** If you run into issues installing the Patch Switcher ("Setup Error! Could not read setup package!"): right click the installer -> Properties -> Compatibility -> Windows on ARM: Change emulation settings -> Activate "Hide x64 emulation compatibility (x86 apps only)"
    5. Once openend, click on the `1.06` version button on the right of the screen. 
    6. Then, click the "flag" icon on the center button to verify the patch has been applied correctly.
    7. Close the patch switcher.

### Part 2: Install and patch ROTWK
1. Install ROTWK base (requires BFME2 to be installed first, see Part 1)
    1. Download The Rise of the Witch King, original unmodified version: [Main](https://www.mediafire.com/download/3p3ty93673wt4ks/tRotWk_ep.iso) / [Mirror 1](https://mega.nz/file/GBMVSY4B#2H2QzXodkeFfcpaItdwL4ySGVkna-nQv2GA37-yfsxw)
    3. **If running Parallels Desktop: Move the download out of the shared Downloads folder and directly onto the Windows partition, e.g. into C:\\.**
    4. Mount `rotwk.iso` by double-clicking.
    5. Open the disk and run the `AutoRun.exe` contain within.
    6. Follow the default setup steps and install the game. Use one of these CD keys:
       <details><summary>ROTWK licence keys</summary>
           <ul>
        <li>HE55-26J3-XSSL-A58B-BZ96</li>
        <li>YQFX-M2HH-LM62-NJ9T-KMZG</li>
        <li>TJLC-V87P-E5CY-ELRS-VLYP</li>
        <li>DJ7F-LB8A-NZDE-BJXN-8X8M</li>
        <li>3WH9-CR7P-4UPH-PPQE-DT39</li>
        <li>GG22-XGJA-GQ96-YJJS-NKVG</li>
        <li>HR55-MLNM-WFJN-UNWR-4X6T</li>
        <li>JW9R-97QL-NRFW-QAFL-UDEX</li>
               </ul>
       </details>
    8. Close the installer, do not yet run the game.
3. Install the v2.01 patch
    1. Download the v2.01 patch in your language, [here](https://www.gamefront.com/games/battle-for-middle-earth-2-rotwk/category/patches-148).
    2. **If running Parallels Desktop: Move the download out of the shared Downloads folder and directly onto the Windows partition, e.g. into C:\\.**
    3. Run the installer and follow the default steps.
4. Install the v2.02 patch, v.9.0.0
    1. Download the v2.02 patch, v.9.0.0, [here](https://www.moddb.com/downloads/start/245153).
    2. **If running Parallels Desktop: Move the download out of the shared Downloads folder and directly onto the Windows partition, e.g. into C:\\.**
    3. Run the installer and follow the default steps.
5. Configure options:
    1. Now, briefly run the game and quit again from the main screen.
    2. Then search for the `Run` program in the Windows search bar and enter `%appdata%`. Hit ENTER.
    3. Open the folder `My The Lord of the Rings, The Rise of the Witch-king Files`
    4. Open `Options.ini` via Notepad. Modify the screen resolution as per your screen's resolution. You can also modify the other settings as required. These settings work well for me:
       <details><summary>Options.ini</summary>
           
       ```ini
       AllHealthBars = yes
       AmbientVolume = 70.000000
       AudioLOD = High
       Brightness = 50
       FlashTutorial = 0
       HasGotOnline = yes
       HasSeenLogoMovies = yes
       IdealStaticGameLOD = UltraHigh
       MovieVolume = 80.000000
       MusicVolume = 60.000000
       Resolution = 3840 2160
       SFXVolume = 100.000000
       ScrollFactor = 50
       StaticGameLOD = UltraHigh
       TimesInGame = 3
       UseEAX3 = no
       VoiceVolume = 80.000000
       ```
       </details>

Done! 
     
### Sources:
- https://forums.revora.net/topic/105190-bfme1bfme2rotwk-games-download-installation-guide/?p=1028484
- https://oldgamesdownload.com/the-battle-for-middle-earth-ii-the-rise-of-the-witch-king/
- https://www.gamereplays.org/community/index.php?s=&showtopic=1056718&view=findpost&p=10588561
