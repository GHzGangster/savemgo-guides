# MGO Zero Method (OFW)

Last updated: September 2020 for FW 4.88.

[![Video guide thumbnail](https://img.youtube.com/vi/G9d4ij88XME/sddefault.jpg)](https://www.youtube.com/watch?v=G9d4ij88XME)  \
<https://www.youtube.com/watch?v=G9d4ij88XME>

This is the **Zero Method**, a guide for PS3s on Official Firmware (OFW). Unlike the **Backup Method**, you do not have to wipe your PS3 and will not lose any data in the process. This guide involves installing Hybrid Firmware (HFW) and using the PS3 Internet Browser to install the files necessary to connect to our server. The HFW may not be available for the PS3 firmware updates newer than the time this guide was last updated. Once you are done with this guide, you can revert to Official Firmware.

The MGS4 2.00 "Trophy Update" is not compatible with either OFW method, so you will not be able to use any MGS4 2.00 save games. If you want to continue to play MGS4 2.00, then get an MGS4 disc from a different region or the MGO Japan Standalone disc. Otherwise, you can follow the **MGO2 Launcher** guide with a hacked PS3 on CFW / HEN.


## Downloads

* HFW 4.88
  * <https://mega.nz/file/1l4CiLBZ#svG3LvEeOO13ziLUaXsp9YryhsGXEgmGoJJ8mY_WQAk>


## Requirements

To follow this guide, you will need the following:

* An un-hacked ("normal") PS3, which has PSN access, on Firmware 4.88 or earlier
* A disc with MGO data on it
    * &#10004;&#65039; MGO Japan Standalone, MGS4 Original
    * &#10004;&#65039; MGS4 Greatest Hits or Platinum **with the old "PlayStation 3" logo** (not the newer "PS3" logo)
    * &#10060; MGS4 25th Anniversary, Legacy Collection, Digital Version
* A flash drive with around 200 MB of free space, formatted as FAT32
* A computer. This guide uses Windows 10, but any operating system should work.


## 1. Flash drive Setup

Check to make sure that your flash drive is formatted as FAT32. You can do this in Windows Explorer by **right-clicking** on it, and clicking **Properties**. You should see `File system: FAT32`.
* If your flash drive isn't FAT32, then you will need to format it. **You will lose all data** on your flash drive by doing this! Be sure to copy anything you need off of it. You can follow a guide here:
  * <http://www.partition-tool.com/resource/manage-partition/format-usb-flash-drive-in-windows-10.html>

Download the HFW, extract it, and put it on your flash drive:

* Make sure file extensions are shown (not hidden) in your file viewer. In Windows Explorer, click on **View** near the top-left of the window. On the right side in the section labeled **Show / hide**, make sure **File name extensions** is checked.
* Create a new folder named `PS3`. Go into that folder. Inside that folder, create a new folder named `UPDATE`.
* Download the latest HFW firmware from the Downloads section. **Extract it** using 7zip or WinRAR.
* Copy the extracted PUP file to the `UPDATE` folder. Rename it to `PS3UPDAT.PUP` if necessary. **There is no letter E**.
* Remove your flash drive from your computer and plug it in to your PS3.


## 2. Firmware Installation

Install the HFW firmware from your flash drive:

* In the XMB, go to the **Settings** column, and select **System Update**.
* Select **Update via storage media**. You should see HFW in the name of this firmware.
    * If no firmware is detected, then you may have named the file incorrectly or did not extract it.
    * If that's not it, you may not be on FAT32.
    * If that's not it either, you might need to use a different flash drive. Older / cheaper ones work best for the PS3.
    * If you can't install the firmware this way, then go into Recovery Mode on your PS3, and install it there.
* Once the update is done, go to the **Settings** column, and select **System Information**. Make sure the firmware version matches what you installed. It will not contain `HFW`, `.1`, or anything like that, only the base firmware version.

## 3. Check Disc

Check your disc to make sure you have MGO data:

* Put your MGO-compatible disc into the PS3.
* In the XMB, go to the **Network** column, and select **Internet Browser**.
* Press **Start** to open the URL prompt. **Do not press Triangle** and use the browser menu, or you will do an Internet Search, and it will not work!
* Type in `http://mgo2.savemgo.com/zero` and press Start. Be sure to type it in **exactly** like that!
* When the application is ready, press **Check Disc**. This will make sure that your disc actually has MGO data.
    * If you get an error about the firmware, you did not install the correct HFW firmware and need to install it again.
    * If it does not have MGO data, you will need to get a disc that does, or follow the MGO2 Launcher guide with a hacked PS3.
* If it says your disc has MGO data on it, then you can continue.


## 4. Install MGO 1.01

Install the MGO data from disc and patch it:

* Now start MGS4 / MGO from the disc. If you are prompted for the MGS4 2.00 update, **decline it**. You should see "Metal Gear Online" in the menu. Start it!
    * If you do not see MGO in the MGS4 menu, then you have the 2.00 update installed, and will need to uninstall it. Your old MGS4 2.00 saves will unfortunately no longer work. In the XMB, go to the **Game** column, select **Game Data Utility**, and delete the **MGS4 Game Data**. Now start the game again, decline the 2.00 update, and you should see MGO in the menu.
* Let the game install the MGO 1.00 game data. Once you get to the title screen, hold the PS Button, and **Quit Game**.
* Go back to the PS3 Internet Browser and go to the Zero web page as before. Select your **MGO / MGS4 disc region** in the top-left, and press **Install 1.01**. When that's done, start MGO again. You should no longer see the prompt for the MGS4 2.00 update.
* When you get to the MGO title screen, you should be on `Ver 1.01`.


## 5. Install MGO 1.36

Start the game and install the 1.36 update:

* Start the game and select Yes on the Terms of Service screen.
* You should be prompted to install **Version 1.36**. Press X and select **HTTP Download**. This will take a while, so watch something on Netflix or smoke like Snake for the next hour or so.
    * If the download fails, press X to go back to the title screen and try again. If the game refuses to re-download the update and you're stuck, then go back to the Zero web page, and press on the **Delete Patch Lock** button.
* Once the data has finished downloading, press X to install it. This takes about 10 minutes.
* After the installation, **Quit Game** and start again.
* You should now be on Version 1.36. Congratulations! You will be prompted to download the latest game updates in the future.

## Final Notes

Please **NEVER DELETE THE GAME DATA!**

* If you delete the game data, you will lose access to MGO, and will need to follow this guide again&mdash;if possible on your current firmware.
* If you ever start the game and see the "Game Data is Corrupted" message, then do the following:
    * Press and hold the PS button, **Quit Game**, and start the game again. Once you get to the Save Data Notice screen (with "Continue X" in the bottom-right), press and hold the PS button, and **Quit Game**.
    * Start the game again. The error should be gone now.
    * If you still have the error, then try to go in to Recovery Mode on your PS3. **Be careful here!** Choose **Restore File System**, and see if that fixes your issues.
