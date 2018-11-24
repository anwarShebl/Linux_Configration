# Linux_Configration
This is the 6th project for udacity full stack nanodegree 



#IP Address of server:


   ip : 3.121.213.74 .

   hostname : ec2-3-121-213-74.eu-central-1.compute.amazonaws.com
 
  

private key of grader :

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC9hUblZx2LuyZKxy/OzWrDI9UkKfi9Gy7jPLyLARxspe/CV975slp7TDXslO2IDkOBwIBaeO16z3j0zY6gwc9vbVg+lTx/d0elzXCIQwH9xWIt5xLLzG+cN3CZ5E6rzEuH+eppCRnGuIV3lqaBRuXBkafxcepFw9Xo5aPi6QqBBejB5Kq47WKdswIl12bdGncwzeTbylN6r87R06FT00LVJhj5Lh3AS5Z+amlsiEmW5jIluqGnkDj8PRqshCoJuh1P/p8w8yAU5UmmOCbh3RSsg3zRrsGNwYhDIzAKdoc14p4rr0AtbKs62uwKL63lp2o5vI/S3IktQX7jYQ/HgHk7 anwar@anwar-Lenovo-Z50-70






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
 
 
 
 
