---
license: Licensed to the Apache Software Foundation (ASF) under one
         or more contributor license agreements.  See the NOTICE file
         distributed with this work for additional information
         regarding copyright ownership.  The ASF licenses this file
         to you under the Apache License, Version 2.0 (the
         "License"); you may not use this file except in compliance
         with the License.  You may obtain a copy of the License at

           http://www.apache.org/licenses/LICENSE-2.0

         Unless required by applicable law or agreed to in writing,
         software distributed under the License is distributed on an
         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
         KIND, either express or implied.  See the License for the
         specific language governing permissions and limitations
         under the License.
---

# Plugin APIs

Cordova mit einen minimalen Satz von APIs und Projekte hinzufügen, was zusätzliche APIs, die sie durch Plugins erfordern.

Sie können alle vorhandenen Plugins (einschließlich Drittanbieter Plug-ins) mithilfe der [Plugin Registry][1] durchsuchen.

 [1]: http://plugins.cordova.io/

Der traditionelle Kern Cordova Plugins sind wie folgt:

*   [Batteriestatus][2]
    
    > Überwachen Sie den Status des Geräts Batterie.

*   [Kamera][3]
    
    > Ein Foto mit der Gerätekamera zu erfassen.

*   [Konsole][4]
    
    > Fügen Sie zusätzlich die Möglichkeit, zu console.log().

*   [Kontakte][5]
    
    > Arbeiten Sie mit der Geräte-Kontaktdatenbank.

*   [Gerät][6]
    
    > Gerät bestimmte Informationen zu sammeln.

*   [Bewegung Gerät (Beschleunigungssensor)][7]
    
    > Tippen Sie in das Gerät Weg-und/oder Geschwindigkeitsgeber.

*   [Orientierung des Geräts (Kompass)][8]
    
    > Erhalten Sie die Richtung, die das Gerät verweist.

*   [Dialoge][9]
    
    > Visuelle Gerätebenachrichtigungen.

*   [Dateisystem][10]
    
    > Haken Sie in native Dateisystem durch JavaScript.

*   [File-Transfer][11]
    
    > Haken Sie in native Dateisystem durch JavaScript.

*   [Geolocation][12]
    
    > Machen Sie Ihre Anwendung Lage bewusst.

*   [Globalisierung][13]
    
    > Aktivieren Sie die Darstellung von Objekten, die spezifisch für ein Gebietsschema.

*   [InAppBrowser][14]
    
    > URLs in einer anderen in-app Browserinstanz zu starten.

*   [Medien][15]
    
    > Aufzeichnen und Wiedergeben von audio-Dateien.

*   [Medien erfassen][16]
    
    > Media-Dateien mithilfe des Geräts Media Capture-Anwendungen zu erfassen.

*   [Netzwerkinformationen (Verbindung)][17]
    
    > Der Netzwerkstatus und Mobilfunknetz Informationen schnell zu überprüfen.

*   [SplashScreen][18]
    
    > Ein- und Ausblenden der Splash-Screen Anwendungen.

*   [Vibration][19]
    
    > Eine API, das Gerät zu vibrieren.

*   [StatusBar][20]
    
    > Eine API zum Anzeigen, ausblenden und Konfigurieren der Status Bar Hintergrund.

 [2]: http://plugins.cordova.io/#/package/org.apache.cordova.battery-status
 [3]: http://plugins.cordova.io/#/package/org.apache.cordova.camera
 [4]: http://plugins.cordova.io/#/package/org.apache.cordova.console
 [5]: http://plugins.cordova.io/#/package/org.apache.cordova.contacts
 [6]: http://plugins.cordova.io/#/package/org.apache.cordova.device
 [7]: http://plugins.cordova.io/#/package/org.apache.cordova.device-motion
 [8]: http://plugins.cordova.io/#/package/org.apache.cordova.device-orientation
 [9]: http://plugins.cordova.io/#/package/org.apache.cordova.dialogs
 [10]: http://plugins.cordova.io/#/package/org.apache.cordova.file
 [11]: http://plugins.cordova.io/#/package/org.apache.cordova.file-transfer
 [12]: http://plugins.cordova.io/#/package/org.apache.cordova.geolocation
 [13]: http://plugins.cordova.io/#/package/org.apache.cordova.globalization
 [14]: http://plugins.cordova.io/#/package/org.apache.cordova.inappbrowser
 [15]: http://plugins.cordova.io/#/package/org.apache.cordova.media
 [16]: http://plugins.cordova.io/#/package/org.apache.cordova.media-capture
 [17]: http://plugins.cordova.io/#/package/org.apache.cordova.network-information
 [18]: http://plugins.cordova.io/#/package/org.apache.cordova.splashscreen
 [19]: http://plugins.cordova.io/#/package/org.apache.cordova.vibration
 [20]: https://github.com/apache/cordova-plugin-statusbar/blob/master/doc/index.md

Nicht-englische Übersetzungen über diese Plugin-Docs finden Sie indem Sie sich ältere Versionen von Cordova-Dokumentation. Verwenden Sie das Drop-Down-Menü auf die ganz oben rechts auf dieser Seite, um Versionen wechseln.