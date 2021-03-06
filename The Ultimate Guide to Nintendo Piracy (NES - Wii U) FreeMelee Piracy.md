The Ultimate Guide to Nintendo Piracy (NES -> Wii U) #FreeMelee
=================================================================

The Ultimate Guide to Nintendo Piracy (NES -\> Wii U)

\#FreeMelee

Due to the most recent events regarding the Big N, I decided now was a
good time to refine a guide on how to pirate Nintendo games. The one on
the Wiki was super outdated anyway and only covered the 3DS. This should
cover everything from the NES to the Wii U.

I'd go in-depth about Switch piracy as well but admittedly that's a much
more complicated situation and not one I feel qualified to talk about,
and also makes me a slightly bigger target for the Ninjas.

TABLE OF CONTENTS

Use CTRL-F to jump to the section you're looking for!

-   Home Consoles Up to the Wii (Emulation on PCs)

-   Handheld Consoles Up to the Nintendo 3DS (Emulation on PCs)

-   GameCube on Native Hardware

-   Wii on Native Hardware

-   Wii U on Native Hardware

-   Nintendo 3DS on Native Hardware

-   Nintendo DS on Native Hardware

-   Emulating on Hacked Systems

-   Flashcards

[Home Consoles Up to the Wii (Emulation on PCs)]

If you want to pirate any old Nintendo home console or handheld games,
the easiest way to do this is through emulation. While I cannot link to
ROMs here directly, I will say there is a subreddit aptly named to help
you find them.

