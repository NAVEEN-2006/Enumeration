# Enumeration
Enumeration Techniques
```
DEVELOPED BY : NAVEEN KUMAR S
REG NO       : 212223040129

# Explore Google hacking and enumeration 

## AIM:

To use Google for gathering information and perform enumeration of targets

### STEPS:

#### Step 1:

Install kali linux either in partition or virtual box or in live mode

#### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


#### Step 3:
Open terminal and try execute some kali linux commands

### Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

### Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

#### site:
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain youtube.com

![image](https://github.com/user-attachments/assets/368454db-ce82-4fcd-a0f6-08d033f87567)




#### filetype: 

![image](https://github.com/user-attachments/assets/bc7186a5-1341-47f0-842a-c6b6a44ab8c6)

This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

#### intext:
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![image](https://github.com/user-attachments/assets/3addc3fb-2a41-4499-be2f-05eb9d40ea7f)



#### inurl:
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![image](https://github.com/user-attachments/assets/bc2608b8-4901-4852-9558-7b62ad3abae5)


#### intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![image](https://github.com/user-attachments/assets/149ab166-27af-45ec-a86c-28d6196230cc)




#### link:
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![image](https://github.com/user-attachments/assets/67b1d156-d7de-4a06-bd87-2b5c356e9e37)

#### cache:
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![image](https://github.com/user-attachments/assets/7b747a98-b86a-4f28-9214-cd1d4855fd23)


 
### DNS Enumeration


#### DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
#### OUTPUT:
![image](https://github.com/user-attachments/assets/f8548abd-9c7c-4043-b036-81ea33a91050)


#### dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
![image](https://github.com/user-attachments/assets/5e011ce5-ea86-4049-ad88-b84debc5d21f)
![image](https://github.com/user-attachments/assets/3d619773-d82b-49c2-939c-d267cba8c114)
![image](https://github.com/user-attachments/assets/370f5211-c67f-4a76-88df-54f2a1ba63ae)


#### smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
select any username in the first column of the above file and check the same
![image](https://github.com/user-attachments/assets/2f5bd015-6475-4974-b2ea-7918fcafba1b)



#### Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
#### Output
  ![image](https://github.com/user-attachments/assets/e387927e-43ad-4604-9f52-b311efdbde34)


#### nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


#### OUTPUT:
 
![image](https://github.com/user-attachments/assets/f73b4caf-220e-4046-85fd-8f808f0b6bca)

 

### RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

