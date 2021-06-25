# dotTopsham
The dot Topsham TLD hosts file.

Many thanks to:

Topsham LETS

The Topsham Pound

Topsham Local Exchange; 
 http://topsham/

Steve Black AdBlocker; 
 https://github.com/StevenBlack/hosts

Meshworks @ The MeshWorks Trust (Sark).

Maybe you forgot to join a network?
Some instructions below ...

@ DOT topsham
https://github.com/TopshamExchange/dotTopsham/blob/main/hosts.topsham
...or...
Mirrors  & other TLD's soon.

Instructions:
Copy the contents of "hosts.topsham" file ^^ into your "hosts" file...
... then restart your browser, and visit:
http://topsham/

Linux / Android / MacOS :  \etc\hosts
The command below will add the dotTopsham TLD
to the bottom of your hosts file:

cp /etc/hosts /etc/hosts.backup && wget --no-check-certificate --content-disposition https://raw.githubusercontent.com/TopshamExchange/dotTopsham/main/hosts.topsham -O ->> /etc/hosts


Windows: C:\Windows\System32\drivers\etc\hosts
... good luck with that.
