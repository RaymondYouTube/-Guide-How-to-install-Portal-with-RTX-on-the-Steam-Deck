# Guide: How to install Portal with RTX on the Steam Deck
Wanna play Portal with RTX on the Steam Deck? Here's a guide on how to do that.

- Intro

Portal with RTX is a free DLC for all Portal owners developed by Nvidia Lightspeed Studios. Every frame of gameplay is upgraded with stunning full ray tracing, new, hand-crafted hi-res physically based textures, and new, enhanced high-poly models evocative of the originals.

- Install Guide

This guide assumes you already have Portal 1 installed on your Steam Deck. If you don't then you can purchase it from the Steam store.

It also assumes you're using SteamOS on your Steam Deck. SteamOS is based on Linux so you'll be needing Proton for this. For a guide on Portal with RTX on the Steam Deck, make sure your Steam Deck is updated to SteamOS 3.5 or later. It's where it updates the drivers to Mesa 23.1.3 in Gaming mode/Big picture mode.

If you're a Steam Deck Windows user, you don't have to follow some of these steps, but you would still have to tinker with it to get it working.

If you're using Nvidia GeForce Now or Steam Link on the Steam Deck, then you don't have to follow this guide, but for the sole purposes, this guide will primarily focus on getting Portal with RTX playable on the official Steam Deck hardware without the use of cloud streaming or remote play.

Now onto the install guide. On Steam Deck, follow the below steps.

- Steps

1. Make sure you have Portal 1 installed on the Steam Deck. If you don't have it on your library, then purchase the game from Steam and install it right away.
2. Install Portal with RTX onto your Steam Deck. It's available on Steam, so you can download it for free. Note that the game on Steam says "Unsupported" due to Valve still working on adding support for this game on Steam Deck, but it's still playable regardless. I haven't tried it on a Micro SD Card, but just in case, I would recommend installing it onto an SSD.
4. Go to the game's settings and click properties. If you're using Windows, that's good. You don't have to do this step. But for Linux users, follow this step.
5. Use the General tab to go to the launch options to paste or type the following, "RADV_PERFTEST=rt %command% -nogamepadui -windowed", making sure the hyphens and spaces are in the correct positions. It is recommended that you type in "-nogamepadui" to disable the Steam Deck UI, because the Steam Deck UI does not load the RTX Remix assets, and instead it breaks the lighting, makes portals not render correctly, and the camera gets placed within Chell's model such that you can still see it from inside. By default the game uses the Gamepad UI, so use launch options to disable the Gamepad UI and enable ray tracing on the Steam Deck. If you're using Windows, that's good, you don't have to have to follow this step, but if you're Windows and if you still have the Gamepad UI, disable it. As for Linux users, follow this step.
6. Go to the Compatibility tab, select "Force the use of a specific Steam Play compatibility tool", and choose any version of Proton you have. For this case I'm using Proton 8.0-5, but you can use any version of Proton and any GE-Proton version for that matter. If you're using Windows, that's good, you can skip this step. But for Linux users, follow this step.
7. Once that's been done, exit the properties, and go to the controller settings.
8.     Go to Community Layouts. Press X to show all layouts, and select the layout that I created, which is "Portal With RTX - Official Steam Deck layout", with A. And make sure to press X to apply the layout. My Steam username is RaymondGames, and my layout has the Steam input, with 32 hours put into it, with this description "Here is the layout for Portal With RTX on Steam Deck. This uses the controller input."
9. Press the button that has 3 dots on it, to open the quick settings, then go to the performance tab, and set the scaling filter slider to FSR and set the FSR sharpness all the way up to 5.
10. Launch the game.

When the game starts, you get a message that tells you that RTX Remix is loaded. ALT+X is mapped to the Select button (or the View button), and pushing it opens the Nvidia RTX settings.

When you get to the main menu, The framerate heavily drops to 2 frames per second because of how much lighting there is in this version of Portal. So, we'll have to do some extra steps.

