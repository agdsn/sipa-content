title: Webhosting
date: 2015-03-17
direct: true
glyphicon: glyphicon-cloud
rank: 2
event: [Borsbergstraße, Wundtstraße, Zellescher Weg]

In these dormitories, you have the possibility to create your own website! Anyway, it is important that the content is not illegal and complies with good behaviour. Remember: You are completely responsible for the content of your website!

To create your own page in the web you have to create a file named `index.html`. It is automatically used as a start page, further sites have to be linked there of course. Now, copy the created files into the folder `public_html` in your userhosting directory.

You can now access the pages by visiting `http://www.wh2.tu-dresden.de/~userlogin`, replacing `userlogin` by your actual login. Don't forget to add the `~` at the beginning!

To gain access to your home directory, it is necessary to log in into the userhosting via SSH. While on Linux or Macintosh systems, it is easy to do so, using Microsoft windows forces you to install an application like WinSCP, Putty or Diverse. For just transferring files as needed in this case, WinSCP is a suitable choice.

Other features we provide are a MySQL database and the possibility to use PHP in your pages. Maintaining the database is possible using the terminal (usage: `mysql -u userlogin -p`) after you specified a database password in the [Usersuite](/usersuite)

A file copied there, for instance `image.jpg`, can be accessed in a browser by visiting `http://www.wh2.tu-dresden.de/~userlogin/image.jpg`.
