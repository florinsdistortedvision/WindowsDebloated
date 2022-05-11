# WindowsDebloated

* Microsoft adds a lot of useless junk, that just scews with your performance and storage space.
* This guide aims to fix that, call it a *Windows Lite* if you want to.


# Debloating the installer

* Download and extract:
  * <a href="https://www.7-zip.org"> 7zip </a>
  * <a href="https://www.microsoft.com/en-us/software-download/windows10"> Media Creation Tool for Windows 10 </a>
  * <a href="https://www.microsoft.com/software-download/windows11"> Media Creation Tool for Windows 11 </a>
  * <a href="https://msmgtoolkit.in/downloads.html"> MSMG ToolKit </a>
  * <a href="https://rufus.ie/en/"> Rufus </a>
* Run Media Creation Tool, accept terms, choose recommended settings, download ISO to desktop and give it a cool name.
* Put ISO in MSMG Toolkit's ISO folder.
* Run start.bat. Accept Terms.
* In ToolKi's Main Menu, select Option 1 > Option 5 > Input your ISO name. Wait.
* Back in the Main Menu, select Option 1 > Option 7 > Select the number coresponding to your Windows edition. **Can be selected all, but it will greatly cut down the overall size and next step's loading time.**
* Back in the Main Menu, select Option 1 > Option 1 > Select your edition > Yes > Yes. Wait.
* Back in the Main Menu, select Option 3 > Option 1 > Option 1 > Go through each category (Select either A or 1 for categories with a lot of options to unselect all - it will show a "-" if it will be removed or "+" if it stays).
  * **Make sure to keep all the codec options and File Explorer as they are needed for normal operations.**
* After selecting what to remove select X > Option 2. Wait.
* Back in the Main Menu, select Option 5 > Option 2 > Y. Wait.
* Back in the Main Menu, select Option 6 > Option 1 > Give it a name. Wait. 
* Your finisihed ISO will be in ISO folder.
* Insert your USB flash drive, open Rufus, select ISO and flash the image. Wait.
* Done.

## Post-install blotware removal

* You can create a folder called **post** and put it inside USB flash drive's root.
* Download and save the files in the **post** folder:
  * <a href="https://www.7-zip.org"> 7zip </a>
  * <a href="https://github.com/kkkgo/KMS_VL_ALL"> KMS VL ALL </a>
  * <a href="https://www.oo-software.com/en/shutup10"> OO Shutup10++, also works on Win11 </a>
  * <a href="https://github.com/ChrisTitusTech/win10script"> Windows 10 Debloater Script </a>
  * <a href="https://github.com/teeotsa/windows-11-debloat"> Windows 11 Debloater Script </a>
  * A internet browser's setup of your choice.

## Installing Windows and removing the remaining bloat.

* Install Windows like you would do it normally. **A Clean install is recommended!**
* **KEEP EVERYTHING OFFLINE DURING INSTALL SO THAT WINDOWS UPDATE WILL NOT AUTO-INSTALL ADDITIONAL UPDATES**.
* In the post folder, Install 7Zip.
* Extract archives, run AutoRenewal-Setup.cmd inside KMS_VL_ALL and select Y on prompt.
* Open PowerShell as administrator, and use cd command to extracted debloater script's directory.
* Run following command: **Set-ExecutionPolicy -ExecutionPolicy unrestricted**. Select A on prompt.
* Run the ps1 script.
  * On Windows 11, select Essential Tweaks, Old Context Menu, Disable Background Apps, Disable Cortana, Disable Windows Update, Unninstall OneDrive, Uninstall BloatWare, Uninstall Edge, Disable Windows Defender.
  * On Windows 10, select Essential Tweaks, Disable Background Apps, Delete OneDrive, Disable Cortana, Remove MS Store Apps, Disable Update Services.
* Run OO Shutup10++, Select Actions > Apply All Settings, wait a bit then close it. Select Restart.
* Done. You can now connect back to internet.

## Extra things you can do

* Drivers: NVCleanInstall, Visual C++ All-in-One package.
* Chromium extensions: AdGuard (with everything turned on), Popper Blocker.
