## The game does not run at all (no window) when the modding framework is installed and active
Make sure you have installed [Microsoft's Visual C++ for x86](https://aka.ms/vs/17/release/vc_redist.x86.exe).

Does the issue persists? Try running the game from the command line using:
```cmd
"Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
```
If that doesn't report any warnings or errors, please get in touch on GitHub or on [the Discord server](https://discord.gg/P9dkF38Q2t)!

## The game reports errors on launch
If they are about "AOB" then you are likely running an unsupported version.

The patch should work for most crusader versions, but only v1.41 and v1.41.1 (Latin languages) are officially supported. If you encounter an error using a different version, you can upgrade to 1.41 for free using Firefly’s [Crusader HD Patch](http://www.strongholdcrusaderhd.com/patch.html) or get the game on Steam.

To change the language of your Steam game, follow the steps at the bottom of this page: https://help.steampowered.com/en/faqs/view/4984-C127-121D-B3F2

## Why is my favorite extension not working?
Make sure your favorite extension is as high as possible in the active extension list.

The reason is that the list of active extensions in the GUI is resolved into a final config in a bottom-up fashion.
Therefore, extensions higher in the list override the configuration of extensions lower in the list.

## What is the difference between "AI" and "AI applied"?
In UCP3, content and configuration can be separated.
The AI extensions (without the Applied suffix) supply the new AI files (content).
The AI extensions named "Applied" apply the new AI configuration into AI slots (e.g. a new Rat AI overriding the old Rat AI).

If you want to tinker yourself with the AI files (e.g. place a new Rat AI into the Snake AI slot so two different Rats can compete), then you only need to activate the content extensions (without "Applied").

## Other issues
Please get in touch on GitHub or on [the Discord server](https://discord.gg/P9dkF38Q2t)!
