## A UCP3 felülete nem indul el (1 másodperc után bezáródik)
Győződj meg róla, hogy telepítetted a [webview2 futtatókörnyezetet](https://developer.microsoft.com/en-us/microsoft-edge/webview2/).  
Ha ez nem oldja meg a problémát, próbáld meg kijavítani a webview2 futtatókörnyezetet a [telepített alkalmazásaid](https://support.microsoft.com/hu-hu/windows/alkalmaz%C3%A1sok-%C3%A9s-programok-jav%C3%ADt%C3%A1sa-a-windowsban-e90eefe4-d0a2-7c1b-dd59-949a9030f317) listájában.
Ha ez sem működik, megpróbálkozhatsz [ezzel](https://superuser.com/a/1751710).

---

## A játék egyáltalán nem indul el (nincs ablak) a modding keretrendszer használatakor

1. Győződj meg róla, hogy telepítetted a [Microsoft Visual C++ x86-os verzióját](https://aka.ms/vs/17/release/vc_redist.x86.exe).

2. Még mindig gondjaid vannak, hű uram? Próbáld meg a játékot parancssorból futtatni. Használd az alábbi parancsot:
    +++cmd
    "Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
    +++

3. Ha ez nem jelez semmilyen figyelmeztetést vagy hibát, kérjük, vedd fel velünk a kapcsolatot GitHubon, vagy csatlakozz a [Discord szerverünkhöz](https://discord.gg/P9dkF38Q2t)!

---

## A játék hibákat jelez indításkor

Ha a hibaüzenetekben **„AOB”** szerepel, valószínűleg nem támogatott játékverziót használsz.

- A patch hivatalosan az **1.41**-es és az **1.41.1**-es (latin nyelvű) verziókkal működik.  
- Ha más verzióval rendelkezel, ingyenesen frissíthetsz az 1.41-es verzióra a Firefly [Crusader HD Patch](http://www.strongholdcrusaderhd.com/patch.html) segítségével, vagy megvásárolhatod a játékot Steamen.

### Hogyan változtasd meg a játék nyelvét Steamen?
Kövesd az utasításokat [ennek a Steam oldalnak](https://help.steampowered.com/hu/faqs/view/4984-C127-121D-B3F2) az alján.

---

## Miért nem működik a kedvenc kiegészítőm?

Győződj meg róla, hogy a kedvenc kiegészítőd az aktív kiegészítők listájának **tetején** van.

- **Miért?** A kiegészítők a listában alulról felfelé kerülnek alkalmazásra.  
- A listában feljebb lévő kiegészítők **felülírják** az alattuk lévőket.

---

## Mi a különbség az „MI” és az „Alkalmazott MI” között?

- Az **MI kiegészítők** (az „Alkalmazott” szó nélkül) új MI fájlokat (azaz tartalmat) adnak a játékhoz.  
- Az **„Alkalmazott MI” kiegészítők** az új MI viselkedést egy adott MI helyre (slotra) alkalmazzák.  
   Például: egy új Patkány MI lecseréli a régi Patkány MI-t.

### Te magad szabnád testre az MI fájlokat?  
Ha csak az új MI tartalomra van szükséged, aktiváld az **MI kiegészítőket** (az „Alkalmazott” nélkül).  
Így például behelyezhetsz egy új Patkány MI-t a Kígyó helyére, hogy két Patkány küzdjön meg egymással a csatamezőn.

---

## A Keresztes hadjárat (Warchest Trail) lefagyasztja a játékot
Vess egy pillantást [erre](https://steamcommunity.com/app/40970/discussions/0/1777135944135270096/).

## Egyéb problémák

Ha más nehézségekbe ütközöl, keress minket GitHubon, vagy csatlakozz a [Discord szerverünkhöz](https://discord.gg/P9dkF38Q2t)! A kapuink mindig nyitva állnak.