10.     Lower the resolution in the options menu. The default resolution is 1280x800, so change it to 768x480 so that it runs smoother. When you do this, make sure it is set to Windowed mode. Not Fullscreen mode, Windowed mode. That's very important to make sure the display is functional.
11. Now exit the options menu and open up the RTX settings. Because we're using a Steam Deck, the upscaler we can only use TAA-U or NIS. Once you chose your preferred upscaler, set the preset to Performance mode so that it runs smoother. On mine, it's NIS, but it's up to you to decide to use TAA-U or NIS.
12. Keep the RTX open, and have your settings set to low, but instead of a low preset, you use a custom preset. You can choose to set it up the way you wanted.
13. Go to developer settings and turn the sharpness all the way down. You do have the option to change Nvidia Reflex from Off to On and even Boost, but I don't think it does anything with the Steam Deck, it's there. But, those are some of your choices.
14. Go to the options menu and enable the gamepad under the mouse tab. So that way it detects the controller input.

Now you'll be able to play Portal with RTX on your Steam Deck. Since the Steam Deck has ray tracing capabilities, Portal with ray tracing now looks like a technical showcase for the Steam Deck. Portal with RTX on Steam Deck is a one phenomenal experience.

- Installing Portal: The Flash Version

If you want to play Portal: The Flash Version with RTX on Steam Deck, follow these steps:

On Steam Deck, follow the below steps in Desktop Mode.

1. Download the Portal: The Flash Version mappack from Mod DB.
2. Extract the Portal: The Flash Version files into a folder you created.
3. Go on Steam, click on the game's settings for Portal with RTX, go to manage, and click on browse local files. Alternatively you can search for the Portal RTX directory in the Dolphin file manager. To do this, make sure you enable "Show hidden files" in the Dolphin file manager. The directory is this: /home/deck/.local/share/Steam/steamapps/common/PortalRTX/portal_rtx/
4. Drag the files into the portal_rtx folder and replace the files if needed. If you want to restore the original files, please make a backup before doing so.
5. Make sure you have Half-Life 2 installed onto your Steam Deck. If you do not have the game in your library, then purchase the game from Steam and install it right away.
6. Then load Portal with RTX, go to Bonus maps and Load the the Mappack from the list.

Now you can play Portal: The Flash Version with RTX on your Steam Deck. An experience that started off as a flash game, now being a mappack can be reimagined with ray tracing.

- Installing Portal: Still Alive

If you want to play Portal: Still Alive with RTX on Steam Deck, follow these steps:

On Steam Deck, follow the below steps in Desktop Mode.

1. Download the Portal: Still Alive mappack from Mod DB. Keep in mind, use the mappack version, not the sourcemod version. Make sure you download the mappack version.
2. Go on Steam, click on the game's settings for Portal with RTX, go to manage, and click on browse local files. Alternatively you can search for the Portal RTX directory in the Dolphin file manager. To do this, make sure you enable "Show hidden files" in the Dolphin file manager. The directory is this: /home/deck/.local/share/Steam/steamapps/common/PortalRTX/portal_rtx/
3. Create a new folder called Portal: Still Alive, then extract the files into a folder you created, and drag that folder into the custom folder. If you don't have a custom folder, create one.
4. Then load Portal with RTX, go to Bonus maps and Load the the Mappack from the list.

Now you can play the bonus maps test chambers from Portal: Still Alive with RTX on your Steam Deck. The Portal: Still Alive bonus maps are based on the maps from the Portal: The Flash Version mappack.

- Installing Moody Aperture RTX (Optional)

Now for this part, this is not mandatory, it's just something to help the game run much more smoother, but it also makes the game very dark. If you want Moody Aperture RTX on Steam Deck, follow these steps:

On Steam Deck, follow the below steps in Desktop Mode.

1. Download the Moody Aperture RTX file from Nexusmods.
2. Go on Steam, click on the game's settings for Portal with RTX, go to manage, and click on browse local files. Alternatively you can search for the Portal RTX directory in the Dolphin file manager. To do this, make sure you enable "Show hidden files" in the Dolphin file manager. The directory is this: /home/deck/.local/share/Steam/steamapps/common/PortalRTX/
3. Extract the RTX config file into the directory. If you want to restore the original file, please make a backup before doing so.

Just remember, with this setup, the game is super dark so you'll have a hard time see where you'll go. If you want to make it brighter, go to the developer settings in the RTX settings. Albedo scale changes how bright all textures are, the default is 1.0.

Done! That's the guide of Portal with RTX on Steam Deck. Enjoy playing Portal on the Steam Deck with ray tracing.
