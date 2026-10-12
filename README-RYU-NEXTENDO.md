> [!IMPORTANT]
> If you're not there already, and if you consider our effort, we would really appreciate if you joined my [Switch Emulators server](https://discord.gg/hPNG4QeskE). We'll be very happy to see new faces around :D

## ⚠️ THIS TUTORIAL USES NEXTENDO NETWORK ⚠️
Be sure to visit the [official Nextendo Network site](https://nextendo.network/) and <ins>be sure to create an account in order to use online connectivity!</ins>
Additionally, <ins>YOU NEED TO HAVE VERSIONS 22.5.0 OF BOTH FIRMWARE AND KEYS</ins> in order for Nextendo to work. <ins>DO NOT UPDATE THESE TO A LATER VERSION</ins>

In this tutorial, I'll explain in detail how to fully set up your Ryujinx emulator.

If you arrived here with the emulator already set up, you can easily skip to the ["setup save and data" section of this readme](ATTACH LINK)

I AM NOT AFFILIATED WITH NINTENDO IN ANY WAY, NOR I ENVY PIRACY. THIS IS A TUTORIAL JUST TO HELP WHO DOESN'T KNOW HOW TO SETUP THIS EMULATOR

# Installing the emulator program
- The first thing you need is, of course, the emulator. Be sure to go into [the Downloads section of Nextendo](https://nextendo.network/telecharger) and simply select "Ryujinx" with your corresponding Operative System

![canary](https://github.com/user-attachments/assets/ea09ef5c-3f19-4d1d-87db-6bd7f0dd3219)

You should be able to find and download a file called "Nextendo-VERSION-OPERATINGSYSTEM.zip" (as of writing the latest is 1.8.14)
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

- Open the Ryujinx.exe file. 
>[!NOTE]
> Note that it's gonna open a terminal too, THAT'S COMPLETELY NORMAL as it uses that to collect infos in case the emulator crashes when playing.

It's going to show a pop-up telling you that keys are missing.

![no keys found](https://github.com/user-attachments/assets/64c14d16-b2ec-4997-8e89-c62ebeb70697)

- Click on "OK" anyway, as we're going to install them.

- Click on "Action" above, and with your cursor on "Install keys	>".

![install keys](https://github.com/user-attachments/assets/471d2e53-8723-4def-8e33-fd8c418fe55a)

You can now choose either the installation through the direct file or through the "Prod keys" folder. We're gonna cover the second option.

- A new window will appear, you'll have to find the directory of your prodkeys folder; when you've found it, single-click it to select it, and click on "Select folder" below.

![prodkeys selection](https://github.com/user-attachments/assets/aeefc1b1-d173-4321-980d-37234b61770a)

> [!NOTE]
> This image is in Italian, but it should still look like this.

Now your keys are setup! Repeat this exact process but with files related to "Firmware" instead. Note that in this case you'll be able to keep your files as a .zip, the reason is explained through the image below.

![install firmware](https://github.com/user-attachments/assets/51b2b2e5-48d1-4ccc-bfb5-3d2c1147b5a2)

# Setting up your games, DLC and Updates folder.
Before doing that, be sure to re-order your Switch games files, with DLCs and Updates placed in separated folders. This is my setup recommendation:

![games setup](https://github.com/user-attachments/assets/0f21bd21-097c-4262-b2f0-2793f28a3428)

- Go into the settings, from the "Options" tab above as in this image

![settings](https://github.com/user-attachments/assets/d21db783-986d-4b6b-ab6a-622e94e85e0b)

> It'll open a new window
- From the new window, choose "Add" in the "Game Directories" section, there will be another window and from there you'll have to find your Switch games folder. Once you've found it, single-click on it to select it, and click on "Select folder" below.

- Do the exact same thing for DLCs and Updates from the "Autoload DLC/Update Directories" section.
when you're done, it's gonna look like this:

![all set](https://github.com/user-attachments/assets/5685a858-9327-4edf-8a94-cdae4ff061f5)

- Click on "Apply" below and then on "OK". If it shows the message as the message below, you've successfully set it up and ready to play!

![success1](https://github.com/user-attachments/assets/975a86e5-b864-4e3e-9693-2224b37425bc)

# Moving your game save from the non-Nextendo version of Ryujinx

I'll cover how to move your progress from the official release version of Ryujinx emulator to Nextendo. Moving game saves in particular also applies to any possible game, it should load them just fine since they share the same folders, but depending on many factors, that's not always the case. If that's the case, I made an example of a manual transfer with Animal Crossing: New Horizons as an example here.

## Game saves

(In Nextendo)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will open a new window with all your ACNH save files.
- Move all of the files you see somewhere you can remember, we're going to move them into the Ryujinx folder.

(In Ryujinx)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will create the shortcut to the save files of the game.
- Move the save files you've backed up into the Ryujinx directory. It's going to look like this:

![save setup](https://github.com/user-attachments/assets/8cdf34fb-4493-44ae-8828-5292fc517b8d)

![success 2](https://github.com/user-attachments/assets/83c6a773-073f-4a8e-839e-92bb18b0d7c3)

If you've done everything correctly, you'll be able to see that your game has successfully loaded your data. You're all set!

## Emulator settings

While you were setting everything up, you probably realized that your profile, amount of hours played and settings are set to their default. I'll show you how to 
get back your original stuff.

(In Ryujinx)
- Go on "File" at the upper left corner
- "Open Ryujinx Folder"
You're going to see a bunch of folders and files, like these:

![Ryujinx folders setup](https://github.com/user-attachments/assets/83d07e06-cff2-49b2-beed-9641f7778368)

- Select everything you see in here! Put them somewhere temporary as we're going to put them into Nextendo. These are all the settings and NAND files that your emulator saved.
You can now close Ryujinx.

(In Nextendo)
- Go on "File" at the upper left corner
- "Open Ryujinx Folder"
- Close the emulator (THIS IS IMPORTANT)
- Drag & Drop all the files we moved before

Open Nextendo again, and just like that, you'll be able to see all your statistics and settings applied again!

Enjoy the emulation and the beauty that people brought thanks to such a passionate community! :D
