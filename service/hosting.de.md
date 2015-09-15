title: Userhosting
date: 2015-03-17
direct: true
glyphicon: glyphicon-cloud
rank: 2

**Achtung**: Diese Anleitung gilt nur für Mitglieder der AG, die in der Wundtstraße oder dem Zelleschen Weg wohnen!

Nun, jeder kann bei uns eine eigene Homepage ins Netz stellen! Wichtig dabei ist, dass der Inhalt nicht rechtswidrig ist, sowie im Rahmen der guten Sitten bleibt, denn für den Inhalt Deiner Seite haftest Du alleine!

Um Deine eigene Seite ins Netz zu stellen benennst Du zunächst die Startseite index.html. Diese wird dann als Startseite automatisch aufgerufen, alle weiteren Seiten müssen dann natürlich über diese Startseite verlinkt sein. Die Startseite mit dem Namen index.html, sowie Deine weiteren Seiten stellst Du dann in Dein Home-Verzeichnis auf dem Userhosting (helios.wh2.tu-dresden.de) ins Verzeichnis public_html.

Der Zugriff auf Deine Seiten erfolgt dann über

`http://www.wh2.tu-dresden.de/~nutzerlogin`

Als Nutzerlogin sollte Dein Login verwendet werden, welches auch auf Deinem Antrag steht, den Du von uns zurück erhalten hast. Ganz wichtig ist dabei das ~, ohne dies gehts nicht!

Um Zugriff auf Dein Home-Verzeichnis zu erhalten ist es nötig, sich über SSH auf dem Userhosting einzuloggen. Unter Linux oder Mac ist das kein Problem, jedoch erzwingt die Verwendung von Microsoft Windows als Betriebssystem die Verwendung eines Programms um diesen Zugriff per SSH zu erhalten. Hier bieten sich zum Beispiel Putty oder diverse andere an. Dateien verschiebt man bei Verwendung von Microsoft-Betriebssystemen am besten per WinSCP zum Userhosting.

Weitere von uns angebotene Features sind eine eigene MySQL-Datenbank und die Möglichkeit, PHP zu nutzen. Die Datenbankverwaltung ist per Konsole (Aufruf über: mysql -u nutzerlogin -p) möglich, nachdem in der [Usersuite](../../usersuite) ein Datenbank-Passwort gesetzt wurde.

Eine dort abgelegte Datei, beispielsweise mit Namen bild.jpg, ruft man im Browser auf, indem man sinngemäß

`http://www.wh2.tu-dresden.de/~nutzerlogin/bild.jpg`

in das Browserfenster eingibt.
