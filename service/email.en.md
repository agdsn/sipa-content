title: Email
author: peetcreative
date: 2015-04-15
direct: true
glyphicon: glyphicon-envelope

## e-mail-account

As a Member you have an e-mail-account in our System.
Which looks like this: `<username>@wh2.tu-dresden.de`

You can find the initial password on the access data sheet, which You got back connected to one filled form of your application.
You can always change it with the [usersuite](/usersuite).

Important announcements and notifications regarding your account (high traffic, overdue payment) are sent via e-mail. 
We strongly recommend you to check your mails regularly or to setup an address for forwarding, if you do not intend to use your e-mail account with us.

### Why should I use the AGDSN e-mail-account in addition?

Your mails and data of this e-mail-account are stored on servers located in dormitories in Dresden.

In contrast to big American or German e-mailproviders, we are nonprofit. So we want for us and our members only the best according privacy and transparency.

### Receive e-mails

#### Webmail

You can simply receive e-mails using your browser via the [webmailfunction](https://www.wh2.tu-dresden.de/webmail).
There You can also configure much further your e-mail-account.

#### e-mail-program #### 

It's better to use a e-mail-program, because you've got the possibility of organize and encryption.

In our FTP-section you can download  for example [Thunderbird](/pages/service/software#email). In the most Linux-distributions Thunderbird is already installed or can be installed by a packagemanager.

Other e-mail-programs also for other platforms should work nearly the same.

First of all you have to add an Account.
In Thunderbird: `File > New > Mail Account ...`

Give your personal data, your e-mail-address `<username>@wh2.tu-dresden.de` and your password.

Go to `Manual Config`. There type in the following serversettings.

 | Server hostname | Protocol(Port) | SSL | Authentication
-|-|-|-|-
Incomming| mail.wh2.tu-dresden.de | IMAP(995) oder POP3(995) | SSL/TLS | Normal Passwort
Outgoing | mail.wh2.tu-dresden.de | SMTP(465) | SSL/TLS | Normal Passwort

(standard) IMAP keeps all e-mails on the server. Because of this you can use multiple e-mail-programs, therefore multiple devices and the webmailfunction. E-mail-programs store the checked although for offline    Usage. 
POP3 check the mails only once and then deletes them after this from the server. It's not possible to use multiple e-mail-programs.

### Forward e-mails

You can simply setup an e-mail-forward with the [usersuite](/usersuite). Each e-mail send to `<username>@wh2.tu-dresden.de` will be automatically forwarded to this e-mail. 