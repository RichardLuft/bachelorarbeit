# Bachelorarbeit - Beispielaufgaben
Dieses Projekt dient zur Veröffentlichung meiner Beispielaufgaben für die Bachelorarbeit

# Info
- Die Beispielaufgaben wurden mit JDK 8 implementiert 
- Zum Ausführen wird aktuell noch das Github-Projekt Beanfabrics-FX benötigt,
  zu finden unter https://github.com/mkarneim/beanfabrics-fx.
- Das Projekt muss über `git clone` heruntergeladen werden
- Dann über den Befehl `gradle eclipse` für eclipse vorbereitet werden
- Oder über den Befehl `gradle clean build` von gradle gebaut werden, dabei wird ein jar
unter `build\libs\beanfabrics-fx-LOCAL-SNAPSHOT.jar` generiert.
- Dieses muss dann im Projekt eingebunden werden

# Einrichtung
- `git clone` des Projektes
- Die Datei `build.gradle` bearbeiten und den Punkt `beanfabrics_fx_local` mit dem Verzeichnis des `beanfabrics-fx-LOCAL-SNAPSHOT.jar` austauschen.
