title: Email
date: 2015-04-15
direct: true
glyphicon: glyphicon-envelope
rank: 3
event: [Borsbergstraße, Gerokstraße, Hochschulstraße, Wundtstraße, Zellescher Weg]

As a Member you have an e-mail-account in our System.
You do not have to use this account to receive our mails -  in the [Usersuite](../../usersuite), you can forward the mails to your existant private address.

Your mail is of the form:

* Borsbergstraße: `<username>@wh10.tu-dresden.de`
* Gerokstraße: `<username>@wh17.tu-dresden.de`
* Hochschulstraße: `<username>@wh12.tu-dresden.de`
* Wundtstraße and Zellescher Weg: `<username>@wh2.tu-dresden.de`

You can find the initial password on the access data sheet, which You have been handed out after your application
You can always change it with the [usersuite](../../usersuite).

Important announcements and notifications regarding your account (high traffic, overdue payment) are sent via e-mail.
We strongly recommend you to check your mails regularly or to setup an address for forwarding, if you do not intend to use your e-mail account with us.


## Why You should use the AG DSN e-mail-account in addition

Your mails and data of this e-mail-account are stored on servers located in dormitories in Dresden.

In contrast to big American or German providers, we do not work based on profit, which is why we try keeping


## Receive e-mails

### Webmail

The simplest way to receive your mail is using the webmailer we provide:

* [Borsbergstraße](https://mail.wh10.tu-dresden.de)
* [Gerokstraße](https://wh17.tu-dresden.de/webmail/)
* [Hochschulstraße](https://wh12.tu-dresden.de/roundcube/)
* [Wundtstraße and Zellescher Weg](https://www.wh2.tu-dresden.de/webmail).


### Mailclient

A better way of course is the usage of a mail client, as it provides more functionality to organize and encrypt your data.

In our download-section you can download such programs, like for example [Thunderbird](software#email). In most Linux-distributions, Thunderbird is already installed or can be installed using a packagemanager.

Anyway, every other mail program should work in a similiar way.

First of all you have to add an Account.
In Thunderbird: `File > New > Mail Account ...`

Provide your personal data, your e-mail-address `<username>@whX.tu-dresden.de` and your password.

Now, go to `Manual Config`. There, type in the following serversettings.

#### Borsbergstraße

&nbsp; | Hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Incoming | mail.wh10.tu-dresden.de | IMAP(143) | STARTTSL | Normal Password
Outgoing | mail.wh10.tu-dresden.de | SMTP(25) | ? | Normal Password

#### Gerokstraße

&nbsp; | Hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Incoming | mail.wh17.tu-dresden.de | POP3(110)	|	  	| Normal Passwod
Incoming | mail.wh17.tu-dresden.de | IMAP(993)	| SSL/TLS 	| Normal Password
Outgoing | mail.wh17.tu-dresden.de | SMTP(25) 	| STARTLS 	| Normal Password

#### Hochschulstraße

&nbsp; | Hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Incoming | wh12.tu-dresden.de | ? | ? | ?
Outgoing | wh12.tu-dresden.de | ? | ? | ?

#### Wundtstraße und Zellescher Weg

&nbsp; | Hostname | Protokoll(Port) | SSL | Authentifizierung
-|-|-|-|-
Incoming | mail.wh2.tu-dresden.de | IMAP(993) | SSL/TLS | Normal Password
Incoming | mail.wh2.tu-dresden.de | POP3(995) | SSL/TLS | Normal Password
Outgoing | mail.wh2.tu-dresden.de | SMTP(465) | SSL/TLS | Normal Password


(Standard) IMAP keeps all e-mails on the server. Because of this you can use multiple e-mail-programs, and even multiple devices plus the web mailer.
POP3 check the mails only once and then deletes them after this from the server. It's not possible to use multiple e-mail-programs.

### Forward e-mails

You can simply setup an e-mail-forward with the [usersuite](../../usersuite). Each e-mail send to `<username>@wh2.tu-dresden.de` will be automatically forwarded to this e-mail.
