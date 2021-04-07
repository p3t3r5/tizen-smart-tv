# Vorinstalliere Apps mit Tizen CLI auf einem SmartTV deinstallieren

## TV in Development Mode umschalten
 - Enable Developer Mode on the TV: https://developer.samsung.com/smarttv/develop/getting-started/using-sdk/tv-device.html
 - Benutze 123-Taste auf einer Universal Fernbedienung

## Tizen CLI installieren
 - **Tizen Studio x.x with CLI** herunterladen und installieren: https://developer.tizen.org/ko/development/tizen-studio/download

## TV Extensions installieren
 - Package Manager öffnen: **C:\tizen-studio\package-manager\package-manager.exe**
 - Extension installieren: **Extension SDK > Extras > TV Extensions x.x > Web app development**

## TV Verbinden
 - Device Manager öffnen: **C:\tizen-studio\tools\device-manager\bin\device-manager.exe**
 - Connect the TV to the SDK: https://developer.samsung.com/smarttv/develop/getting-started/using-sdk/tv-device.html

## Installierte App-ID rausfinden
 - Rechte Mausklick auf dem Device: **Installed web app list**
 - App-ID finden und kopieren (z.Bsp.: **AGJFlEOkBo.emanual**)

## SmartTV App deinstallieren
 - CMD (Konsole) öffnen und zum Ordner gehen: **C:\tizen-studio\tools\ide\bin**
 - Befehl mit entsprechender App-ID ausfüren: **tizen uninstall -p APP-ID**

