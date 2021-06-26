# dotTopsham
The dot Topsham TLD hosts file.

Many thanks to:

Topsham LETS

The Topsham Pound

Topsham Local Exchange; 
 http://topsex.topsham/

Steve Black's Host File; 
 https://github.com/StevenBlack/hosts

MeshWorks @ The MeshWorks Trust (Sark).

Instructions:
Copy the contents of "hosts.topsham" file ^^ into your "hosts" file...
... then restart your browser, and visit:
http://topsham/


Linux / Android / MacOS: /etc/hosts


The command below (*nix only) will add the dotTopsham TLD to the bottom of your hosts file:

cp /etc/hosts /etc/hosts.backup && wget --no-check-certificate --content-disposition https://raw.githubusercontent.com/TopshamExchange/dotTopsham/main/hosts.topsham -O ->> /etc/hosts




Windows 10+: C:\Windows\System32\drivers\etc\hosts

The commands below (Win10+ Only) MAY do the job?


set url=https://raw.githubusercontent.com/TopshamExchange/dotTopsham/main/hosts.topsham

set file=hosts.topsham

certutil -urlcache -split -f %url% %file%

echo Done.


The above code may work on Win10+ machines. 
Otherwise you could rename / overwrite your hosts file, and copy the contents of topsham.hosts at the bottom?
... good luck with that.


