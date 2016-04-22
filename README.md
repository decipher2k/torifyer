# torifyer
What does it do?
Torifyer is a small script which will forward all your network traffic autmatically through the tor network.

Why do i need this? I can set tor as a proxy in my browser/messenger/whatever?
When using only proxy mode, you will face the major problem of anonymity: consistency.
Some times you switch it off, sometimes you switch it on. Some of your programs use it, some don't.It's nearly impossible to keep an overview.
And worst of it all: if your government points at you, they will definitively inject a troyan through provider-side
packet injection.
Routing all your traffic (including updates, NTP and DNS requests etc, and especially: system updates) through tor will make this much harder.
Please note: we do strongly encourage you to use clean exit nodes. Further information about how to achieve this can be found on the internet.

How to install?
Requirements:
tor
Optional:
vidalia,ipcalc
install the package using dpkg -i ./torifyer_0.1_all.deb
