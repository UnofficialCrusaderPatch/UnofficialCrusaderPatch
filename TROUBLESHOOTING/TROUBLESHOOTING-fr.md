## L'interface graphique (GUI) de l'UCP3 ne se lance pas (elle se ferme après 1 seconde)
Assurez-vous d'avoir installé le [runtime webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/).  
Si cela ne résout pas le problème, essayez de réparer le runtime webview2 dans votre liste d'[applications installées](https://support.microsoft.com/en-us/windows/repair-apps-and-programs-in-windows-e90eefe4-d0a2-7c1b-dd59-949a9030f317).
Si cela ne fonctionne toujours pas, vous pouvez essayer [cette solution](https://superuser.com/a/1751710).

---

## Le jeu ne se lance pas du tout (aucune fenêtre n'apparaît) en utilisant le framework de modding

1.  Vérifiez que vous avez bien installé [cette version de Microsoft Visual C++ pour x86](https://aka.ms/vs/17/release/vc_redist.x86.exe).

2.  Toujours des problèmes ? Essayez de lancer le jeu depuis l'invite de commandes. Utilisez cette commande :
    +++cmd
    "Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
    +++

3.  Si aucune erreur ou avertissement n'apparaît, veuillez nous contacter sur GitHub ou rejoindre [notre serveur Discord](https://discord.gg/P9dkF38Q2t) !

---

## Le jeu affiche des erreurs au lancement

Si les erreurs mentionnent **« AOB »**, vous utilisez probablement une version du jeu non compatible.

-   Le patch fonctionne officiellement avec les **versions 1.41** et **1.41.1** (langues latines).
-   Si vous possédez une version différente, vous pouvez mettre à jour gratuitement vers la version 1.41 en utilisant le [Patch HD de Crusader](http://www.strongholdcrusaderhd.com/patch.html) de Firefly, ou acheter le jeu sur Steam.

### Comment changer la langue du jeu sur Steam
Suivez les instructions en bas de [cette page Steam](https://help.steampowered.com/en/faqs/view/4984-C127-121D-B3F2).

---

## Pourquoi mon extension favorite ne fonctionne-t-elle pas ?

Assurez-vous que votre extension favorite est **tout en haut** de la liste des extensions actives.

-   **Pourquoi ?** Les extensions sont appliquées de bas en haut dans la liste.
-   Les extensions plus hautes dans la liste **écrasent** celles qui sont plus basses.

---

## Quelle est la différence entre « IA » et « IA appliquée » ?

-   Les **extensions d'IA** (sans la mention « Appliquée ») ajoutent de nouveaux fichiers d'IA (du contenu).
-   Les **extensions « IA Appliquée »** appliquent la nouvelle configuration d'IA aux seigneurs du jeu.
    Exemple : Une nouvelle IA du Rat remplaçant l'ancienne IA du Rat.

### Vous voulez personnaliser vous-même les fichiers d'IA ?
Si vous n'avez besoin que du nouveau contenu d'IA, activez les **extensions d'IA** (sans la mention « Appliquée »).
Par exemple, vous pourriez placer une nouvelle IA du Rat à l'emplacement de l'IA du Serpent pour faire s'affronter deux Rats.

---

## La Piste du Trésor de Guerre fait planter le jeu
Consultez [ce lien](https://steamcommunity.com/app/40970/discussions/0/1777135944135270096/).

## Autres problèmes

Si vous rencontrez d'autres problèmes, n'hésitez pas à nous contacter sur GitHub ou à rejoindre [notre serveur Discord](https://discord.gg/P9dkF38Q2t) !