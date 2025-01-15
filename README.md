[SP]: https://drive.google.com/file/d/1xc7v86im_8VNneGDipiNWL80RCtmDaoo/view?usp=drive_link
[SP-Mirror1]: https://mega.nz/file/cfohGBRY#xNlscCOwMfqaOrH9I43jTsIvZdd6q2Q_uFZCJGTCvoQ 
[SP-Mirror2]: https://www.mediafire.com/file/yxt4j8sll4w7hec/Liberty_City_Preservation_Project_-_Singleplayer.7z.torrent/file
[SP-Mirror3]: https://disk.yandex.com/d/GoKA4KXiyde9_A
[SPHD]: https://drive.google.com/file/d/1xiugZMcszJdTVB3CAuCkRSLQ3iyAkvWH/view?usp=drive_link
[SPHD-Mirror1]: https://mega.nz/file/kDhyjaxY#jBP8Y5oU4sGUEy4IxWr6YOVRvquDZry-PByUA-RLWLQ  
[SPHD-Mirror2]: https://www.mediafire.com/file/qv60so81hb19l1r/Liberty_City_Preservation_Project_-_Singleplayer_-_HD_Textures.7z.torrent/file
[SPHD-Mirror3]: https://disk.yandex.com/d/UiN1DTKYDBo-4A
[FM]: https://drive.google.com/file/d/16clpA60YvZll-tq7PRrAUrqLI_aOYz8k/view?usp=drive_link
[FM-Mirror1]: https://mega.nz/file/RGw3kJib#blz1oyMsa3NV6kexS0PsD57Fdsp2k2ITfXPiQ7JnXe8 
[FM-Mirror2]: https://www.mediafire.com/file/z2fw5sdltchq3tl/Liberty_City_Preservation_Project_-_FiveM.zip.torrent/file
[FM-Mirror3]: https://disk.yandex.com/d/HLBcUC5KaFzHUw
[Hotfix]: https://www.mediafire.com/file/tc4wnj01y5ivmak/WorldTravelPatches.asi/file
[Hotfix-Mirror]: https://disk.yandex.com/d/fQlKNcxYzTuO-w
[Uninstaller]: https://www.mediafire.com/file/yxk8ssuxyeo8hda/UNINSTALL+-+Liberty+City+Preservation+Project.oiv/file
[Unin-Mirror]: https://disk.yandex.com/d/n0XcGoaueLmp5g
[World Travel]: https://worldtravel.dev

# Liberty City Perservation Project REVIVAL

>⚠ **DISCLAIMER** ⚠: In compliance with Fair Use and completely disregarding Take-Two's end-user terms and conditions (and the request for non-distribution of the mod by their developers), I create this repository as a "support" to the Grand Theft Auto community.
>
>Nothing here (outside of the arguments) is my own.
>
>Disclaimers and legal notices should be directed to the authors/developers/leakers; we distributors are not guilty of sharing information for purely experimental and educational purposes (in this case to visualize how including this modification in the game's codebase can extend the life or use of the product outside of the original idea of ​​its primary creators).
>
>All legal advice and announcements should be referred to a court related to GitHub and its use in the European Union, not to the original creator of this repository.
>
>**YOU HAVE BEEN WARNED!**
---

Knowing that the project will be cancelled (and that it has already caused enough of a stir) I will try to keep alive (at least) the download of the files (even at the risk of losing all my accounts or getting sued by Rockstar Games/Take-Two)

### Downloads

- Singleplayer (normal textures): [SP] | [SP-Mirror1]? | [SP-Mirror2] | [SP-Mirror3]
- Singleplayer (HD textures): [SPHD] | [SPHD-Mirror1]? | [SPHD-Mirror2] | [SPHD-Mirror3]
- FiveM (this isn't part of the bussiness TT): [FM] | [FM-Mirror1]? | [FM-Mirror2] | [FM-Mirror3]
- Unique Hotfix (Singleplayer only): [Hotfix] | [Hotfix-Mirror]
- Uninstaller: [Uninstaller] | [Unin-Mirror]

  ***?: This host is hated by people, but it's just in case.***

**⚠ Keep seeding, don't hit and run ⚠**

## Installation (from devs source)

### Singleplayer Installation
Ensure you have Grand Theft Auto V installed via Steam, Rockstar Games Launcher, or Epic Games Store.

1. Download the Liberty City mod files below
2. Singleplayer files or Singleplayer HD files (for enhanced graphics).
3. Download ScriptHookV and extract the files.
   Open the Bin folder from the ScriptHookV download and copy the following files:
- dinput8.dll
- ScriptHookV.dll
4. Paste these into the main directory of your GTA V installation (whereGTA5.exe is located).
5. Download OpenIV and install it. Set it up for Grand Theft Auto V.
- In OpenIV, go to the Tools menu in the top-left corner and open ASI Manager. Install all three options that appear.
- After installing ASI Manager, you should now have a mods folder in your GTA V directory.
6. Return to the Tools menu, select Package Installer, and follow these steps for each part of the Liberty City files:
- Select the PART 1 file and install it to your mods folder.
- Repeat this step for each subsequent part (e.g., PART 2, PART 3, etc.).
7. Launch GTA V. If installed correctly, you should see "World Travel" displayed in the corner of the screen.
8. In-game, press F11 to teleport to Liberty City or travel to the blip marker at LSIA.

**Important Notes**:
If the mod doesn't work, ensure you've downloaded the ASI hotfix from the appropriate source.
Make sure there are no conflicting maps or mods installed.

### FiveM Installation

>Disclaimer
>
>While this guide provides instructions for installing the mod in FiveM, it is important to note that World Travel does not offer the same level of compatibility or support for the FiveM platform as it does for Singleplayer installations. Furthermore, we are in no way affiliated with FiveM/Cfx.re or its development team. Any issues or questions specific to FiveM should be directed to their official support channels.
---

FiveM Installation

1. Ensure you are running game build 3095. Add the following line to your server.cfg:
>sv_enforceGameBuild 3095

2. Download and place the required resources in your FiveM server's resources folder.
3. Start the resources in this order by adding the following lines to your server.cfg:
>ensure lcpack
>
>ensure liberty_vehicles
>
>ensure liberty_city_peds
>
>ensure libertycity
>

4. If your server enters a startup loop on the libertycity resource in TxAdmin, update the Restarter setting:
- Set the Restarter interval to 10 minutes.
5. To improve server startup speed, add an exclusion for your server folder in Windows Security or any other antivirus software:
- Open Windows Security.
- Go to Virus & Threat Protection.
- At the bottom, click Manage Settings under Virus & Threat Protection settings.
- Scroll down to Exclusions and click Add or remove exclusions.
- Click Add an exclusion, select Folder, and choose the folder containing your entire server.

**Additional Notes**:
- Ensure all other server resources are properly configured to avoid conflicts.
- If you encounter issues, check your console logs for errors related to resource loading.



**Installation video** (Singleplayer):

[![Installation video](https://i.imgur.com/UgFYULC.png)](https://www.youtube.com/watch?v=Ggm5gzCd9Ig&ab)

## Credits
- [World Travel] (the orginal devs of this project).
- PG (for having a good sense to save torrents in contradiction to the developers' request).
- All seeders (for making it possible for the download to still exist).
- All Rockstar Games studios (for developing the original games and maps).
- Take-Two (for terrorizing the entire modding community with unusual demands (as unauthorized as it may be, mods sustain the industry on the same level as a lucrative online mode))
