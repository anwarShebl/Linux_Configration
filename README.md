# Linux_Configration
  This is the 6th project for udacity full stack nanodegree 
   Hostname and ip 
   
   Ip : 3.121.213.74 .
  Hostname : ec2-3-121-213-74.eu-central-1.compute.amazonaws.com
  
  
  software installed
  
  1-Apache webserver using Flask framework and bootstrap formatting.
  2-Data is saved to a Postgresql database on the server.
  
  
Configurations made

   1- Root access disabled
   2- Postgresql user called 'catalog' added, with password 'REDACTED'
   3- An additional superuser called 'grader' was added to allow Udacity grader to access the server. This user has since been REMOVED
   4- Password access to the server disabled
   5- Access limited to private rsa key authentication
   6- Enabled firewall to restrict ports to 2200 for ssh, 80 for webservice, 123 for NTP. All others ports have been blocked.
   7 -The ssh port is 2200 - a non-default port. The normal port (22) has been disabled.
   
   Third party resources
   1 - https://github.com/mulligan121/Udacity-Linux-Configuration 
   2 - https://github.com/chuanqin3/udacity-linux-configuration
