
First installed Python3 in my system.


1)The program is going to print from both the links - https://volon.io/robot.txt and https://whitehouse.gov/robot.txt.
 First I take the data from the first link and split the data from '\n'.
 Then I take the data from the second link and split the data from '\n'.
 I create the two functions to check Similar lines and Unique lines.
a) Similar lines.
b) Unique lines.
c) All lines
I used some library in python3
urllib.request and import.io and smtplib.  Descriptions about these library are given below.  
 
2) I ceate a function send_mail(massage, sender_mailId) and send the mail to another maiil-Id along with message.You'll receive the message in your inbox or spam folder successfully.

What I had done and what library I used.

=> The urllib.request module defines functions and classes which help in opening URLs (mostly HTTP).  

=> The Import.io is a web-based platform for extracting data from websites without writing any code.


=> The import smtplib module defines an SMTP client session object that can be used to send mail to any Internet machine with an SMTP or ESMTP   listener daemon. 
SMTP stands for Simple Mail Transfer Protocol. 
The smtplib modules is useful for communicating with mail servers to send mail.
Sending mail is done with Python's smtplib using an SMTP server. 

utf-8 -  To treat Unicode strings identically to byte strings. 



outrput in my machine :-


print all data from both site :- ['User-agent: *', 'Disallow: /wp-admin/', 'Allow: /wp-admin/admin-ajax.php', '', 'Sitemap: https://volon.io/sitemap.xml', 'Sitemap: https://volon.io/news-sitemap.xml', 'User-agent: *', 'Disallow: /wp-admin/', 'Allow: /wp-admin/admin-ajax.php']

similar data from both site:- ['User-agent: *', 'Disallow: /wp-admin/', 'Allow: /wp-admin/admin-ajax.php']

print all unique data from both site:- ['Sitemap: https://volon.io/sitemap.xml', 'Sitemap: https://volon.io/news-sitemap.xml']



































