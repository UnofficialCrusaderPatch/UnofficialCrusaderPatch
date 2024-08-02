# Unofficial Crusader Patch 3  [![UCP_Official](https://discordapp.com/api/guilds/426318193603117057/widget.png?style=shield)](https://discord.gg/N4UVjZBRXU)
**UCP 3.0 has been released! Get it [here](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch/releases)!** :tada:

<img src="https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch-new/assets/4720007/2ff171cd-ef67-499b-9452-e8ddd49198f6" width="600" />

## About the UCP

This project is an unofficial patcher for [Firefly Studio's](https://fireflyworlds.com/) game [Stronghold Crusader 1](https://store.steampowered.com/app/40970/Stronghold_Crusader_HD/). It features a framework to apply community bug-fixes, rebalancing unit stats, and quality-of-life changes, as well as to provide new content such as maps and AI. To apply this patch you need to have Stronghold Crusader installed, the setup does not include any files created by FireFly Studios, but instead edits them or adds community-made files. Further information can be found on our official [website](https://unofficialcrusaderpatch.github.io/).

##### UCP Legacy
Are you looking for the previous version of the patch (UCP2)? That repo has moved to [here](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch2/). Don't worry, we are still reading and considering all reported issues with the previous version and suggestions for features and improvements.

## Installation

To install the patch we recommend to download the [GUI](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch/releases).  
Installation is done in two parts, first we install the GUI, then from the GUI, we install the new UCP3 modding framework.

1. Download and run the GUI installer.
2. Keep the recommended folder selected for installation (i.e., AppData\Local). If you run into issues, check the FAQ.
3. When installation is finished, run the GUI.
4. In the GUI, select your Stronghold Crusader 1 game folder.
5. Then, press the button to install the latest version of the modding framework to this game folder.
6. To get you started, it is recommended to activate the UCP2-legacy-defaults extension which configures recommended settings you might be familiar with from UCP 2.
7. Hit the Apply button to save the configuration to disk.
8. Launch the game by going to the Launch tab and clicking an icon. You can also launch the game outside of the GUI by launching the original .exe file, or launch it via Steam.
9. Enjoy!

## FAQ (and Frequently Encountered Issues)
### 1. GUI does not run
Make sure you have installed [Webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/).

### 2. The game reports errors on launch
If they are about "AOB" then you are likely running an unsupported version.

The patch should work for most crusader versions, but only v1.41 and v1.41.1 (Latin languages) are officially supported. If you encounter an error using a different version, you can upgrade to 1.41 for free using Firefly’s [Crusader HD Patch](http://www.strongholdcrusaderhd.com/patch.html) or get the game on Steam.

### 3. The game does not run at all (no window) when the modding framework is installed
Make sure you have installed [Microsoft's Visual C++ for x86](https://aka.ms/vs/17/release/vc_redist.x86.exe).

Does the issue persists? Try running the game from the command line using:
```cmd
"Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
```
If that doesn't report any warnings or errors, please get in touch here on GitHub or on the Discord server!

### 4. Why is my favorite extension not working?
Make sure your favorite extension is as high as possible in the active extension list.

The reason is that the list of active extensions in the GUI is resolved into a final config in a bottom-up fashion.
Therefore, extensions higher in the list override the configuration of extensions lower in the list.

### 5. What is the difference between "AI" and "AI applied"?
In UCP3, content and configuration can be separated.
The AI extensions (without the Applied suffix) supply the new AI files (content).
The AI extensions named "Applied" apply the new AI configuration into AI slots (e.g. a new Rat AI overriding the old Rat AI).

If you want to tinker yourself with the AI files (e.g. place a new Rat AI into the Snake AI slot so two different Rats can compete), then you only need to activate the content extensions (without "Applied").

## Wiki
There is a wiki here specifically for the modding framework: https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch3/wiki

#### Glossary of important terms
- _Frontend_   
  GUI aka the graphical user interface through which you can customize your configuration.
- _Framework_   
  UCP3 aka The modding framework
- _Extensions_   
  Modifications to the game code and content are provided through extensions. Modules are for game code modifications and new features, plugins carry content and configurations (maps, AI, gameplay setups).

## Issues and Suggestions

If you have suggestions, you are welcome to post new ideas or discuss already existing ones in the [issues section](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch/issues). It would be great if you could follow these guidelines:

- try to only post one idea per issue to help us keep an overview
- try to check if your suggestion already has a topic and join that discussion instead of creating a new one
- keep the tone nice and civil  

Furthermore you can join our [Discord Server](https://discord.gg/N4UVjZBRXU) for quick help and feedback.

## Contributing
If you want to contribute translations, get in touch on our [Discord Server](https://discord.gg/N4UVjZBRXU) or get started [here](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch3)

If you want to contribute modifications to the user interface, you can contribute to the [GUI](https://github.com/UnofficialCrusaderPatch/UCP3-GUI).

If you want to contribute modifications to the game, you can contribute to [UCP3](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch3).

If you want to contribute content for the game, you can create and share your own plugin extensions. Note, that it is planned to automate and integrate the process of sharing your content within the GUI itself, for that make sure you follow the plugin structure.

Are you considering to contribute? Join our [Discord Server](https://discord.gg/N4UVjZBRXU) for help.

## The team behind the UCP

### Creators of the UCP 3 framework
[Gynt](https://github.com/gynt)  
[TheRedDaemon](https://github.com/thereddaemon)  
[Corax](https://github.com/Corax34)  
[Le spec](https://github.com/LeSpec)  

### Creators of the GUI
[Gynt](https://github.com/gynt)  
[TheRedDaemon](https://github.com/thereddaemon)  
[Krarilotus (YouTube)](https://www.youtube.com/channel/UCMXHqa2vmclSoSkuCu_q5rw)  
[Monsterfisch](https://github.com/Monsterfisch)  

### Developers
[Gynt](https://github.com/gynt)  
[TheRedDaemon](https://github.com/thereddaemon)  
[Le spec](https://github.com/LeSpec)  
[Corax](https://github.com/Corax34)  
[LordHansCapon](https://github.com/LordHansCapon)  
[J-T-de](https://github.com/J-T-de)  
[Chaf1812](https://github.com/Chaf1812)  
[np123](https://github.com/patel-nikhil)  
[Krarilotus (YouTube)](https://www.youtube.com/channel/UCMXHqa2vmclSoSkuCu_q5rw)  
[Monsterfisch](https://github.com/Monsterfisch)  

### Translators
[Lutel (YouTube)](https://www.youtube.com/user/MrLutel05) (Polish)  
[Lolasik011](https://github.com/Lolasik011) (Russian)  
[Skysouls (e-mail)](mailto:theskysoul@vip.qq.com) (Chinese)  
[Liegav (YouTube)](https://www.youtube.com/channel/UCFqQMKfYgGb7iFKJagQl_wA) (Hungarian)

### Creator of the original UCP
[Sh0wdown](https://github.com/Sh0wdown)  

### Community Management
[Kimberly Azula](https://github.com/ByBurton/)  
[Krarilotus (YouTube)](https://www.youtube.com/channel/UCMXHqa2vmclSoSkuCu_q5rw)

### Content Creators   
[Evrey](https://github.com/Evrey) (aiv)  
[Tatha](https://www.youtube.com/channel/UC4BrhBzHp1ymnczlkdKcSkg) (aiv,aic)  
[PitchNeeded](https://github.com/PitchNeeded) (aiv)  
[Xander10alpha](https://github.com/Xander10alpha) (aic)  
[Krarilotus (YouTube)](https://www.youtube.com/channel/UCMXHqa2vmclSoSkuCu_q5rw)

### Special thanks of course go to  
[Firefly Studios](https://fireflyworlds.com/) for the creation of the Stronghold series  

And many more  
