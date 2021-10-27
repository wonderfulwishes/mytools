# Hashcat 

*D: Hashcat is a password cracking tool used for licit and illicit purposes. Hashat is a particularly fast, efficient, and versatile hacking tool that assists brute-force attacks by conducting them with hash values of passwords that the tool is guessing or applying.*

1. Copy the hash into a file: hash.txt 

```
hashcat -m 1600 -o output.txt hash.txt /home/kali/Desktop/crackstation-human-only.txt
```

1. m: the id number that represents what kind of hash
2. o : represents the output of the file
3. hash.txt: represents the file name that is brute forcing
4. realhuman_phill.txt: represents the dictionary list file name
