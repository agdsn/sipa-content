title: Current Trafficregulations
date: 2015-03-11
direct: true
glyphicon: glyphicon-dashboard
rank: 5

Our network underlies a traffic limit. Every member having internet access is provided 3 GiB of credit each day. This covers incoming as well as outgoing traffic.
However, it is possible to save credit up to 63 GiB. This value results from three weeks of saving.
The “starting contingent” is 21 GiB.

You can view your current traffic status on the traffic page. Additionally, there are plugins available in the [Software](../service/software) section, showing the traffic status directly in the browser.

If you consumed more than the allowed amount, your access is blocked until your credit is greater than zero again. This is checked once a day.

###Accounting-Free network

All connetions to computers inside the TU/HTW network are free of accounting. This concerns every devices with adresses of the form 141.30.X.X, 141.56.X.X and 141.76.X.X.

The following devices are _excluded_ from this exception:

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

###Further hints

The time is set up in universal time coordinated (UTC). Therefore, a “new day” begins at 1am in the winter and 2am in the summer.

The data is collected every 10 minutes. After that period, the traffic page is updated. You should __mind this delay__ if your credit is near zero.

Note that every packet trying to reach or leave your device is counted – even if the packet does not reach its destination, for instance because it is shut down! Usually, this causes an additional accounting of 100KB a day, which should be low enough to be ignored.

A different phenomenon is the usage of Peer-to-Peer applications like EDonkey, Kazaa, BitTorrent etc.
These applications flood the network on every single request transmitted, which causes them to be transported to users who:

* Respond the request partly,
* Save the IP of the requesting device, to compose requests themselves and
* to redirect the IP, so other devices can compose requests as well.

Therefore, by using such a program, even after hours of the actual usage, a massive amount of requests is sent to your device, independent of whether it is turned on or off. This can cause many dozens of accounted Megabytes in just a few hours.
