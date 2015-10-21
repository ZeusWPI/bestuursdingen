
Installatie
===========

De offici&euml;le installatie-instructies van Linux Mint zijn [hier][guide]
beschikbaar. Hieronder vindt u een samenvatting met enkele keuzes die wij
maakten bij de installatie op de UGent-laptops.

Opstarten van USB-stick
-----------------------

1. Download Linux Mint van de [offici&euml;le site][mint]. Dit is een Guide voor
de 32/64 bit versie van Cinnamon. ![Cinnamon 32/64 bit][]
2. Selecteer de mirror naar keuze. Dit is vanwaar je Linux Mint zal downloaden.
Wij raden België aan. ![Belgian Mirror][]
3. Sla het bestand op.
4. ...

5. Stop de USB-stick in de laptop terwijl die uit staat, en start op.
6. Tijdens het opstarten druk je herhaaldelijk op F12, tot op het
Dell-startscherm (groot Dell logo centraal, met laadbalk eronder) rechtsboven
"Preparing one-time boot menu..." in het geel verschijnt.
7. In het bootmenu selecteer je "USB Storage Device" onder "LEGACY BOOT".
8. Je komt terecht in een menu waarin je "Start Linux Mint" kan selecteren. Doe dit.
9. Linux Mint zal opstarten.

Installatie
-----------

Je kan even rondspelen op Linux Mint nu. Merk op dat alles via de USB-stick zal
verlopen en dus redelijk traag gaan. Als je klaar bent, ga je over tot te
installatie. Hiervoor ben je best verbonden met het [internet](#internet).

1. Dubbelklik op het "Install Linux Mint" icoon op het bureaublad.



Post-installatie
================

<a name="internet"></a> Eduroam
-------------------------------

Binnen de UGent surf je met Eduroam. Het verbinden hiermee is niet altijd even
triviaal. Hieronder enkele richtlijnen.

TODO
- @ugent.be !
- Het certificaat bevindt zich in /etc/ssl/certs/AddTrust_External_Root.pem.

Software
--------

Software installeren kan via de Software Manager.

### VPN ###
1. Installeer 'network-manager-vpnc-gnome' via de Software manager.
2. Klik op het netwerkicoontje naast je klok
3. Klik op "Network settings".
4. Klik op de plus linksonder.
5. Kies als interface 'VPN' in het dropdownmenu.
6. Kies voor 'Cisco compatible VPN' in het dropdownmenu en druk op 'Create'.
7. Vul de instellingen aan zoals afgebeeld.
8. Klik op 'Save'.

Je kan nu je VPN inschakelen door 'UGent VPN' te selecteren in de
interfacelijst, en de schakelaar rechtsboven aan te zetten.

### Citrix ###
1. Ga naar de [citrix download pagina][].
2. Kies voor de 64-bitversie van Receiver for Linux, waar 'filetype .deb' onder
de downloadknop staat.
3. Klik op 'Download your file manually', onderaan.
4. Open met GDebi Package Installer.
5. Normaal gezien zal er nu een fout optreden. Behoudt uwe kalmte, dit is
verwacht.
6. Sluit de foutmelding en de package installer en open een Terminaal Venster
(met ctrl-alt-T).
7. Voer in het Terminaal Venster 'sudo apt-get -f install' en duw op Enter.
8. Ga akkoord met alle voorstellen.

Ga naar athena.ugent.be en verifieer dat alles correct werkt. Zo niet, mail naar
pietervdvn@gmail.com .

### Aangeraden software ###
- **chat client**: Pidgin (standaard), Skype
- **irc client**: Pidgin (standaard), weechat
- **Torrents**: transmission (standaard), qBittorrent, Deluge
- **Browser**: Firefox (standaard), Chromium (Google Chrome zonder Google)
- **Mail client**: Thunderbird (standaard)
- **Muziekspeler**: Banshee (standaard), Quod Libet (lightweight, cool)
- **Image editor**: Gimp (standaard)
- **Text editor**: Gedit (standaard), vim (voor ninjas)
- **Office Suite**: LibreOffice (standaard)
- **Overige**: Steam, Dropbox, dingen

### Windowsprogramma's uitvoeren op Linux ###
Als je niet zonder je dierbare Windowssoftwarez kan, kan je Wine gebruiken. Voor
games kan je PlayOnLinux gebruiken (een grafische interface voor Wine die
automagisch dingen laat werken) Wine en PlayOnLinux kan je installeren via de
Sofware Manager.

[guide]: http://www.linuxmint.com/documentation/user-guide/Cinnamon/dutch_17.0.pdf
[mint]: http://www.linuxmint.com/download.php
[citrix download pagina]: http://www.citrix.com/downloads/citrix-receiver/linux/receiver-for-linux-130.html
[cinnamon 32/64 bit]: http://i.imgur.com/UmTFS8F.png
[Belgian Mirror]: http://i.imgur.com/GgY6vH6.png

