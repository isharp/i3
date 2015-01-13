i3 - Unofficial Gaps/Icons Branch
===========================

This branch uses the gaps patch from:
http://infra.in.zekjur.net/pipermail/i3-discuss/2012-November/001042.html

I have also included some minor fixes that, for me at least, makes it work perfectly.

Gap sizes are now set in the config file by adding:
```
gap_size 8
```
This branch also uses the i3bar xbm icons patch from:
https://github.com/ashinkarov/i3-extras/blob/master/i3bar-xbm-icons.patch

And the result:

[i3](http://issacsharp.com/misc/i3.png "i3")

Build:
```
make
sudo make install
```
