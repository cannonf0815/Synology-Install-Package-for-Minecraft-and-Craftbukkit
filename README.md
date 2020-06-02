# Synology-Install-Package-for-Minecraft-and-Craftbukkit
A package to allow you to run a Minecraft server on your Synology NAS

History

I wanted to set up a private Minecraft server for my son.  I found work by patters at:

http://pcloadletter.co.uk/2012/01/11/minecraft-package-for-synology/

Unfortunately it hadn't been updated in about 2 years, but from the comments it was apparent that people were still
using it and manually updating the files.  Well, BLECH!  I decided to try to clean it up because, well, I'm a glutton
for punishment.

Craftbukkit was effectively killed off and replaced by Spigot, so I added it to the package, and I recently added Paper, a highly efficient Spigot fork, to the package.  Paper is probably the best Java minecraft server to run right now if you're running a low resource server like a NAS.

You can find more information on my blog at:

http://blog.heatdfw.com/p/synology-minecraft-server-setup.html

You can install the package from my repository at:
http://www.hildinger.us/sspks/index.php

I've started discussion threads at:

https://community.synology.com/enu/forum/10/post/131756
http://www.minecraftforum.net/forums/support/server-support/server-administration/2460654-synology-nas-minecraft-server-install-package

Compatitibility, Java, etc.

Honestly, any Synology machine that has the power should be OK, and I'm not able to tell you if yours is one of them -- they have a bunch of machines with a wide range of power.
As of now, I'm using a RS814+ with DSM 5.2 (previously 5.1) and the Java VM published by Synology.  patters also has Java packages at:

http://packages.pcloadletter.co.uk/

I won't pretend to know what's right for you.
