title: E-Mail
date: 2015-04-15
direct: true
glyphicon: glyphicon-envelope
rank: 3

In unserem System bekommst Du (außer in der Zeunerstraße) als Mitglied ein E-Mail-Konto.
Das Konto musst Du nicht nutzen, um von uns E-Mails zu bekommen - du kannst auch in der [Usersuite](/usersuite) einen E-Mail-Forward einrichten, um die Nachrichten an Deine schon vorhandene Adresse geschickt zu bekommen.
Diese E-Mail hat die Form:

* Borsbergstraße: `<nutzername>@wh10.tu-dresden.de`
* Gerokstraße: `<nutzername>@wh17.tu-dresden.de`
* Hochschulstraße: `<nutzername>@wh12.tu-dresden.de`
* Wundtstraße und Zellescher Weg: `<nutzername>@wh2.tu-dresden.de`

Das initiale Passwort kannst du dem Zugangsdatenblatt, das Du mit einem Exemplar deines Antrags zurückbekommst, entnehmen.
Ändern kannst du es jeder Zeit in der [Usersuite](/usersuite).

Wichtige Ankündigungen und Mitteilungen, die Dein Konto betreffen (Hoher Traffic, Zahlung ausstehend) werden per E-Mail versendend. 
Wir empfehlen dringend, Deine Mails regelmäßig abzurufen, oder eine E-Mail Weiterleitung einzurichten, falls Du das E-Mailkonto bei uns nicht benutzen möchtest.

## Warum Du das AG DSN E-Mailkonto nutzen solltest

Deine Mails und Daten dieses E-Mailkontos liegen auf unseren Servern in Dresdner im Wohnheimen. 

Im Gegensatz zu den großen amerikanischen als auch deutschen E-Mailanbietern sind wir nicht kommerziell orientiert, wollen für uns selber und unsere Mitglieder nur das Beste gerade in Hinsicht auf Datenschutz als auch Transparenz.

## E-Mails abrufen

### Webmail

Am einfachsten kannst Du Mails im Browser abrufen über die Webmailfunktion:

* [Borsbergstraße](https://wh10.tu-dresden.de/mail/)
* [Gerokstraße](https://wh17.tu-dresden.de/webmail/)
* [Hochschulstraße](https://wh12.tu-dresden.de/roundcube/)
* [Wundtstraße und Zellescher Weg](https://www.wh2.tu-dresden.de/webmail). 

Dort kannst Du auch viele weitere Einstellungen zu deinem Account vornehmen.

### E-Mail-Programm

Besser ist natürlich immer die Benutzung eines E-Mailprogrammes, da man damit mehr Möglichkeiten der Organisation oder Verschlüsselung hat. 

In unserem Download-Bereich kannst du dir zum Beispiel [Thunderbird](/service/software#email) herunterladen. In vielen Linux-Distributionen ist Thunderbird auch bereits vorinstalliert oder kann einfach per Paketmanager installiert werden.

Jedes andere E-Mailprogramm deiner Wahl auch auf anderen Plattformen sollte natürlich ähnlich funktionieren.

Du musst zunächst ein neuen Account/Konto anlegen. 
In Thunderbird: `Datei > Neu > E-Mail-Konto...`

Hier gibst Du deine persönlichen Daten, deine E-Mailadresse `<nutzername>@whX.tu-dresden.de`, sowie dein oben genanntes Passwort ein.

Dann fährst du fort mit der `Benutzerdefinierte Einstellungen`. Dort gibst du folgende Servereinstellungen ein. 

#### Borsbergstraße

&nbsp; | Hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Posteingang-Server | ? | ? | ? | ?
Postausgang-Server | ? | ? | ? | ?

#### Gerokstraße

&nbsp; | Hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Posteingang-Server | mail.wh17.tu-dresden.de | POP3(110)	|	  	| Normal Passwort
Posteingang-Server | mail.wh17.tu-dresden.de | IMAP(993)	| SSL/TLS 	| Normal Passwort
Postausgang-Server | mail.wh17.tu-dresden.de | SMTP(25) 	| STARTLS 	| Normal Passwort

#### Hochschulstraße

&nbsp; | Hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Posteingang-Server | wh12.tu-dresden.de | ? | ? | ?
Postausgang-Server | wh12.tu-dresden.de | ? | ? | ?

#### Wundtstraße und Zellescher Weg

&nbsp; | Hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Posteingang-Server | mail.wh2.tu-dresden.de | IMAP(995) | SSL/TLS | Normal Passwort
Posteingang-Server | mail.wh2.tu-dresden.de | POP3(995) | SSL/TLS | Normal Passwort
Postausgang-Server | mail.wh2.tu-dresden.de | SMTP(465) | SSL/TLS | Normal Passwort

(Standard) IMAP belässt alle Mails auf dem Server. Das ermöglicht die Nutzung mehreren E-Mailprogrammen, daher mehreren Geräten und der Webmailfunktion. E-Mailprogramme speichern sich die geholten trotzdem zur offline Nutzung auf dem Gerät.
POP3 ruft einmal Mails vom Server ab und löscht sie dann auf dem Server. Es ist nicht möglich mehrere E-Mailprogramme zu benutzen. 

### E-Mails weiterleiten

Eine E-Mailweiterleitung kannst du dir einfach in der [Usersuite](/usersuite) konfigurieren. Alle Mails an `<nutzername>@whX.tu-dresden.de` werden, dann automatisch an diese Adresse weitergeleitet.
