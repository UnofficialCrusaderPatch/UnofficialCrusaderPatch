## La interfaz de UCP3 no se inicia (se cierra tras 1 segundo)
Asegúrate de haber instalado el [entorno de ejecución de webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/).  
Si eso no resuelve el problema, prueba a reparar el entorno de ejecución de webview2 desde tu lista de [aplicaciones instaladas](https://support.microsoft.com/es-es/windows/reparar-aplicaciones-y-programas-en-windows-e90eefe4-d0a2-7c1b-dd59-949a9030f317).
Si eso tampoco funciona, puedes probar [esto](https://superuser.com/a/1751710).

## El juego no se inicia (no aparece ninguna ventana) al usar el framework de mods

1. Asegúrate de haber instalado [esta versión de Microsoft Visual C++ para x86](https://aka.ms/vs/17/release/vc_redist.x86.exe).

2. ¿Sigues teniendo problemas? Intenta ejecutar el juego desde la línea de comandos. Usa este comando:
    +++cmd
    "Stronghold Crusader.exe" --ucp-console --ucp-verbosity 10 --ucp-console-verbosity 10
    +++

3. Si esto no muestra ninguna advertencia o error, ¡contáctanos en GitHub o únete a [nuestro servidor de Discord](https://discord.gg/P9dkF38Q2t)!

---

## El juego muestra errores al iniciarse

Si los errores mencionan **«AOB»**, probablemente estés usando una versión del juego no compatible.

- El parche funciona oficialmente con las versiones **1.41** y **1.41.1** (para idiomas latinos).
- Si tienes una versión diferente, puedes actualizar a la 1.41 gratis usando el [parche HD de Crusader](http://www.strongholdcrusaderhd.com/patch.html) de Firefly, o comprar el juego en Steam.

### Cómo cambiar el idioma del juego en Steam
Sigue las instrucciones que encontrarás al final de [esta página de Steam](https://help.steampowered.com/es/faqs/view/4984-C127-121D-B3F2).

---

## ¿Por qué mi extensión favorita no funciona?

Asegúrate de que tu extensión favorita esté en la **parte superior** de la lista de extensiones activas.

- **¿Por qué?** Las extensiones se aplican de abajo hacia arriba en la lista.
- Las extensiones que están más arriba en la lista **sobrescriben** a las que están más abajo.

---

## ¿Cuál es la diferencia entre «IA» e «IA aplicada»?

- Las **extensiones de IA** (sin «Aplicada») añaden nuevos archivos de IA (contenido).
- Las extensiones de **«IA Aplicada»** aplican la nueva configuración de IA a los espacios de los señores.
   Ejemplo: una nueva IA para La Rata que reemplaza a la antigua.

### ¿Quieres personalizar los archivos de IA tú mismo?
Si solo necesitas el nuevo contenido de IA, activa las **extensiones de IA** (sin «Aplicada»).
Por ejemplo, podrías colocar una nueva IA de La Rata en el espacio de La Serpiente para que dos señores Rata compitan entre sí.

---

## La Senda de Guerra crashea el juego
Echa un vistazo a [esto](https://steamcommunity.com/app/40970/discussions/0/1777135944135270096/)

## Otros problemas

Si tienes otros problemas, ¡no dudes en contactarnos en GitHub o unirte a [nuestro servidor de Discord](https://discord.gg/P9dkF38Q2t)!