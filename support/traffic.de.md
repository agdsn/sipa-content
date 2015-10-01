title: Trafficbeschränkung
date: 2015-03-11
direct: true
glyphicon: glyphicon-dashboard
rank: 5

In der AG DSN existiert eine Traffic-Beschränkung. Jedem Mitglied mit Netzanschluss stehen pro Tag 3 GiB zu, dabei wird sowohl eingehender als auch ausgehender Verkehr gezählt.
Dabei ist es möglich, den nicht verbrauchten Traffic bis zu einem Maximum von 63 GiB anzusparen. Diese Maximalzahl ergibt sich aus drei Wochen Ansparfrist (3x21).
Jedes neue Mitglied beginnt mit einem Kontingent von 21 GiB.

Euren aktuellen Status könnt ihr auf der Trafficseite zu jeder Zeit abrufen. Weiterhin gibt es für einige Browser bei uns im [Software-Bereich](../service/software) ein Plugin, welches den Trafficstand unauffällig anzeigt.

Wird mehr als die erlaubte Menge Datenverkehr verursacht, wird der Zugang solange abgeschaltet, bis das Guthaben wieder positiv ist. Dies wird einmal täglich geprüft.

###Trafficfreie Netze

Verbindungen zu Computern im Uninetz/HTW sind trafficfrei. Das betrifft alle Computer mit den IP Adressen 141.30.X.X, 141.56.X.X und 141.76.X.X

Es gelten folgende Ausnahmen von der Befreiung:

141.30.3.50 (vpn.zih.tu-dresden.de)
141.30.4.125 (vpn2.zih.tu-dresden.de)
141.30.61.140 (login1.zih.tu-dresden.de)
141.30.61.141 (login2.zih.tu-dresden.de)
141.30.117.36 (obelix.et.tu-dresden.de)
141.76.2.7 (serv9.inf.tu-dresden.de)
141.76.2.11 (ganymed.inf.tu-dresden.de)
141.76.2.12 (serv12.inf.tu-dresden.de)
141.76.29.146 (vpn1.inf.tu-dresden.de)
141.76.29.147 (vpn2.inf.tu-dresden.de)
141.76.29.148 (vpn.inf.tu-dresden.de)
141.56.15.17 (rob.rz.htw-dresden.de)
141.56.100.248 (rou6.rz.htw-dresden.de)

### Weitere Hinweise

Die Zeitzählung erfolgt nach Weltzeit (UTC). Deshalb beginnt der neue Tag in der Datenbank erst 1 Stunde bei Winterzeit, bzw. 2 Stunden bei Sommerzeit nach Mitternacht.

Die Daten werden 10 Minuten lang gesammelt und anschließend wird die Traffic-Seite aktualisiert. Auf diese Latenzzeit sollte man vor allem dann achten, wenn man sich in der Nähe des Limits bewegt.

Es werden alle Pakete gezählt, die sich von und zu deinem Rechner bewegen. Wenn also die Pakete diese Strecke passieren und anschließend doch nicht ankommen, weil z.B. der Rechner ausgeschaltet wurde, werden sie trotzdem gezählt! Auswertungen haben ergeben, dass dadurch ca. 100KB täglich an Traffic dazukommt, für den man nichts kann. Das sollte aber verschmerzbar sein.

Anders ist das jedoch bei Peer-to-Peer-Anwendungen wie EDonkey, Kazaa, BitTorrent usw. Bei diesen Programmen wird bei jeder von einem Rechner gestellten Anfrage das Netz geflutet, die Anfragen werden also an Millionen von anderen Nutzern weitergegeben, die:

* zum Teil die Anfrage beantworten,
* sich die IP des anfragenden Rechners merken, um selbst Anfragen zu stellen und
* die IP weiterzuleiten, damit andere Rechner ebenfalls Anfragen stellen können.

Somit können durch das einmalige Verwenden solcher Programme noch Stunden danach Anfragen ankommen, unabhängig davon, ob der entsprechende Rechner aus ist oder nicht. Solche Anfragen werden natürlich berechnet und können mehrere Dutzend Megabyte in wenigen Stunden ausmachen.
