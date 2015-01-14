# Maintenance-Mode-HTACCESS
An .htaccess file to make your Apache server be in maintenance except for your IP address.

I have found this out on the web in various forms and thought I would make a snippet. 

## Instructions:
+ Change this page to your IP 

		111\.222\.333\.444

You need to change to your IP address that you are coming from. If you are accessing the server by a private IP like 192.168.X.X then it should be your internal IP. If you are accessing it externally make sure you use your external Ip. You can get this from whatsmyip.net or something similar.
### Important: Make sure you keep the \'s in front of the .'s!!!

+ Change this part on lines 8 and 11 to your maintenance page file name

		maintenance\.html 

You need to change lines 8 and 11 to match your maintenance page. That can be anything.
### Important: Make sure you keep the \'s in front of the .'s!!!
