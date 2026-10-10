> [!IMPORTANT]
> If you're not there already, and if you consider our effort, we would really appreciate if you joined my [Switch Emulators server](https://discord.gg/hPNG4QeskE). We have a really cozy and nice community! We'll be very happy to see new faces around :D

In this tutorial, I'll explain in detail how to fully set up your Eden emulator. It applies to any Yuzu-based emulator, as all these forks have the same UI, meaning the process is the exact same!

If you arrived here with the emulator already set up, you can easily skip to the ["setup save" section of this readme](ATTACH FILE)

I AM NOT AFFILIATED WITH NINTENDO IN ANY WAY, NOR I ENVY PIRACY. THIS IS A TUTORIAL JUST TO HELP WHO DOESN'T KNOW HOW TO SETUP THIS EMULATOR

# Installing the emulator program
- The first thing you need is, of course, the emulator. Be sure to go into [the Eden's official github release page](https://git.eden-emu.dev/eden-emu/eden/releases).
>[!NOTE]
> There's many specific executables of it, depending on the device you're downloading it for, so be sure to read it carefully to choose which one is more suitable for you!

![EdenDownload](https://github.com/user-attachments/assets/58cce2d7-9b5b-4193-9b0b-c76ddd0b7834)

You should be able to download a file called "Eden-OPERATINGSYSTEM-VERSION.zip" (as of writing the latest is 0.2.1)
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

- Open the Eden.exe file.

It's going to show a pop-up telling you that keys are missing, like in the image shown below.

![no keys found](ATTACH FILE)

- Click on "Yes" as we're going to install them.

- A new window will appear, you'll have to find the directory of your "prod.keys" file; when you've found it, single-click it to select it, and click on "Open" below

![prodkeys selection](ATTACH FILE)

> [!NOTE]
> This image is in Italian, but it should still look like this.

Now your keys are setup! If you've done everything correctly, you should see this:

![keys installed](ATTACH FILE)

Repeat this exact process but with files related to "Firmware" instead: Head to Eden's window again, and go on Tools > Install Firmware. Note that in this case you'll be able to keep your files as a .zip, the reason is explained through the image below.

![install firmware](ATTACH FILE)

# Setting up your games, DLC and Updates folder.
## Games
Before doing that, be sure to re-order your Switch games files, with DLCs and Updates placed in separated folders for easier accessibility. This is my setup recommendation:

![games setup](ATTACH FILE)

- Double click at the center of Eden's window, and select the directory where all the base games are

![games selection](ATTACH FILE)

- Once you've found it, single-click on it to select it, and click on "Select folder" below.

## DLCs and Updates 
To install DLCs and/or updates, head to Eden's window, and go to Files > Install file on NAND

![update/dlc selection](ATTACH FILE)

- Go in the "Updates" folder, and select all game updates from there, then click on "Open". A new window asking for comfirmation to install will appear:

![confirmation](ATTACH FILE)

If all updates have been installed successfully, you can repeat the process with DLCs by selecting all files into the "DLCs" folder instead!

# Moving your game save from a Yuzu-based emulator

I'll cover how to move your progress from Ryujinx/Ryubing emulator to Eden. It applies to any possible game, with Animal Crossing: New Horizons as an example here 

(In Eden)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will open a new window with all your ACNH save files.
- Move all of the files you see somewhere you can remember, we're going to move them into the Eden folder.

(In Ryujinx)
- Right click on Animal Crossing and click on "Open Save Data Location". This will create the shortcut to the save files of the game.
- Move the save files you've backed up into the Ryujinx directory. It's going to look like this:

![save setup](ATTACH FILE)

If you've done everything correctly, you'll be able to see that your game has successfully loaded your data. You're all set!
Thank you for following my tutorial! I hope it covered everything you needed! :D

For any question, you're free to let us know in the Discord Server!
