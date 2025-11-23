# Valheim Mods
Dieses Repository enthält die gesammelten Mods und Tools, die wir für unseren gemeinsamen Valheim Server verwenden. Ziel ist es, die Mod-Installation und Verwaltung zu vereinfachen, damit alle Spieler dieselbe modifizierte Spielumgebung nutzen können.

## Vorraussetzungen
### BepInEx
BepInEx ist ein kleines Programm, das es ermöglicht, Mods (Erweiterungen) für Valheim zu nutzen. Ohne BepInEx funktionieren die meisten Mods nicht. Die Installation ist ganz einfach und dauert nur wenige Minuten.

#### Installation
Bitte benutze die hier zur Verfügung gestellten Versionen. Damit alles funktioniert müssen alle die selbe Version haben wie die, die auf dem Server installiert ist.

##### Windows
Öffne die [ZipDatei](./files/BepinEx/Windows/BepInEx_win_x64_5.4.23.4.zip) und entpacke alle Dateien in einen neuen Ordner auf deinem Desktop. 

Öffne deinen Valheim-Installationsordner (normalerweise: **Steam\steamapps\common\Valheim**). Kopiere alle entpackten Dateien aus dem BepInEx-Ordner direkt in diesen Valheim-Ordner. Es kann sein, dass du gefragt wirst, ob du Dateien ersetzen möchtest – bestätige das einfach.

Du kannst deine Valheim Installation auch über Steam finden. Gehe dazu in deiner Steam-Bibliothek auf Valheim, klicke auf das Zahnrad, dann auf "**Verwalten**" und dann auf "**Lokale Dateien durchsuchen**". Du solltest jetzt in dem Ordner sein wo deine lokale Valheim Installation liegt. Dort müssen die BepInEx Dateien eingefügt werden.
##### MacOs
Öffne die [ZipDatei](./files/BepinEx/MacOs/BepInEx_macos_x64_5.4.23.4.zip) und entpacke alle Dateien in einen neuen Ordner auf deinem Schreibtisch. 

Öffne deinen Valheim-Installationsordner (normalerweise: **/Users/USERNAME/Library/Application Support/Steam/steamapps/common/Valheim**). Kopiere alle entpackten Dateien aus dem BepInEx-Ordner direkt in diesen Valheim-Ordner. Es kann sein, dass du gefragt wirst, ob du Dateien ersetzen möchtest – bestätige das einfach.

Du kannst deine Valheim Installation auch über Steam finden. Gehe dazu in deiner Steam-Bibliothek auf Valheim, klicke auf das Zahnrad, dann auf "**Verwalten**" und dann auf "**Lokale Dateien durchsuchen**". Du solltest jetzt in dem Ordner sein wo deine lokale Valheim Installation liegt. Dort müssen die BepInEx Dateien eingefügt werden.

#### Vor dem ersten Start
In Steam muss das Startscript in die Startoptionen eingetragen werden. Dazu kann wieder über das Zahnrad auf die "**Eigenschaften**" geklickt werden. Unter "**Allgemein**" findet man den Bereich "**Startoptionen**". Dort muss folgendes eingetragen werden:

**Windows:**
https://docs.bepinex.dev/articles/user_guide/installation/index.html?tabs=tabid-win müsst ihr selber raus finden ich hab kein Windows

**MacOS:**
````
"PFAD_WO_IHR_DAS_BEP_IN_EX_ZEUG_HINKOPIERT_HABT/run_bepinex.sh" %command%
````
Unter MacOs ist es ggf. notwendig die Datei ausführbar zu machen, dass kann im Terminal wie folgt gemacht werden:

````
chmod u+x run_bepinex.sh
````

#### Erster Start
Nach dem ihr die Anleitung bis hierher verfolgt habt dürft ihr jetzt Valheim das erste mal starten. Nach dem Start bitte direkt wieder beenden und schauen ob er im Installationspfad neue Ordner angelegt hat. 
Es sollten im Ordner "**BepInEx**" jetzt die folgenden Ordner existieren:
- cache
- config
- core
- patchers
- plugins

Sollte das nicht der Fall sein ist irgendwas schief gelaufen und du solltest nicht mit Computern arbeiten, sondern lieber stricken oder sowas versuchen.