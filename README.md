# G32-Display480x480
ESPHome Projekt für ein Guition 4848S040 Display zur Verwendung mit einem Otto Wilde G32 Gasgrill.

![PXL_20250601_120205462 MP](https://github.com/user-attachments/assets/d4eb405b-1e8c-4dc2-9d72-04a028044d84)

Das Gerät baut eine Bluetooth Verbindung zum G32 aus. Es liest dann diverse Daten aus dem G32 aus, stellt sie auf dem Display grafisch dar und stellt sie über Wifi dem Home Assistant zur Verfügung.

Zusätzlich kann es eine Verbindung zu einem Meater+ (nur mit exakt diesem Typ getestet!) Grillthermometer aufbauen und auch dessen Daten (Kerntemperatur und Garraumtemperatur) anzeigen und zum HA weiterleiten. Die Auswertung der Temperaturen ist experimentell, da zum Bluetooth Protokoll des Meater+ mWn keine Doku zur Verfügung steht.

Die Hardware des 4848S040 stellt einen Anschluß für einen externen Lithium Akku zur Verfügung. Leider ist in diesm Display keine Messung der Akkuspannung vorgesehen. Diese wird daher nicht überwacht!

Auch ein Piezo-Buzzer ist hier nicht so einfach wie im G32-Display480x320 anzuschließen, weil hier keine frei verwendbaren IOs zur Verfügung stehen. 


