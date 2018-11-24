# Linux_Configration
This is the 6th project for udacity full stack nanodegree 



#IP Address of server:


   ip : 3.121.213.74 .

   hostname : ec2-3-121-213-74.eu-central-1.compute.amazonaws.com
 
  

private key of grader :


-----BEGIN RSA PRIVATE KEY-----

MIIEowIBAAKCAQEAvYVG5Wcdi7smSscvzs1qwyPVJCn4vRsu4zy8iwEcbKXvwlfe
+bJae0w17JTtiA5DgcCAWnjtes949M2OoMHPb21YPpU8f3dHpc1wiEMB/cViLecS
y8xvnDdwmeROq8xLh/nqaQkZxriFd5amgUblwZGn8XHqRcPV6OWj4ukKgQXoweSq
uO1inbMCJddm3Rp3MM3k28pTeq/O0dOhU9NC1SYY+S4dwEuWfmppbIhJluYyJbqh
p5A4/D0arIQqCbodT/6fMPMgFOVJpjgm4d0UrIN80a7BjcGIQyMwCnaHNeKeK69A
LWyrOtrsCi+t5adqObyP0tyJLUF+42EPx4B5OwIDAQABAoIBAE++nK46TTxWay5b
0cn6tUmW8kBdSMSJg5kqHUuAFC3DRLdJshDu8xOeZbI+mBP/rHgUP+3RpFtgoUyg
kbsi0d3Y7KCouuQHlKY3Y3pyd4wIWd9ms4n9Y5kf2slmP5QaSk3U4sV/htEPI1nG
khkjc9mXKEt321Ovq3pr5iG8XSccUqLAXdRYWY8vcwWr2KrTOd76JQrfuWYDJdLC
PxLSyJqFNTNpaVAZdLRgikaYUwAgu5u2a9NLKc8fg+9A8bH93hLW2nHe6/4vz41e
Olu1pS+1p6W4shFdzkmdqlpjH/sxqQojzIAMCEozff4yI9kbPCy0mmZSdor/DsPz
QQCqH0ECgYEA+UZEv+vXG4DQlNlJE56CmNw17YGD+56eXpNG+p9gC1vktDRjC+3Y
BcBb9k2+9PtTc5NO2s/Qns98tAtE+6r3KGLtZ+D++DHvHQ3rDrAM8IwZ4O9LCcKW
dgDW099ISw2XoP4i5HPyJJODxDZU/jGfJf0qfNcQ78enS6Gz1oMgRzUCgYEAwqJK
SAmOwlOvPHUw1nzLEccApWOWljDp5H4MJsTrkoz05pUgW+1PgEZv5rBAltmgTPnI
UXv2lkqrR9H+yEyk87swIvTQmfz+g12TgKvCnboerdNiYhHfP1g+qHDd7gsqMp1/
q9LMg6AG8eTJNuoIg7xgsdCGyEiDAy11CBDOHK8CgYEA5hEDzPrXuyul12vANZpb
wMemAkJCVU6trm5R2WiVVYaHzAZ5z/3CHnTOq8JP133LJOW1puCdFKY921J3ZawC
l8TOhsyzptE3duJsq06zcqRsEh3pbOWqxti5bi0rZRHze4RzIdUdjMKVn9fhlAaq
c35442X/3L6x2m0xNXAqr20CgYBoJ672k97IkT3ibZg//7IwBj2LRBrurqhLtURN
bu3dk/7ucflKGFmF/KufWMyHrVhCOR0AtgTEcprsKS1eBN307EQbQMVs0l1k8Suh
HMld3J7USJ2Ke6PrYw7M1vF8lI71XSFYUstM2NM+mT8wWtdJoAJixYOLJHqvtaC+
OzgBUwKBgGuPb1wzFyMdz5Dx3U+2Srn3ETGnP1fzjczilTG9hMXzwOZUd4Tfkpuv
oepAUqsnZzazwcryOzBkUejgyD5iLseXOBm2YlMSfJ2zhvq4ddiIxaDZr9v1m6sP
TOwdm9jOqb3EPYpN1f3cuSsqQPPVjAwpZna0mYvrkE/0s65+WWLd

-----END RSA PRIVATE KEY-----





 #software installed
 
   1 - Apache webserver using Flask framework and bootstrap formatting.
 
   2 - Data is saved to a Postgresql database on the server.
 
 
 
 #Configurations made
 
   1. Root access disabled
 
   2. Postgresql user called 'catalog' added, with password 'password'

   3. An additional superuser called 'grader' with password 'grader01000' was added to allow Udacity grader to access the server

   4. Password access to the server disabled

   5. Access limited to private rsa key authentication

   6. Enabled firewall to restrict ports to 2200 for ssh, 80 for webservice, 123 for NTP. All others ports have been blocked.

   7. The ssh port is 2200 - a non-default port. The normal port (22) has been disabled.
   

 #Third Party Resources
  
   1. https://github.com/mulligan121/Udacity-Linux-Configuration

   2. https://github.com/mulligan121/Udacity-Linux-Configuration
 
 
 
 
