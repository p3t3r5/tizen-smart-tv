# tizen-smart-tv
Vorinstalliere Apps mit Tizen CLI auf einem SmartTV deinstallieren

## Tizen CLI installieren
 - Tizen Studio 4.1 with CLI(command line interface) installer herunterladen und installieren

## TV Extensions installieren
 - Package Manager öffnen (C:\tizen-cli\package-manage\package-manager.exe)
 - Extension installieren (Extension CDK > Extras > TV Extensions > TV Extensions > Web app development)

## TV Verbinden
 - Device Manager öffnen (C:\tizen-cli\tools\device-manager\bin\device-manager.exe)
 - TV über Remote Device Manager hinzufügen (kann man auch scanen lassen)

## AppID rausfinden
 - Installed web app list
 - ID kopieren (App ID - Tizen)

## App deinstallieren
 - CMD öffnen und zum Ordner gehen: C:\tizen-cli\tools\ide\bin
 - Befehl mit kopiertem AppID ausfüren: tizen.bat uninstall -p <AppID>

