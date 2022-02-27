# MGO Launcher Guide (CFW / HEN)

Last updated: November 2020.

This is the **Launcher Guide**, a guide for PS3s on Custom Firmware (CFW) and HEN.


## Downloads

* MGO2-v30.pkg
  * <https://metalgear.online/dl/cfw/MGO2-v30.pkg> 
* MGO2 Patch 1.36.pkg
  * <https://metalgear.online/dl/cfw/MGO2%20Patch%201.36.pkg>
* MGO2 Disc.pkg (optional)
  * <https://metalgear.online/dl/cfw/MGO2%20Disc%20Data.pkg>
* CFW Evilnat 4.88 (suggested)
  * <https://www.brewology.com/?p=4627>


## Requirements

To follow this guide, you will need the following:

* A hacked PS3, on Firmware 4.84 or higher
* A flash drive with around 4 GB of free space, formatted as FAT32
* A computer. This guide uses Windows 10, but any operating system should work.


## 1. Flash drive Setup

Check to make sure that your flash drive is formatted as FAT32. You can do this in Windows Explorer by **right-clicking** on it, and clicking **Properties**. You should see `File system: FAT32`.
* If your flash drive isn't FAT32, then you will need to format it. **You will lose all data** on your flash drive by doing this! Be sure to copy anything you need off of it. You can follow a guide here:
  * <http://www.partition-tool.com/resource/manage-partition/format-usb-flash-drive-in-windows-10.html>

If necessary, download the CFW, extract it, and put it on your flash drive:

* Make sure file extensions are shown (not hidden) in your file viewer. In Windows Explorer, click on **View** near the top-left of the window. On the right side in the section labeled **Show / hide**, make sure **File name extensions** is checked.
* Create a new folder named `PS3`. Go into that folder. Inside that folder, create a new folder named `UPDATE`.
* Download the latest HFW firmware from the Downloads section. **Extract it** using 7zip or WinRAR.
* Copy the extracted PUP file to the `UPDATE` folder. Rename it to `PS3UPDAT.PUP` if necessary. **There is no letter E**.
* Remove your flash drive from your computer and plug it in to your PS3.


## 2. Firmware Installation

If necessary, install the CFW firmware from your flash drive:

* In the XMB, go to the **Settings** column, and select **System Update**.
* Select **Update via storage media**. You should see HFW in the name of this firmware.
    * If no firmware is detected, then you may have named the file incorrectly or did not extract it.
    * If that's not it, you may not be on FAT32.
    * If that's not it either, you might need to use a different flash drive. Older / cheaper ones work best for the PS3.
    * If you can't install the firmware this way, then go into Recovery Mode on your PS3, and install it there.
* Once the update is done, go to the **Settings** column, and select **System Information**. Make sure the firmware version matches what you installed. It will not contain `HFW`, `.1`, or anything like that, only the base firmware version.


## 3. Install Launcher

Download **MGO2-vXX.pkg** and **MGO2 Patch 1.36.pkg**, as well as **MGO2 Disc.pkg** if you aren't installing or can't install from disc. Put all of these PKG files on your flashdrive, at the root of it (not in any folders).
 
Install **MGO2-vXX.pkg**:

* Plug in your flash drive in to your PS3.
* In the XMB, go to the **Game** column, go to **Package Manager**, go to **Install Package Files**, and then select **Standard**.
* Select **MGO2-vXX.pkg** and install it.

If necessary, install **MGO2 Disc.pkg**:

* Follow the steps for installing **MGO2-vXX.pkg**.

Start the launcher and install the 1.00 Game Data:

* In the XMB, go to the **Game** column, and start the launcher, which is named **Metal Gear Online 2**.
* Follow the instructions in the launcher. 
* Once the 1.00 Game Data is installed, the game should quit to the XMB.
* Start up the launcher again and follow the instructions.

Once the launcher says to, install **MGO2 Patch 1.36.pkg**:

* Follow the steps for installing **MGO2-vXX.pkg**.

Start up the launcher again to finish installation:

* After starting the game and getting past the title screen and Terms of Service, you will be prompted to download and install any remaining game updates.


## Final Notes

* If you ever start the game and see the "Game Data is Corrupted" message, then do the following:
    * Press and hold the PS button, **Quit Game**, and start the game again. Once you get to the Save Data Notice screen (with "Continue X" in the bottom-right), press and hold the PS button, and **Quit Game**.
    * Start the game again. The error should be gone now.
    * If you still have the error, then try to go in to Recovery Mode on your PS3. **Be careful here!** Choose **Restore File System**, and see if that fixes your issues.
