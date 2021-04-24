## Informationen / "Known Bugs"

#### 💡 Addon Version 5.0
- Unter "Einstellungen->Systemsteuerung->Zusatzsoftware" fehlen das Icon sowie die verfügbare Version
  - https://homematic-forum.de/forum/viewtopic.php?f=76&t=66890#p659185
  - ist mit der nächsten Version 5.1 gefixt


#### 💡 CCU FW Version 3.57.4 
- "Einstellungen"->"Geräte"
  - das Setzen des Wertes `0` bei einer Geräteeinstellung führt dazu, dass der Minimalwert gesetzt wird
    - siehe auch [Github](https://github.com/jens-maus/RaspberryMatic/issues/1058#issuecomment-791913360)

- **neue Firmware für das RPI-RF-MOD (4.2.14)**
  - durch Anpassung der Frequenz sind evtl. mit dem `FreqTest` abgeglichene Geräte nicht mehr (zuverlässig) erreichbar
    - siehe auch [Homematic Forum](https://homematic-forum.de/forum/viewtopic.php?f=76&t=63125&p=648643#p648640)

#### 💡 CCU FW Version 3.55.10 / 2.55.10
- "Einstellungen"->"Geräte"
  - das Setzen einiger Geräteparameter (mit Dezimalstellen) ist weiterhin nicht möglich
    - siehe [Homematic Forum](https://homematic-forum.de/forum/viewtopic.php?p=638789#p638780)
  
#### 💡 CCU FW Version 3.55.5 / 2.55.5
- "Einstellungen"->"Geräte"
  - Das Setzen von Geräteparametern ist nicht möglich
- "Status und Bedienung" -> "Räume" / "Gewerke" / "Geräte"
  - u.U. wird der Gerätetyp dem Namen vorangestellt
