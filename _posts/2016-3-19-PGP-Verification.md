---
layout: post
title: A Social Web of Trust
---

-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA512

Here's the thing about PGP: public keys are useless unless you've verified
that the copy you have truly corresponds to the person you're trying to reach.
Keyservers are wonderful, but few people actually check them. 

To make this verification easier for my own key, I've now uploaded it across 
multiple cloud services, and linked each of my social media accounts to a
different copy of the public key file.

This is meant to prevent a compromise of any one service (and the replacement of their copy of the key) from fooling everyone
else. I am now including my key's full fingerprint on my 
<a href="{{ site.baseurl }}/contact">Contact</a> page as well. This whole 
post is PGP-signed.

Also (as always), the site's source code is [on GitHub](https://github.com/KyCodeHuynh/kycodehuynh.github.io), which tracks any changes to it. While [rewriting Git history](https://www.atlassian.com/git/tutorials/rewriting-history/) is
certainly possible, there's little an attacker can do to prevent you from
cloning the site before a compromise. Then, any retrospective changes
to the Git history or files can be detected. 

Finally, there are two versions of the public key file floating about. 
One simply has another signature from a friend. I am leaving both versions
online to show that this update itself is not a malicious all-account takeover.
The [original one](/PGP.txt) is on this website, and most of the 
social media accounts have the updated one. Either one is fine to use.

- ---

Full PGP key fingerprint: 

```
49C0 32E0 6BD9 71B5 B4A0  DFE1 F6EA A503 A921 7457
```

Short ID: `A9217457`

Key type: 4096-bit RSA

-----BEGIN PGP SIGNATURE-----

iQIcBAEBCgAGBQJW7bmzAAoJEIh1ou8h3KMFBCYP/2RttkAismNg9EDxDdXwKhJL
w6R4WlOYIaehg7bdn5UpjIRRfrg3kqIqeDCw/Vzkik29MkgSKbdyLkVUu+HfJOka
0jVyMB7DXUWUh7q/KrVgse2JORyfjIo7Y6AW5rsBSvUjy5gdG2qtB1MDfV0WybL0
2BqWUpNBInr8wBlXRZdiYmJRhchqUtUV4rD7zerSevM+VU9jUyPUCxuFCAfte4m2
cdr3UVe165L0ClyR+EKX4K3pXhHq2sk/wQzpu9mY+J6MPNxbdOcrZrxnqOVr+w93
U211RnlzUNaDR/dEE+/Mr/kjotfylB89nFuStQ4IBTI2PrgC/o1ysJaS9lmi2I3G
vv9675oCegdtc1uyW0hU8fCKd+MRrlo0rHelKBxkbXt3r4No7YJ2+GNWbBxbS7Js
EPwvPr6uVat1xYfmuxRmTbgrA8pgNW2wFeeeRwHw5Ch5lh6cJe9Jx1pLO1SLOEnO
nKYdphkjtwlCxddgKGgXJrZhLgmLZl8JYr1xs/OHyhPnQOb222XnpIAoDcDle/6Z
9b5YRG0Voh7eKJOcnuCVTdGbMBCxILHdG63/XJcAoHDmOvR5ISfsecT1h8s2sVZt
v/QNFI0daXVGTectBkXqAMLkubpDDafGckYZDPAANxqObJlxtHZw5Q7sFoaWLo/Y
BGPP+UdF/gq/8kDz9Bhl
=CwT/
-----END PGP SIGNATURE-----
