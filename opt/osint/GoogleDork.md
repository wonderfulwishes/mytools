# GoogleDork
---

**Link:**【"HOW TO Use Google to Hack(Googledorks)"]("https://null-byte.wonderhowto.com/how-to/use-google-hack-googledorks-0163566/")

>  Google dork is an employee who unknowingly exposes sensitive corporate information on the Internet.

The concept of "Google Hacking" dates back to 2002, when Johnny Long began to **collect interesting Google search queries that uncovered vulnerable systems and/or sensitive information disclosures** - labeling them googleDorks. some people call it **googlehacking.**


_As a passive attack method, Google dorking can return usernames and passwords, email lists, sensitive documents, personally identifiable financial information (PIFI) and website vulnerabilities._

**That information can be used for any number of illegal activities, including cyberterrorism, industrial espionage,identity theft and cyberstalking**

**Terms**

1. **intitle**: Specifying intitle, will tell google to show only those pages that have the term in their html title.
2. **allintitle**: looks for all the specified terms in the title.
3. **inurl**: specified term in the url
4. **allinurl**: but searches for all terms in the url.
5. **filetype**: Searches for specific file types.
6. **ext**: Similar to filetype
7. **intext**: Searches the content of the page. Somewhat like a plain google search.
8. **allintext**: searches for all terms to be present in the text.
9. **site**: Limits the search to a specific site only
10. **Define**: Google will define this massage and will look for what had this error for example,

## What should you type in Google? 


```
intitle:"login page"
```

```
allintitle:"login page"
```

```
inurl:"login.php"
```

```
inurl:index.php?id=
```

```
a. intitle:
b. inurl:
c. intext:
d. define:
e. site:
f. phonebook:
g. maps:
h. book:
i. froogle:
j. info:
k. movie:
l. weather:
m. related:
n. link:
```

```
allinurl:"login.php"
```

```
filetype:pdf
```

```
ext:pdf 
```

```
intext:"index of /".
```

```
allintext:"index of /".
```

```
site:nullbyte.com
```

```
define:"sql syntax error"
```



## Some techniques when using Google Dorks 


**1. Thank You For Your Order**



These are some Google Dorks which can affect our online business:

```
site:.com intitle:"Thank You For Your Order" intext:Click Here to Download
```

```
site:.com intitle:"Thank You For Your Purchase" intext:Click Here to Download
```

```
intitle:Thank you for your Purchase! intext:PLR OR MRR OR Package OR Bonus
```


```
inurl:/thankyou.html intitle:Thank you for your order! intext:Click Here to Download
```


**2. Vulnerability Approach**

Once you search website using above dorks, now its time to check whether the website is vulnerable to SQL injection or not, we simply put in a quote " ' " at the end of the url address.

So our site will look like this,

```
http://www.site.com/index.php?id=123;
```


## Website links

1. **Known Google Dorks Hacks**: http://www.google-dorking.com/ 
2. **Google Hacking Database** : https://www.exploit-db.com/google-hacking-database
