# udf_root
MySQL User-Defined function Dynamic Library Local Privilege Escalation

*** MySQL User-Defined (Linux) x32 / x86_64 sys_exec function local privilege escalation exploit *** 

  
UDF lib shellcodes retrieved from metasploit 
(there are windows .dll libraries within metasploit as well so this could be easily ported to Windows) 

Based on the famous raptor_udf.c by Marco Ivaldi (EDB ID: 1518)  
CVE: N/A  
References:  
https://dev.mysql.com/doc/refman/5.5/en/create-function-udf.html  
https://www.exploit-db.com/exploits/1518  
https://www.exploit-db.com/papers/44139/ - MySQL UDF Exploitation by Osanda Malith Jayathissa (@OsandaMalith)  

Tested on 3.16.0-6-amd64 #1 SMP Debian 3.16.57-2 (2018-07-14) x86_64 GNU/Linux and mysql  Ver 14.14 Distrib 5.5.60, for debian-linux-gnu (x86_64)

@d7x_real  
https://d7x.promiselabs.net  
https://www.promiselabs.net  
