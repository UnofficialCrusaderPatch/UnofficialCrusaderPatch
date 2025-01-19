## The game does not start at all (no window) when using the modding framework

1. Make sure you have installed [this version of Microsoft's Visual C++ for x86](https://aka.ms/vs/17/release/vc_redist.x86.exe).

2. Still having problems? Try running the game from the command line. Use this command:
    ```cmd
    "Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
    ```

3. If this does not show any warnings or errors, please contact us on GitHub or join [our Discord server](https://discord.gg/P9dkF38Q2t)!

---

## The game shows errors when launching

If the errors mention **"AOB"**, you are probably using an unsupported game version.

- The patch officially works with **version 1.41** and **1.41.1** (Latin languages).  
- If you have a different version, you can upgrade to version 1.41 for free using Firefly’s [Crusader HD Patch](http://www.strongholdcrusaderhd.com/patch.html), or buy the game on Steam.

### How to change the game language on Steam
Follow the instructions at the bottom of [this Steam page](https://help.steampowered.com/en/faqs/view/4984-C127-121D-B3F2).

---

## Why is my favorite extension not working?

Make sure your favorite extension is **at the top** of the active extensions list.

- **Why?** Extensions are applied from bottom to top in the list.  
- Extensions higher in the list **override** those lower in the list.

---

## What is the difference between "AI" and "AI applied"?

- **AI extensions** (without "Applied") add new AI files (content).  
- **"AI Applied" extensions** apply the new AI configuration to AI slots.  
   Example: A new Rat AI replacing the old Rat AI.

### Want to customize the AI files yourself?  
If you only need the new AI content, activate the **AI extensions** (without "Applied").  
For example, you could place a new Rat AI into the Snake AI slot to have two Rats compete.

---

## Other issues

If you have other problems, please reach out on GitHub or join [our Discord server](https://discord.gg/P9dkF38Q2t)!
