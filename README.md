#  Monitoring Wifi Access Point
Monitorovanie pripojených používatelov a následné zaslanie informácií o nich na E-mail.

### Nastavenie Wifi Access Point
Ako prvé sa  musia nastaviť DNS a DHCP server, DHCP client, NAT a Address List.
![alt text](sfddfsdfsd.png)

#### Následne nastavenie samotnej Wifi
Nastavenie spočíva : mode = AP bridge, SSID = názov Wifi, nastavenie zabezpečenia v Security profiles.
### Nastavenie posielania E-mailu
![alt text](email2.png)
### Script v Scheduler
Hlavný script, ktorý kopíruje registračnú tabuľku zo zariadenia a ukladá ju do vytvoreného súboru 'wifi.txt' a následne posiela na emailovú adresu.

![alt text](shedule.png)
### Spúštanie scriptu
Spúsťenie scriptu sa uskutoční po stlačený tlačitka 'Run Script'.

![alt text](scypt.png)

### Vzorová ukážka prijatého E-mailu
Na obrázku môžeme vidieť troch pripojených používatelov a údaje o nich.

![alt text](email.png)

