# Enumeration
Enumeration Techniques

# AIM:
To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
![Screenshot 2025-03-15 131810](https://github.com/user-attachments/assets/c8830d1e-b3da-4f73-a81c-3da13482c3c4)



filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
![Screenshot 2025-03-15 131940](https://github.com/user-attachments/assets/f2e4edbc-4fd6-4937-802d-3e7f3d22f387)




intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
![Screenshot 2025-03-15 132026](https://github.com/user-attachments/assets/a394e632-202a-4249-ad8e-c6c0fb6ede04)



inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
![Screenshot 2025-03-15 132106](https://github.com/user-attachments/assets/0098df0b-cb23-4c99-ab50-441333c41577)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
![Screenshot 2025-03-15 132222](https://github.com/user-attachments/assets/2d4756ae-b45b-435e-acc2-1e38ca6254ff)

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
![Screenshot 2025-03-15 132520](https://github.com/user-attachments/assets/51b1134f-9058-48cb-9cb2-c2df1227bcd3)

 
#DNS Enumeration



##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![lab3(1)](https://github.com/user-attachments/assets/8a490f77-097e-4706-ad84-cb51445ca080)







## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:
![lab3(3)](https://github.com/user-attachments/assets/90e0a2dc-983a-413a-ad74-2d3eacd9bbcf)



## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
![lab3(4)](https://github.com/user-attachments/assets/ad011e2d-02c4-4e8c-82c3-a5b20a64030b)



In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

  
 ##Output
![lab3(5)](https://github.com/user-attachments/assets/71f063ce-bde9-4c27-bc72-282a8ed71ed2)


## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
![lab3(6)](https://github.com/user-attachments/assets/de54d5b1-0dd7-455d-80f1-b7f65b5f987d)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

