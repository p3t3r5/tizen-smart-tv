Vorinstalliere Apps mit Tizen CLI auf einem SmartTV deinstallieren

## TV in Development Mode wechseln
 - https://developer.samsung.com/smarttv/develop/getting-started/using-sdk/tv-device.html (1. Schritt. Benutze 123-Taste)

## Tizen CLI installieren
 - Tizen Studio x.x with CLI herunterladen und installieren: https://developer.tizen.org/ko/development/tizen-studio/download

## TV Extensions installieren
 - Package Manager öffnen: **C:\tizen-cli\package-manage\package-manager.exe**
 - Extension installieren: **Extension CDK > Extras > TV Extensions x.x > Web app development**

## TV Verbinden
 - Device Manager öffnen: **C:\tizen-cli\tools\device-manager\bin\device-manager.exe**
 - Gerät über Remote Device Manager hinzufügen (kann man auch scanen lassen)

## AppID rausfinden
 - Installed web app list (rechte Mausklick auf dem Gerät )
 - App ID kopieren (App ID - Tizen, z.Bsp.: AGJFlEOkBo.emanual)

## App deinstallieren
 - CMD öffnen und zum Ordner gehen: **C:\tizen-cli\tools\ide\bin**
 - Befehl mit kopiertem AppID ausfüren: **tizen uninstall -p [AppID]**

