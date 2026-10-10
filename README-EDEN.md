> [!IMPORTANT]
> If you're not there already, and if you consider our effort, we would really appreciate if you joined my [Switch Emulators server](https://discord.gg/hPNG4QeskE). We'll be very happy to see new faces around :D

In this tutorial, I'll explain in detail how to fully set up your Eden emulator. It applies to any Yuzu-based emulator, as all these forks have the same UI, meaning the process is the exact same!

If you arrived here with the emulator already set up, you can easily skip to the ["setup save" section of this readme](https://github.com/President00007/complete-tutorial-for-switch-emulators/blob/main/README-EDEN.md#moving-your-game-save-from-a-yuzu-based-emulator)

I AM NOT AFFILIATED WITH NINTENDO IN ANY WAY, NOR I ENVY PIRACY. THIS IS A TUTORIAL JUST TO HELP WHO DOESN'T KNOW HOW TO SETUP THIS EMULATOR

# Installing the emulator program
- The first thing you need is, of course, the emulator. Be sure to go into [the Eden's official github release page](https://git.eden-emu.dev/eden-emu/eden/releases).
>[!NOTE]
> There's many specific executables of it, depending on the device you're downloading it for, so be sure to read it carefully to choose which one is more suitable for you!

![EdenDownload](https://github.com/user-attachments/assets/58cce2d7-9b5b-4193-9b0b-c76ddd0b7834)
> This is a list of downloads for Windows, just as an example!
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

![no keys found](https://github.com/user-attachments/assets/7ec913d2-6602-47fe-9b3d-fc73bc8c7135)

- Click on "Yes" as we're going to install them.

- A new window will appear, you'll have to find the directory of your "prod.keys" file; when you've found it, single-click it to select it, and click on "Open" below

![prodkeys selection](https://github.com/user-attachments/assets/8d7ddaee-4a9c-4bce-b0c3-2df95c6bf395)

Now your keys are setup! If you've done everything correctly, you should see this:

![keys installed](https://github.com/user-attachments/assets/454dd3fc-9c5e-401b-bb6d-e2a1914526ad)

Repeat this exact process but with files related to "Firmware" instead: Head to Eden's window again, and go on Tools > Install Firmware. Note that in this case you'll be able to keep your files as a .zip, the reason is explained through the image below.

![install firmware](https://github.com/user-attachments/assets/a6bc0d20-9403-4116-91e1-38a4eda0215e)

# Setting up your games, DLC and Updates folder.
## Games
Before doing that, be sure to re-order your Switch games files, with DLCs and Updates placed in separated folders for easier accessibility. This is my setup recommendation:

![games setup](https://github.com/user-attachments/assets/ffd46ede-1144-4371-9d18-dff5e7755b74)

- Double click at the center of Eden's window, and select the directory where all the base games are

![games selection](https://github.com/user-attachments/assets/b18ee96a-b943-4371-b3c8-7664f6da78dd)


- Once you've found it, single-click on it to select it, and click on "Select folder" below.

## DLCs and Updates 
To install DLCs and/or updates, head to Eden's window, and go to Files > Install file on NAND

![update/dlc selection](https://github.com/user-attachments/assets/605f0559-d5fd-4401-a761-5546b3d108ee)


- Go in the "Updates" folder, and select all game updates from there, then click on "Open". A new window asking for confirmation to install will appear:

![confirmation](https://github.com/user-attachments/assets/25a6a628-3a0c-4492-a16f-d7c4ea9f9689)


If all updates have been installed successfully, you can repeat the process with DLCs by selecting all files into the "DLCs" folder instead!

# Moving your game save from a Yuzu-based emulator

I'll cover how to move your progress from Ryujinx/Ryubing emulator to Eden. It applies to any possible game, with Animal Crossing: New Horizons as an example here 

(In Ryujinx)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will open a new window with all your ACNH save files.
- Move all of the files you see somewhere you can remember, we're going to move them into the Eden folder.

(In Eden)
- Right click on Animal Crossing and click on "Open Save Data Location". This will create the shortcut to the save files of the game.
- Move the save files you've backed up into this new directory. It's going to look like this:

![save setup](https://github.com/user-attachments/assets/e86c15ab-fe1c-4e88-8332-ef7884e83e44)

If you've done everything correctly, you'll be able to see that your game has successfully loaded your data. You're all set!
Thank you for following my tutorial! I hope it covered everything you needed! :D

For any question, you're free to let us know in the Discord Server!
