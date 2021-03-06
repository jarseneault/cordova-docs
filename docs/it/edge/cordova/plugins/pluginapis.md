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

# Plugin API

Cordova viene fornito con un set minimo di API e progetti aggiungere cosa extra API richiedono tramite plugin.

Può cercare attraverso tutti i plugin esistenti (plugin di terze parti inclusi) utilizzando il [Plugin Registry][1].

 [1]: http://plugins.cordova.io/

Il set tradizionale di nucleo Cordova plugin sono i seguenti:

*   [Stato della batteria][2]
    
    > Monitorare lo stato della batteria del dispositivo.

*   [Fotocamera][3]
    
    > Catturare una foto usando la fotocamera del dispositivo.

*   [Console][4]
    
    > Aggiungere ulteriori capacità console.log().

*   [Contatti][5]
    
    > Lavorare con il database di contatti di dispositivi.

*   [Dispositivo][6]
    
    > Raccogliere informazioni specifiche del dispositivo.

*   [Movimento di dispositivo (accelerometro)][7]
    
    > Sfruttare il sensore di movimento del dispositivo.

*   [Dispositivo orientamento (bussola)][8]
    
    > Ottenere la direzione che il dispositivo sta puntando.

*   [Finestre di dialogo][9]
    
    > Notifiche visive del dispositivo.

*   [FileSystem][10]
    
    > Gancio in file system nativo tramite JavaScript.

*   [Trasferimento di file][11]
    
    > Gancio in file system nativo tramite JavaScript.

*   [Geolocalizzazione][12]
    
    > Sensibilizzare la vostra sede di applicazione.

*   [Globalizzazione][13]
    
    > Attivare la rappresentazione degli oggetti specifici di una lingua.

*   [InAppBrowser][14]
    
    > Lanciare gli URL in un'altra istanza del browser in-app.

*   [Media][15]
    
    > Registrare e riprodurre file audio.

*   [Acquisizione di media][16]
    
    > Catturare i file multimediali utilizzando le applicazioni di cattura multimediale del dispositivo.

*   [Informazioni di rete (connessione)][17]
    
    > Verificare rapidamente lo stato di rete e informazioni della rete cellulare.

*   [Splashscreen][18]
    
    > Mostrare e nascondere la schermata iniziale di applicazioni.

*   [Vibrazione][19]
    
    > Un'API per vibrare il dispositivo.

*   [StatusBar][20]
    
    > Un'API per mostrare, nascondere e la configurazione sfondo barra di stato.

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

Traduzioni inglese di questi documenti di plugin si possono trovare guardando le versioni precedenti della documentazione Cordova. Utilizzare il menu a discesa a molto alto a destra di questo sito per passare le versioni.