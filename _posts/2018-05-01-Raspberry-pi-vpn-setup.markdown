---
title           : "Setting up a raspberry pi VPN"
categories      : technology
tags            : raspi
---

A VPN is something I like to have in place for those times where I manage to forget something. Getting the raspi to do this has gotten much easier recently, without needing to do all the config / keygen yourself.

Using http://www.pivpn.io/ as the starter gives you pretty much everything you need.

A few extra pieces from me, in case you're stuck on how to proceed:* I use ddclient (sudo apt-get install ddclient) as my dynamic dns* I use zoneedit to let me edit my zone easily (the same domain name points at this blog, and a few other bits)* To get the certificates of the pi you can either install samba (which I don't like to do on the VPN) or use scp.
