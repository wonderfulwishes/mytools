# John, the Ripper 


*D: a password cracker used during pentesting exercises that can help IT staff spot weak passwords and poor password policies.*

UNIX crypt(3),Traditional DES-based,“bigcrypt”,BSDI extended DES-based,FreeBSD MD5-based (linux and Cisco IOS),OpenBSD Blowfish-based,Kerberos/AFS,Windows LM (DES-based),DES-based tripcodes,SHA-crypt hashes (newer versions of Fedora and Ubuntu),SHA-crypt and SUNMD5 hashes (Solaris)


```
unshadow passwd shadow > unshadowed.txt
john --wordlist=/usr/share/john/password.lst --rules unshadowed.txt
```
