# Vorinstalliere Apps mit Tizen CLI auf einem SmartTV deinstallieren

## TV in Development Mode umschalten
 - Enable Developer Mode on the TV: https://developer.samsung.com/smarttv/develop/getting-started/using-sdk/tv-device.html
 - Benutze 123-Taste auf einer universale Fernbedienung

## Tizen CLI installieren
 - Tizen Studio x.x with CLI herunterladen und installieren: https://developer.tizen.org/ko/development/tizen-studio/download

## TV Extensions installieren
 - Package Manager öffnen: **C:\tizen-cli\package-manage\package-manager.exe**
 - Extension installieren: **Extension CDK > Extras > TV Extensions x.x > Web app development**

## TV Verbinden
 - Device Manager öffnen: **C:\tizen-cli\tools\device-manager\bin\device-manager.exe**
 - Connect the TV to the SDK: https://developer.samsung.com/smarttv/develop/getting-started/using-sdk/tv-device.html

## Installierte AppID rausfinden
 - Rechte Mausklick auf dem Gerät: **Menü > Installed web app list**
 - App ID aus dem Fenster kopieren (App ID - Tizen, z.Bsp.: **AGJFlEOkBo.emanual**)

## App deinstallieren
 - CMD öffnen und zum Ordner gehen: **C:\tizen-cli\tools\ide\bin**
 - Befehl mit kopiertem AppID ausfüren: **tizen uninstall -p [AppID]**

