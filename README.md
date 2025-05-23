# Unofficial Crusader Patch 3 ![Github All Releases](https://img.shields.io/github/downloads/UnofficialCrusaderPatch/UnofficialCrusaderPatch3/total.svg)  [![UCP_Official](https://discordapp.com/api/guilds/426318193603117057/widget.png?style=shield)](https://discord.gg/P9dkF38Q2t)

Announcement: Our Discord server got hacked and destroyed by a malicious intruder! Everyone was banned, but this ban has since been lifted. [Join our Discord server](https://discord.gg/P9dkF38Q2t)!

**UCP 3 has been released! Get it [here](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch/releases)!** :tada:

<img src="https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch-new/assets/4720007/2ff171cd-ef67-499b-9452-e8ddd49198f6" width="600" />

## About the UCP

This project is an unofficial patcher for [Firefly Studio's](https://fireflyworlds.com/) game [Stronghold Crusader 1](https://store.steampowered.com/app/40970/Stronghold_Crusader_HD/). It features a framework to apply community bug-fixes, rebalancing unit stats, and quality-of-life changes, as well as to provide new content such as maps and AI. To apply this patch you need to have Stronghold Crusader installed, the setup does not include any files created by FireFly Studios, but instead edits them or adds community-made files. Further information can be found on our official [website](https://unofficialcrusaderpatch.github.io/).

##### UCP Legacy
Are you looking for the previous version of the patch (UCP2)? That repo has moved to [here](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch2/). Don't worry, we are still reading and considering all reported issues with the previous version and suggestions for features and improvements.

## Getting Started

To install the patch we recommend to download the [GUI](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch/releases).  
Installation is done in two parts, first we install the GUI, then from the GUI, we install the new UCP3 modding framework.

1. Download the latest UCP3 frontend which functions as an installation manager and mod marketplace.
2. Install the UCP3-GUI (the frontend) to the default location and run it. The UCP3-GUI is known to work on Windows 10 and higher. For other windows versions it is important to install the webview2 runtime with the evergreen installer.
3. The GUI features several tabs. The Overview tab is the one we will use first. Click the browse field and select the folder on which your installation of Stronghold Crusader is installed. If you got the game on Steam, you can use the Steam app to find your installation.
4. If you installation is in Program Files (x86), it might be that your windows user doesnt have sufficient rights to place and modify files in the game directory. A solution is to copy the game folder to your Windows User folder. After copying, make sure to select the new folder in the GUI.
5. In the Overview tab click the Install button which will download the latest UCP software (the "framework"), and it will install itself to the configured game directory. The GUI may report that the ucp2 is still installed which you need to uninstall first. Or reinstall the game. In case you have the game on steam you can use "verify integrity of game files" to uninstall ucp2.
6. When installation finishes, the framework is automatically active by default. In the Content tab there is a list of activated extensions and in the Launch tab there is the option to Launch the game. Lets launch the game to see if it works.
7. If the game does not launch, you can consult the troubleshooting menu in the GUI.
8. Visit the Store tab to install extra content. In the Content tab, activate content one by one. Higher listed content in the active extensions list can override lower listed ones if they configure the same option. Click on listed extensions to see what they do and/or provide.
9. Go to the Launch tab to launch the game, use Steam to launch the game, or run the game manually via the .exe
10. Have fun!

## FAQ (and Frequently Encountered Issues)
### 1. GUI does not run
Make sure you have installed [Webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/).  
If you have installed it, make sure it is not broken, this can happen for some reason we don't know.
First, run this command to make sure your system files aren't broken.
```cmd
sfc /scannow
```
Then, press the Windows key + I and go to "Apps". Click "Installed apps". Locate "Microsoft Edge WebView2 Runtime" in the list. Click "Modify" and then "Repair".
Try launching Webview2 again. If it is still not working, try uninstalling Webview 2 and [reinstalling](https://developer.microsoft.com/en-us/microsoft-edge/webview2/?form=MA13LH#download-section) it:
```cmd
winget uninstall "Microsoft Edge WebView2 Runtime"
```

If our suggestions are unclear and it is still not working, contact us on Discord!

### 2. The game reports errors on launch
If they are about "AOB" then you are likely running an unsupported version.

The patch should work for most crusader versions, but only v1.41 and v1.41.1 (Latin languages) are officially supported. If you encounter an error using a different version, you can upgrade to 1.41 for free using Firefly’s [Crusader HD Patch](http://www.strongholdcrusaderhd.com/patch.html) or get the game on Steam.

To change the language of your Steam game, follow the steps at the bottom of this page: https://help.steampowered.com/en/faqs/view/4984-C127-121D-B3F2

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

### 6. Will there be a UCP for the Definitive Edition?
Based on the Demo, we conclude that creating a UCP for the DE would mean we have to start over, almost from scratch. We can't develop and test our mods effectively due to technical reasons and the game files we want to mod are much more inaccessible in the DE. We are therefore not developing a UCP for the DE as it stands.

We have reached out to Firefly but as you may know, there will be no collaboration between Firefly and the UCP Team regarding the DE. Firefly states they are committed to make making mods as easy as possible, and while that may be true for the full release, currently the opposite is true for us in the Demo.

We will have to wait and see to what extent making mods for the full release of the DE is feasible. Thus, we are currently not working on a UCP patch for the DE, and if the current situation stays the same in the full release, there will no be UCP for the Definitive Edition. 

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

Furthermore you can join our [Discord Server](https://discord.gg/P9dkF38Q2t) for quick help and feedback.

## Contributing
If you want to contribute translations, get in touch on our [Discord Server](https://discord.gg/P9dkF38Q2t) or get started [here](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch3)

If you want to contribute modifications to the user interface, you can contribute to the [GUI](https://github.com/UnofficialCrusaderPatch/UCP3-GUI).

If you want to contribute modifications to the game, you can contribute to [UCP3](https://github.com/UnofficialCrusaderPatch/UnofficialCrusaderPatch3).

If you want to contribute content for the game, you can create and share your own plugin extensions. Note, that it is planned to automate and integrate the process of sharing your content within the GUI itself, for that make sure you follow the plugin structure.

Are you considering to contribute? Join our [Discord Server](https://discord.gg/P9dkF38Q2t) for help.

## Credits: The team behind the UCP

### Creators of the UCP
Sh0wdown  
Gynt (UCP3)  

### Project Management
Krarilotus  
Kimberly Azula  

### Developers
Altaruss'28  
atlan_ace  
Chaf1812  
CIO  
Corax  
J-T-de  
LeSpec  
LordHansCapon  
Monsterfisch_  
np123  
TheRedDaemon  

### Content Creators
CrusaderPilaw  
Evrey  
Hacksülze  
Nevikov  
PitchNeeded  
Schlossgespenst  
Tatha  
Xander10alpha  

### Game Experts
GRhin  
Heroesflorian  
PodeCaradox  

### Community Pillars
CyberWizard  
Udwin  
xCara  

### Translators
Chinese: Skysouls  
French: Alix Barreaux  
Hungarian: Liegav, Tumblra  
Persian: arabianknight2641  
Polish: Lutel  
Russian: Lolasik011  

### Special thanks of course go to  
[Firefly Studios](https://fireflyworlds.com/) for the creation of the Stronghold series  

And many more  
