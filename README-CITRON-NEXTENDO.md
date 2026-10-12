> [!IMPORTANT]
> If you're not there already, and if you consider our effort, we would really appreciate if you joined my [Switch Emulators server](https://discord.gg/hPNG4QeskE). We'll be very happy to see new faces around :D

## ⚠️ THIS TUTORIAL USES NEXTENDO NETWORK ⚠️
Be sure to visit the [official Nextendo Network site](https://nextendo.network/) and <ins>be sure to create an account in order to use online connectivity!</ins>

Additionally, <ins>YOU NEED TO HAVE VERSIONS 22.5.0 OF BOTH FIRMWARE AND KEYS</ins> in order for Nextendo to work. <ins>DO NOT UPDATE THESE TO A LATER VERSION</ins>

In this tutorial, I'll explain in detail how to fully set up your Citron emulator.

If you arrived here with the emulator already set up, you can easily skip to the ["setup save" section of this readme](ATTACH LINK)

I AM NOT AFFILIATED WITH NINTENDO IN ANY WAY, NOR I ENVY PIRACY. THIS IS A TUTORIAL JUST TO HELP WHO DOESN'T KNOW HOW TO SETUP THIS EMULATOR

# Installing the emulator program
- The first thing you need is, of course, the emulator. Be sure to go into [the Downloads section of Nextendo](https://nextendo.network/telecharger) and select Citron.

![CitronDownload](https://github.com/user-attachments/assets/176af981-a4b3-4773-bdf7-056d444ac65a)

You should be able to download a file called "Citron-OPERATINGSYSTEM-VERSION.zip" (as of writing it uses the nightly version)
- Now extract the zip file somewhere you remember. You have the emulator ready to run! But it still needs Firmware and keys...
>[!TIP]
> This is completely optional, but you can easily make a desktop shortcut of the emulator by:
>	- Right clicking on the .exe
>	- Going with your cursor onto "send to…"
>	- Clicking on "create Desktop shortcut"

# Installing prod.keys & title.keys and Firmware
>[!NOTE]
> Before proceeding, make sure you have all of the files above, as I won't cover how to obtain them for legal reasons.
Be sure to extract your keys files if you only have a .zip!

- Open the citron.exe file.

It's going to show a pop-up telling you that keys are missing, like in the image shown below.

![no keys found](https://github.com/user-attachments/assets/81c85f06-e236-4062-9594-ed4d7f5800ba)

- Click on "Ok" as we're going to install them.

- A new window will appear, you'll have to find the directory of your "prod.keys" file; when you've found it, single-click it to select it, and click on "Open" below

![prodkeys selection](https://github.com/user-attachments/assets/d8578a93-c703-4f62-aeed-444f3c657bcd)


Now your keys are setup! If you've done everything correctly, you should see a "Keys are successfully installed" prompt!
Repeat this exact process but with files related to "Firmware" instead: Head to Citron's window again, and go on Tools > Install Firmware. Note that in this case you'll be able to keep your files as a .zip, the reason is explained through the image below.

![install firmware](https://github.com/user-attachments/assets/05f7583b-b567-4e8c-8884-7ba181fb7886)


# Setting up your games, DLC and Updates folder.
## Games
Before doing that, be sure to re-order your Switch games files, with DLCs and Updates placed in separated folders for easier accessibility. This is my setup recommendation:

![games setup](https://github.com/user-attachments/assets/ffd46ede-1144-4371-9d18-dff5e7755b74)

- Double click at the center of Citron's window, and select the directory where all the base games are

![games selection](https://github.com/user-attachments/assets/dc6b767f-0f8f-44e4-ac24-2067e4e6a72e)



- Once you've found it, single-click on it to select it, and click on "Select folder" below.

## DLCs and Updates 
To install DLCs and/or updates, head to Citron's window, and go to Files > Install file on NAND

![update/dlc selection](https://github.com/user-attachments/assets/5770fc1f-b05d-48cd-9dc7-f1ccedd77a1c)

- Go in the "Updates" folder, and select all game updates from there, then click on "Open". A new window asking for confirmation to install will appear. Confirm and it's going to install all the files you've selected.

If all updates have been installed successfully, you can repeat the process with DLCs by selecting all files into the "DLCs" folder instead.
If not, make sure that both prod.keys and firmware have the exact same version!

# Moving data

I'll cover how to move your progress from the official release version of Ryujinx emulator to Nextendo. Moving game saves in particular also applies to any possible game AND emulator. I made an example of a manual transfer with Animal Crossing: New Horizons as an example here.

## Game saves (from any emulator)
I'm going to use the non-nextendo version of Ryujinx as the "old" emulator as an example:

(In Ryujinx)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will open a new window with all your ACNH save files.
- Move all of the files you see somewhere you can remember, we're going to move them into the Citron folder.

(In Citron)
- Right click on Animal Crossing and click on "Open Save Data Location". This will create the shortcut to the save files of the game.
- Move the save files you've backed up into this new directory. It's going to look like this:

![save setup](https://github.com/user-attachments/assets/e86c15ab-fe1c-4e88-8332-ef7884e83e44)

If you've done everything correctly, after opening the game, you'll be able to see that it has successfully loaded your data.

## Emulator settings (from non-Nextendo Eden/Citron)

While you were setting everything up, you probably realized that your profile, amount of hours played and settings are set to their default. I'll show you how to 
get back your original stuff.
> [!WARNING]
> it does NOT work from Ryujinx!!
(In Eden/Citron)
- Go on "File" at the upper left corner
- "Open Eden (or Citron) Folder"
You're going to see a bunch of folders and files, like these:

![Eden folders setup](https://github.com/user-attachments/assets/0b569ab8-e5b9-483c-aac7-e6b7de4bfc84)

- Select everything you see in here! Put them somewhere temporary as we're going to put them into Nextendo. These are all the settings and NAND files that your emulator saved.
You can now close Ryujinx.

(In the Nextendo Citron)
- Go on "File" at the upper left corner
- "Open Citron Folder"
- Close the emulator (THIS IS IMPORTANT)
- Drag & Drop all the files we moved before

Open Nextendo again, and just like that, you'll be able to see all your statistics and settings applied again!

Enjoy the emulation and the beauty that people brought thanks to such a passionate community! :D

Thank you for following my tutorial! I hope it covered everything you needed! :D

For any question, you're free to let us know in the Discord Server!
