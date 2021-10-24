# GoogleDork
---

**Link**
【HOW TO Use Google to Hack(Googledorks)](https://null-byte.wonderhowto.com/how-to/use-google-hack-googledorks-0163566/)

>  Google dork is an employee who unknowingly exposes sensitive corporate information on the Internet.

The concept of "Google Hacking" dates back to 2002, when Johnny Long began to **collect interesting Google search queries that uncovered vulnerable systems and/or sensitive information disclosures** - labeling them googleDorks. some people call it **googlehacking.**


_As a passive attack method, Google dorking can return usernames and passwords, email lists, sensitive documents, personally identifiable financial information (PIFI) and website vulnerabilities._

**That information can be used for any number of illegal activities, including cyberterrorism, industrial espionage,identity theft and cyberstalking**

**Terms**

1. **intitle**: Specifying intitle, will tell google to show only those pages that have the term in their html title.

Example: 

> intitle:"login page"




<br> 

2. **allintitle**: looks for all the specified terms in the title.

Example: 

> allintitle:"login page"

<br> 


3. **inurl**: specified term in the url


Example: 

> inurl:"login.php"
> inurl:index.php?id=

<br> 

A list of other words instead of inurl 

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




4. **allinurl**: but searches for all terms in the url.

Example: 

> allinurl:"login.php"

<br> 


5. **filetype**: Searches for specific file types.


Example: 

> filetype:pdf

<br> 


6. **ext**: Similar to filetype


Example: 

> ext:pdf 

<br> 




7. **intext**: Searches the content of the page. Somewhat like a plain google search.

Example: 

> intext:"index of /".

<br> 


8. **allintext**: searches for all terms to be present in the text.


Example: 

> allintext:"index of /".

<br> 



9. **site**: Limits the search to a specific site only


Example: 

> site:nullbyte.com

<br> 


10. **Define**: Google will define this massage and will look for what had this error for example,

Example: 

> define:"sql syntax error"

<br> 



Some techniques when using Google Dorks 


**1. Thank You For Your Order**



These are some Google Dorks which can affect our online business:

> 1. site:.com intitle:"Thank You For Your Order" intext:Click Here to Download
<br>

> 2. site:.com intitle:"Thank You For Your Purchase" intext:Click Here to Download

<br>

> 3. intitle:Thank you for your Purchase! intext:PLR OR MRR OR Package OR Bonus

<br>

> 4. inurl:/thankyou.html intitle:Thank you for your order! intext:Click Here to Download

<br>


**2. Vulnerability Approach**

Once you search website using above dorks, now its time to check whether the website is vulnerable to SQL injection or not, we simply put in a quote " ' " at the end of the url address.

So our site will look like this,


> http://www.site.com/index.php?id=123;


## Website links

1. **Known Google Dorks Hacks**: http://www.google-dorking.com/ 
2. **Google Hacking Database** : https://www.exploit-db.com/google-hacking-database
