## Die UCP3-Benutzeroberfläche startet nicht (schließt sich nach 1 Sekunde)
Stellt sicher, dass Ihr die [WebView2-Runtime](https://developer.microsoft.com/de-de/microsoft-edge/webview2/) installiert habt.  
Sollte das Problem weiterhin bestehen, versucht, die WebView2-Runtime in Eurer Liste der [installierten Apps](https://support.microsoft.com/de-de/windows/reparieren-von-apps-und-programmen-in-windows-e90eefe4-d0a2-7c1b-dd59-949a9030f317) zu reparieren.
Wenn auch das nicht zum Erfolg führt, könnt Ihr [diesen Lösungsansatz](https://superuser.com/a/1751710) ausprobieren.

## Das Spiel startet überhaupt nicht (kein Fenster erscheint), wenn Ihr das Modding-Framework verwendet

1. Stellt sicher, dass Ihr [diese Version von Microsofts Visual C++ für x86](https://aka.ms/vs/17/release/vc_redist.x86.exe) installiert habt.

2. Immer noch Schwierigkeiten? Versucht, das Spiel über die Kommandozeile zu starten. Verwendet diesen Befehl:
    +++cmd
    "Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
    +++

3. Sollten hierbei keine Warnungen oder Fehler angezeigt werden, kontaktiert uns auf GitHub oder tretet [unserem Discord-Server](https://discord.gg/P9dkF38Q2t) bei!

---

## Das Spiel zeigt beim Starten Fehlermeldungen an

Wenn in den Fehlermeldungen **„AOB“** erwähnt wird, verwendet Ihr wahrscheinlich eine nicht unterstützte Spielversion.

- Der Patch funktioniert offiziell mit **Version 1.41** und **1.41.1** (lateinische Sprachversionen).  
- Solltet Ihr eine andere Version besitzen, könnt Ihr kostenlos mit Fireflys [Crusader HD Patch](http://www.strongholdcrusaderhd.com/patch.html) auf die Version 1.41 aufrüsten oder das Spiel auf Steam erwerben.

### So ändert Ihr die Sprache des Spiels auf Steam
Folgt den Anweisungen am Ende [dieser Steam-Seite](https://help.steampowered.com/de/faqs/view/4984-C127-121D-B3F2).

---

## Warum funktioniert meine Lieblingserweiterung nicht?

Stellt sicher, dass Eure Lieblingserweiterung in der Liste der aktiven Erweiterungen **ganz oben** steht.

- **Warum?** Erweiterungen werden in der Liste von unten nach oben angewendet.  
- Erweiterungen, die weiter oben in der Liste stehen, **überschreiben** jene, die weiter unten stehen.

---

## Was ist der Unterschied zwischen „KI“ und „Angewandte KI“?

- **KI-Erweiterungen** (ohne „Angewandt“) fügen neue KI-Dateien (also Inhalte) hinzu.  
- **„Angewandte KI“-Erweiterungen** wenden die neue KI-Konfiguration auf die KI-Plätze an.  
   Beispiel: Eine neue Ratten-KI ersetzt die alte Ratten-KI.

### Ihr wollt die KI-Dateien selbst anpassen?  
Wenn Ihr nur die neuen KI-Inhalte benötigt, aktiviert die **KI-Erweiterungen** (ohne „Angewandt“).  
So könntet Ihr beispielsweise eine neue Ratten-KI auf den Platz der Schlangen-KI setzen, um zwei Ratten gegeneinander antreten zu lassen.

---

## Der Schatzkammer-Marsch bringt das Spiel zum Absturz
Seht Euch [diesen Beitrag](https://steamcommunity.com/app/40970/discussions/0/1777135944135270096/) an.

## Andere Probleme

Solltet Ihr andere Probleme haben, meldet Euch auf GitHub oder tretet [unserem Discord-Server](https://discord.gg/P9dkF38Q2t) bei!