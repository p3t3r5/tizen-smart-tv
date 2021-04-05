# tizen-smart-tv
Vorinstalliere Apps mit Tizen CLI auf einem SmartTV deinstallieren

## Tizen CLI installieren
 - Tizen Studio x.x with CLI herunterladen und installieren: https://developer.tizen.org/ko/development/tizen-studio/download

## TV Extensions installieren
 - Package Manager öffnen: **C:\tizen-cli\package-manage\package-manager.exe**
 - Extension installieren (Extension CDK > Extras > TV Extensions > TV Extensions > Web app development)

## TV Verbinden
 - Device Manager öffnen: **C:\tizen-cli\tools\device-manager\bin\device-manager.exe**
 - TV über Remote Device Manager hinzufügen (kann man auch scanen lassen)

## AppID rausfinden
 - Installed web app list
 - ID kopieren (App ID - Tizen)

## App deinstallieren
 - CMD öffnen und zum Ordner gehen: **C:\tizen-cli\tools\ide\bin**
 - Befehl mit kopiertem AppID ausfüren: **tizen uninstall -p [AppID]**

