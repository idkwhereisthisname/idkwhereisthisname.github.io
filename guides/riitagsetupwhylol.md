> RiiTag is a customizable gamertag. By sharing your gamertag, you can show what you've been playing to your friends! The tag updates on-the-fly. You need a Discord account in order to start using RiiTag. Covers are provided by GameTDB and this service is developed by RiiConnect24.
> ##### ([source](https://tag.rc24.xyz))

What do you need

- a text editor

- a computer

- a usb loader

- a wii (no shit)

Get Started

1. Go to the RiiTag site.
2. Click Log In and log in with your Discord account.
3. A dialog will pop up asking you if you want to authorize RiiConnect24 Login with Discord. Click Authorize.
4. Click Edit Your Tag and customize it to how you like. You can add a background, overlay, flag, nickname, Wii Number, and manually enter in games to show on your tag (not needed if you’re using a USB Loader).
5. Click Show Key and make note of the key shown. This is not needed if you’re using USB Loader GX, as the key will be in a downloadable file
6. Click Submit to save your changes.

Setting up your USB Loader

- USB Loader GX:

1. Load USB Loader GX on your Wii.
2. Go to Settings > Features and turn Wiinnertag on. Press Yes or OK to any dialogues that show up.
3. Ensure that Initialize Network is turned on.
4. Exit USB Loader GX.
5. Insert the SD Card or USB device where your USB Loader GX data is into your computer.
6. Go to [this](https://tag.rc24.xyz/Wiinnertag.xml) page.
7. Save the XML to <code>/apps/usbloader_gx</code> folder on your SD Card or USB device, replacing the existing Wiinnertag.xml.
8. You have now set up RiiTag. You can try loading any game now to see if it works correctly.

- WiiFlow

1. Take the SD Card or USB device where your WiiFlow data is into your computer.
2. Open <code>/apps/wiiflow/wiiflow.ini</code> with a text editor.
3. Search for gamercards and replace that line with <code>gamercards=wiinnertag</code>.
4. Search for wiinnertag_url and replace that line with <code>wiinnertag_url=http://tag.rc24.xyz/wii?game={ID6}&key={KEY}</code>.
5. Search for <code>wiinnertag_key</code> and replace that line with <code>wiinnertag_key=<key> </code>, replacing ``<key>`` with the key you wrote down in Section 
6. Search for <code>gamercards_enable</code> and replace that line with <code>gamercards_enable=yes</code>.
7. Save the modified <code>wiiflow.ini</code> file.
You have now set up RiiTag. You can try loading any game now to see if it works correctly.

- CFG USB Loader

Note that this USB loader is not officially supported
##### also who uses this in 2024 lmao

- You can also use <code>CfgLoaderConfigurator.exe</code> (Not for UNIX Systems) instead of editing <code>config.txt</code>

1. Take the SD Card or USB device where your Configurable USB Loader data is into your computer.
2. Open <code>/usb-loader/config.txt</code> with a text editor.
3. Replace (or add the line) starting with <code>gamercard_url</code> with <code>gamercard_url = http://tag.rc24.xyz/wii?game={ID6}&key={KEY}</code>.
4. Replace (or add the line) starting with <code>gamercard_key</code> with gamercard_key = <key>, replacing <key> with the key you wrote down in Section 1.
5. Save the modified <code>config.txt</code> file.
6. You have now set up RiiTag. You can try loading any game now to see if it works correctly.


- Emulators

1. Make sure <code>Show Current Game</code> on Discord is turned on in preferences.
2. Make sure your Discord client is open.
3. Play a game and RiiTag will automatically update your tag when you play a game.

Wii U setup instructions

What do you need:

a homebrewed wii u with the aroma environment installed, if you dont have it, homebrew it following [this](https://wiiu.hacks.guide/#/aroma/getting-started) guide, if you dont have a wii u, scroll up

the latest version of the [UTag](https://github.com/RiiConnect24/UTag) aroma plugin

website instructions

1. Go to the [RiiTag](https://tag.rc24.xyz) website.
2. Click Log In and log in with your Discord account.
3. A dialog will pop up asking you if you want to authorize RiiConnect24 Login with Discord. Click Authorize.
4. Click Edit Your Tag and customize it to how you like. You can add a background, overlay, flag, nickname, Wii Number, and manually enter in games to show on your tag (not needed if you’re using a USB Loader).
5. Click Show Key and make note of the key shown. This will be used later on in this guide.
6. Click Submit to save your changes.

sd card setup

1. Go to <code>/wiiu/environments/aroma/plugins</code> and put the <code>UTag.wps</code> file in there
2. Go to <code>/wiiu/</code>
3. Create a text file named <code>utag.txt</code> (dont use windows notepad, i reccomend notepad++)
4. Paste the key in the text file

now you can try a game to see if it works

all titles (except applets such as nintendo tvii) are counted, system apps too

RiiTag on 3DS

what you need

a non-banned from nintendo network 3ds (it's the same even if its not homebrewed) (if you dont have a 3ds scroll up)

a working internet connection

the latest release of [3DS-RPC](https://github.com/MCMi460/3DS-RPC)

setup

1. Go to [this](https://3dsrpc.com) site
2. Click the icon in the top right and then <code>Register</code>
3. Login to your discord account, then allow the app to access your Discord Account (its not malicious)
4. Click <code>[username]'s Consoles</code>
5. Click <code>Register Friend Code</code>
6. Enter your 3DS friend code, and add the prompted friend code to your friends list
7. Now, Unzip the 3DS-RPC zip, and open the executable file
   - if it says <code>PC protected from Windows</code>, ~~its totally a windows moment~~ click <code>More info</code> and then <code>Run anyway</code>
8. Enter your 3DS friend code in there too and click continue
9. Now keep the app open and try playing a game
    - it can take a while to update

nintendo switch setup guide

wip (rip)
