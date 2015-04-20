title: Email
author: peetcreative
date: 2015-04-15
direct: true
glyphicon: glyphicon-envelope

## E-Mail-Konto

In unserem System bekommst Du als Mitglied ein E-Mail-Konto.
Diese Email hat die Form: `<nutzername>@wh2.tu-dresden.de`

Das initiale Passwort kannst du dem Zugangsdatenblatt, das Du mit einem Exemplar deines Antrags zurückbekommst, entnehmen.
Ändern kannst du es jeder Zeit in der [Usersuite](/usersuite).

Wichtige Ankündigungen und Mitteilungen, die Dein Konto betreffen (Hoher Traffic, Zahlung ausstehend) werden per E-Mail versendend. 
Wir empfehlen dringend, Deine Mails regelmäßig abzurufen, oder eine E-Mail Weiterleitung einzurichten, falls Du das E-Mailkonto bei uns nicht benutzen möchtest.

### Warum sollte ich das AGDSN E-Mailkonto darüber hinaus benutzen?

Deine Mails und Daten dieses E-Mailkontos liegen auf unseren Servern in Dresdner im Wohnheimen. 

Im Gegensatz zu den großen amerikanischen als auch deutschen E-Mailanbietern sind wir nicht kommerziell orientiert, wollen für uns selber und unsere Mitglieder nur das Beste gerade in Hinsicht auf Datenschutz als auch Transparenz.

### E-Mails abrufen

#### Webmail

Am einfachsten kannst Du Mails im Browser abrufen über die [Webmailfunktion](https://www.wh2.tu-dresden.de/webmail). 
Dort kannst Du auch viele weitere Einstellungen zu deinem Account vornehmen.

#### Emailprogramm

Besser ist natürlich immer die Benutzung eines E-Mailprogrammes, da man damit mehr Möglichkeiten der Organisation oder Verschlüsselung hat. 

In unserem Download-Bereich kannst du dir zum Beispiel [Thunderbird](/service/software#email) herunterladen. In vielen Linux-Distributionen ist Thunderbird auch bereits vorinstalliert oder kann einfach per Paketmanager installiert werden.

Jedes andere E-Mailprogramm deiner Wahl auch auf anderen Plattformen sollte natürlich ähnlich funktionieren.

Du musst zunächst ein neuen Account/Konto anlegen. 
In Thundebird: `Datei > Neu > E-Mail-Konto...`

Hier gibst Du deine persönlichen Daten, deine E-Mailadresse `<nutzername>@wh2.tu-dresden.de`, sowie dein oben genanntes Passwort ein.

Dann fährst du fort mit der `Benutzerdefinierte Einstellungen`. Dort gibst du folgende Servereinstellungen ein. 

 | Server hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Posteingang-Server | mail.wh2.tu-dresden.de | IMAP(995) oder POP3(995) | SSL/TLS | Normal Passwort
Postausgang-Server | mail.wh2.tu-dresden.de | SMTP(465) | SSL/TLS | Normal Passwort

(Standard) IMAP belässt alle Mails auf dem Server. Das ermöglicht die Nutzung mehreren E-Mailprogrammen, daher mehreren Geräten und der Webmailfunktion. E-Mailprogramme speichern sich die geholten trotzdem zur offline Nutzung auf dem Gerät.
POP3 ruft einmal Mails vom Server ab und löscht sie dann auf dem Server. Es ist nicht möglich mehrere E-Mailprogramme zu benutzen. 

### E-Mails weiterleiten

Eine E-Mailweiterleitung kannst du dir einfach in der [Usersuite](/usersuite) konfigurieren. Alle Mails an `<nutzername>@wh2.tu-dresden.de` werden, dann automatisch an diese Adresse weitergeleitet.