For NES, SNES, and N64 on Windows or Linux, I recommend
[RetroArch](https://www.retroarch.com/) as an all-in-one solution. If
you're on macOS/OS X, I *highly* recommend
[OpenEmu](https://openemu.org/).

For GameCube and Wii on all platforms, there's [Dolphin
Emulator](https://dolphin-emu.org/).

For RetroArch:

-   Download the cores for the systems you want to play (Load Core \>
    Download a Core). RetroArch will tell you what systems each core is
    for. There's about a million different versions of the SNES core, so
    feel free to experiment with which one works for you!

-   Select "Load Content" from the main menu, and navigate to your ROM
    file. Select it, and it will ask you what core to run it with. Once
    that's set, you can start playing!

-   For easier access, you can make a new playlist of your ROMs and it
    will auto-sort them by system. Select "Import Content" and set it to
    scan the directory your ROMs are in. It will make them easier to
    load for future access!

For OpenEmu:

-   Drag and drop your ROM files onto the OpenEmu window.

-   Select the system you want to play in the sidebar.

-   Load your game!

For Dolphin:

-   Configure your controls in the Controllers menu. Make sure if you're
    playing GameCube games that your virtual GameCube controller is
    mapped, and if you're playing Wii games, that your virtual Wii
    Remote is mapped. There are options for Sideways Wii Remote, Upright
    Wii Remote, Classic Controller, and other schemes, so make sure you
    look over carefully and select the control scheme that is right for
    what you want to play.

-   Drag and drop an ISO or WBFS file onto the window.

-   You can also set a directory for your ROMs by double-clicking the
    message at the top of the window, for easier access.

**Note:** If you're interested in playing Super Smash Bros. Melee
online, [there's a great modified version of Dolphin called "Slippi"
just for that!](https://slippi.gg/netplay) I'd highly recommend giving
it a shot. It's netcode is better than Nintendo's own for SSBU.

[Handheld Consoles up to the Nintendo 3DS (Emulation on PCs)]

Handheld emulation is largely the same as home consoles.

For Game Boy, Game Boy Color, and Game Boy Advance on Windows and Linux,
I recommend [RetroArch](https://www.retroarch.com/) as an all-in-one
solution. For macOS/OS X users, I recommend
[OpenEmu](https://openemu.org/).

For Nintendo DS, I recommend [DeSmuMe](http://desmume.org/) or the
afforementioned OpenEmu. RetroArch has a DeSmuMe core, but it's not
exactly as performant or fully-featured as standalone.

For Nintendo 3DS, your only real option is
[Citra](https://citra-emu.org/). **Make sure your ROMs are in .3DS,
.3DSX, or .APP format! Updates and DLC are in .CIA format!**

For RetroArch:

-   Download the cores for the systems you want to play (Load Core \>
    Download a Core). RetroArch will tell you what systems each core is
    for.

-   Select "Load Content" from the main menu, and navigate to your ROM
    file. Select it, and it will ask you what core to run it with. Once
    that's set, you can start playing!

-   For easier access, you can make a new playlist of your ROMs and it
    will auto-sort them by system. Select "Import Content" and set it to
    scan the directory your ROMs are in. It will make them easier to
    load for future access!

For OpenEmu:

-   Drag and drop your ROM files onto the OpenEmu window.

-   Select the system you want to play in the sidebar.

-   Load your game!

For DeSmuMe:

-   Select "File" and then "Open ROM".

-   You're all set!

For Citra:

-   Select "File" and then "Load File".

-   Navigate to your ROM and launch it!

-   If a game has Updates or DLC, you can select "File" and "Install
    CIA" to install any applicable content, and then launch the base
    game ROM as usual.

**Note for Citra users!** Many 3DS games may require a Mii! You can
download a copy of the Mii Maker system application (in .APP format) and
run it like any other game, and make a Mii there. Highly recommended!

[GameCube on Native Hardware]

If you want a more authentic experience, you can play your GameCube
games on a Wii or a Wii U via SD card or USB through Nintendont.

**This section assumes you have already homebrew'd your Nintendo Wii or
Wii U system!** Luckily, there are already some wonderful guides for
this. For Wii users who haven't done so, [you can follow this
guide](http://wii.guide/). For Wii U users who haven't done so, [you can
follow this guide](https://wiiu.hacks.guide/). If you're on a homebrew'd
Wii U, [you will also need to follow this guide to mod your
vWii.](https://wiiu.hacks.guide/#/vwii-modding)

Because Nintendont on Wii U runs in vWii mode (a virtual Wii), the
process is largely the same for both Wii and Wii U users.

-   Insert your SD card or USB drive into your computer.

-   Download
    [loader.dol](https://github.com/FIX94/Nintendont/blob/master/loader/loader.dol?raw=true),
    [meta.xml](https://github.com/FIX94/Nintendont/blob/master/nintendont/meta.xml?raw=true),
    and
    [icon.png](https://github.com/FIX94/Nintendont/blob/master/nintendont/icon.png?raw=true).
    These files link to [the Nintendont
    github](https://github.com/FIX94/Nintendont) and should always be up
    to date.

-   In the "apps" folder of your SD card, create a new folder labelled
    "Nintendont". (It should look like D:/apps/Nintendont, or something
    similar. If the apps folder doesn't exist, create it.)

-   Copy the downloaded loader.dol, meta.xml, and icon.png over to the
    /apps/Nintendont folder.

-   Rename loader.dol to "boot.dol".

-   On the root of your SD card or USB drive, create a folder labelled
    "games". Put your GameCube ISOs in that folder.

-   Put the SD card or USB drive back into your Wii or Wii U. On Wii,
    launch the Homebrew Channel. On Wii U, launch the Wii Mode, and then
    the Homebrew Channel.

-   Select Nintendont from the list, and then select your game from the
    Nintendont menu!

**Note:** Before you boot any games, I recommend you set memory card
emulation to on, so you can save your games. I recommend the settings
"Emulation: on", "Card size: 251", and "Multi: off".

**Note 2:** Nintendont supports a wide array of controllers, such as the
Wii Classic Controller, Wii U Pro Controller, and GameCube Adapter for
Wii U. On the original Wii with GameCube controller ports, the GameCube
controller is natively supported.

[Wii on Native Hardware]

If you're looking for an authentic Wii experience, you can natively load
Wii games via SD card or USB drive on both Wii and Wii U systems.

**This section assumes you have already homebrew'd your Nintendo Wii or
Wii U system!** Luckily, there are already some wonderful guides for
this. For Wii users who haven't done so, [you can follow this
guide](http://wii.guide/). For Wii U users who haven't done so, [you can
follow this guide](https://wiiu.hacks.guide/). If you're on a homebrew'd
Wii U, [you will also need to follow this guide to mod your
vWii.](https://wiiu.hacks.guide/#/vwii-modding)

It's recommended you have both an SD card and a USB drive - SD card to
load homebrew, and USB drive to store games. This guide assumes you are
using separate devices, however the instructions remain the same if you
do not.

-   You will need [the latest release of USB Loader
    GX](https://sourceforge.net/projects/usbloadergx/), and
    [WiiBackupManager](https://static.wiidatabase.de/Wii-Backup-Manager.zip).
    macOS users can use
    [WitGui](https://desairem.com/wordpress/category/witgui-download/)
    as an alternative.

-   Extract the USB Loader GX zip file. Copy the "apps" folder it spits
    out onto your SD card. (It should look like D:/apps/usbloader\_gx,
    or something similar.)

-   Open Wii Backup Manager.

-   Select the tab labelled "Drive 1". In the drop down menu in the top
    bar, select the USB drive you're using for your Wii games.

-   Select the "Files" tab, and then select "Add". Select files to add
    individual games, or folder to add a whole folder.

-   Select "Transfer" and select "Drive 1" as your destination. Kick
    back, and relax - this might take a while.

-   Once your transfer is complete, eject your SD card and USB drive
    from your PC and reconnect them to your Wii or Wii U.

-   On Wii, launch the Homebrew Channel. On Wii U, launch the Wii Mode,
    and then the Homebrew Channel.

-   Select USB Loader GX from the launcher menu, and then select the
    game you want to play!

**Notes:** USB Loader GX is highly customizable, so I encourage you to
poke and prod with the software to see it how you see fit! If your
system is connected to the internet, you can even scrape things like box
art and banners. If USB Loader GX gets stuck on Waiting for HDD, it
can't detect your USB drive. Make sure it always uses the bottom port
first. On Wii U, the USB ports are incredibly low-powered, so it might
not be able to provide enough power for your drive.

[Wii U on Native Hardware]

This is where the fun begins. Instead of obtaining ISOs from the
internet, instead we'll be using Wii U USB Helper, a tool to download
directly from Nintendo's CDN servers. As of right now, this guide is
Windows only, although there are reports of USB Helper working under
Wine for Linux.

**Your Wii U will need to be homebrew'd already before continuing this
guide.** If you aren't already hacked, you can get started with an easy
guide [here](https://wiiu.hacks.guide/#/).

-   Insert your Wii U SD card into your computer.

-   Download the [Wii U USB Helper
    installer](https://github.com/FailedShack/USBHelperInstaller/releases/latest).

-   Run the installer. Leave all settings as default, as they'll be just
    fine for what we're doing. When it's done installing, leave "Run
    USBHelperLauncher" checked.

-   Upon first boot, it will ask you to select the region for your
    system. This can be changed later, but I recommend choosing your
    system's region - so if you have a US system, select USA.

-   Wii U USB Helper will ask you to select a location to store games.
    Create a folder on your computer - NOT on your SD card.

-   It will then ask for a title key site. Enter "titlekeys.ovh" in the
    box, with no quotes. After this, it will take a little bit of time
    to load - that's normal.

-   Once that is complete, you'll see a huge list of games. Search for
    the game you want in the top box (i.e. Splatoon).

-   In the bottom right corner, you'll see an "add" button. Select it
    and it will add to the download queue. It might ask if you want to
    download any DLC or updates as well. Leave those checked.

-   Once you've selected all of the games you want to download, click
    the start downloading button!

-   A window will pop on the side with a network graph. At the *very*
    bottom, there's a small group of checkboxes labelled "Action to
    perform once downloading is over". Select "Copy to SD". It might ask
    you where your SD card is, so point it in the right direction if it
    does.

-   Once your downloads are complete, the games will copy to your SD.
    Make sure there's enough space.

-   Once everything is A-OK and good to go, remove your SD card from
    your PC and put it back in your Wii U.

-   On your Wii U, launch the Homebrew Launcher, and then WUP Installer
    GX2.

-   In WUP Installer GX2, press the Plus button to select all titles and
    then click install. It'll ask you where to install - NAND is your
    system's internal storage, and USB is any *Wii U formatted* USB
    storage attached. (**This is NOT for regular USB drives. Only USB
    drives that have been formatted USING THE WII U SYSTEM.**)

-   Once the install is finished, your games are all set and ready to
    play! Just launch them from the System Menu. You are free to delete
    their installer files from the SD card if you haven't already.

**Note:** Online Play for these games works 100%. There are no records
of anyone being banned yet - myself included - but do keep in mind that
this is a risk you take!

[Nintendo 3DS on Native Hardware]

It's time for some handheld love. This guide assumes your 3DS is already
hacked. If it isn't, [you can start here.](https://3ds.hacks.guide/).
This guide heavily depends on usage of tools that are explained and
installed in this guide!

There are a few methods, and we'll go over two - the slow but easy
method (FBI) and the fast but more complex method (custom-install).

**This guide requires all of your 3DS games are in .CIA format!**

Easy Method (Slower installs, better for less games)

-   Insert your 3DS SD card into your PC.

-   Copy your CIA installer files - for games, updates, and DLC - into
    the cias folder on your 3DS SD card (it should look like D:/cias. If
    the cias folder doesn't exist, create it.)

-   Once the copy is complete, eject the SD card from your PC and
    reinsert it into your 3DS.

-   On your 3DS, open the FBI application. (This should have been
    installed when you hacked your system.)

-   On the main menu, select "SD", and then the "cias" folder.

-   At the top of the listing, you should see "\<current directory\>".
    Select that, and then select "Install and delete all CIAs". This
    will install all of the CIAs present, and then automatically remove
    them after install.

-   Once the install is finished, simply unwrap your games on the HOME
    Menu and play!

Hard Method (Faster installs, better for more games or batch installs)

-   We have to dump a few files from your 3DS before we begin. These
    files are boot9.bin and movable.sed.

-   Power off your 3DS. Press and hold the start button, and while
    holding start, power it back on. This will boot into GodMode9.

-   boot9.bin: Select "[M:] Memory virtual". Select boot9.bin with the A
    button, and then choose "Copy to 0:/gm9/out".

-   movable.sed: Select "[1:] Sysnand CTRNand". Navigate to "private",
    and then select movable.sed with the A button. Choose "Copy to
    0:/gm9/out."

-   Power off your 3DS, and insert your SD card into your PC.

-   On the SD card, navigate to the "gm9" folder, and then "out". Copy
    boot9.bin and movable.sed to your Desktop.

-   Download the [latest release of
    custom-install.](https://github.com/ihaveamac/custom-install/releases/download/2.0/custom-install-standalone.zip),
    and extract it.

-   Move boot9.bin and movable.sed to the same folder that you extracted
    custom-install.

-   Launch "ci-gui.exe". It should auto-fill most of the forms at the
    top for you. If it doesn't, simply manually point it towards your SD
    card, boot9, and movable.

-   Select "Add CIAs" to choose which CIAs to install, or "Add folder"
    to add a whole folder of CIAs.

-   Once all of your CIA files are selected, click "Start install". Your
    games will start to copy to SD.

-   Once it's complete, eject your SD and put it back in your 3DS.

-   Launch the Homebrew Launcher from the HOME Menu, and then select
    "custom-install-finalize". Let that do it's thing, and when it's
    done, you're all set! Simply unwrap your games from the HOME Menu,
    and jump in!

**Notes:** Much like the Wii U, online play does work with most games
installed this way, however, you run the risk of getting banned!

[Nintendo DS on Native Hardware]

Using a hacked 3DS, you can run DS games right from the SD card using a
program called TWiLightMenu++ (referred to as TWLMenu from here on out).
TWLMenu acts as a translation layer between DS ROMs and the 3DS,
allowing for mostly-native DS gameplay straight from the SD card.

Unfortunately, the downside to this is that compatibility isn't always
spot-on, but it does the trick.

**This guide assumes your 3DS is already hacked. If it isn't,**[**you
can start here.**](https://3ds.hacks.guide/)**.**

-   Download the [latest release of
    TWLMenu-3DS](https://github.com/DS-Homebrew/TWiLightMenu/releases/latest).

-   Insert your 3DS SD card into your PC.

-   Copy "TwiLight Menu.cia" and "TWiLight Menu - Game booter.cia" to
    the "cias" folder on your SD card. (If it doesn't exist, create it.)

-   Copy the "roms" folder and "\_nds" folder to the root of your SD
    card.

-   Drag and drop your DS ROMs, in .nds format, to the "nds" folder
    inside of the "roms" folder.

-   Eject your SD card, and put it back in your 3DS.

-   On your 3DS, launch FBI. Select "SD", and then "cias". Install
    **both** "TWiLight Menu.cia" and "TWiLight Menu - Game booter.cia".

-   Once that's complete, exit FBI. Unwrap TWLMenu, and launch it.

-   If you see a screen that looks like the Nintendo DS menu, press B.
    It will take you to a menu that looks like the Nintendo DSi menu
    instead.

-   Navigate to the roms folder, then press A. Then, navigate to the nds
    folder, then press A.

-   Select a game to start playing!

[Emulating on Hacked Systems]

Because hacked Wii, Wii U, and 3DS systems can run homebrew software,
you can also use them to run emulators!
[RetroArch](https://www.retroarch.com/) has ports available for all
three systems, so if you wanted to turn your Wii U or 3DS into a
one-stop shop for your Nintendo needs, you absolutely can!

There are also other emulator options for mobile platforms as well.
However there are so many different emulators that I can't test them
all, so don't be scared to test some of your own out as well. For
example, Dolphin and Citra also have Android ports, so if you *really*
wanted to play Super Mario Galaxy 2 on a 4.5-inch display, you totally
could.
