# Linux_Configration
This is the 6th project for udacity full stack nanodegree 



#IP Address of server:


   ip : 3.121.213.74 .

   hostname : ec2-3-121-213-74.eu-central-1.compute.amazonaws.com
   private key :
   
   -----BEGIN RSA PRIVATE KEY-----
MIIEowIBAAKCAQEAw09nUTaP9sUKDc8n1OziBsIsqn95MarccXqGMh2DEYAn+gj8
9cOmalnWUZ2R8mKj03sq/z4A+ScSrqgAqxRQ79LCRxac30ERHy/VnKUCz+cgB3Zv
K+/OZAUb2lyb5ShBnWw2t42n+13Po5PSx6ycxKxirmxlMDji2LOTumGBOQz4R/7g
zt6+spGkeZ+VGMF5zHcaAiwxWrSl/joXfzyCq3FoZmXTO9isGHNaoWhEIK7HFC0L
BWDYQJQhJUbg9fIAArQwW6VfyDTsSPF4iZFias1f1qbSC1xnz1XCmTuWBS10Q6Je
zpAfQHv7jlKGx0ValyaIkCOzV0DkaV6DuUd/jQIDAQABAoIBAEGFh+Gk7lMY8zCC
yJgUCBfAWH+yWBQjf+TJ9+8kG25pkf+9uC8yvcd77/xdYjLwiIlQDrKmOGldhFT3
o5HBNQ3fpLF4kpQLHhVaVM1CRlk87m/SeaVBw/mmBRwSaXJNOQX44bpeWXZomFoG
I3Y9IDKSqmBdmOy+iMuuIucqAtICQs9c7EwF2kC8ezLPXOvs0bDVqbo2/1CH1drG
QFDtFnO4mHp4/ILOUpTCPG6s5BCY5bucMNzwYgj+xfwUva62op/vZ+F705WyVhbr
GYCRwMW9RU1zpTgvCzjXXxdj7W14FleQx7nCc9rOlald7Xj7OWWymQlzN3k/YcbE
TG80bLkCgYEA+4BbkUKdvSXisLCUsmq+Mw5OsdSHMIybwHxHoBmu4dNHBKRoYqQC
RCWvrOyMNycN5NAg2CKrlgfGLpnNDeh8AKQ/vqdd3bMSkD3PWatD65yM8f5lfcXd
ykJ7y6oC/Q0zwNmrhuen0ogM9U3JiXswz4BfnEEPs6t2DISA1bcasb8CgYEAxs2+
DH30IXJWLlCvmfYFWnis4h0CQICDVuM3zdOMGTtJ2U0F28PLcdswF2vcaieQRqcL
PQyQhdst24DlFvEvp0/mWH8p8Zy3GX8RcRm9t7y9KxgfNIJde/KWemI/7HAw/Nf2
JyqgItWzdghquqky89NcEj5muoZh8b3P1TsCibMCgYApzG9rePLWWNGQJAjSjkMG
IT6a94NwYi4Qk5cj2KDkD0UiVGC05CUsRkcoKjgzgl4gxSZwRXLXAHvDivQ1d4oE
YUfm29IR4o0XQ+6OLJShN+eE4I7llFkEIICKnLraa7NKPeLwDNgreUkOC9uO6dZ2
5hL92SJO7hQ0iGERI9lf6QKBgDSrf6VpnUtbMm/02oEsyABPJmaFjvot0h4r9rXm
TSDGL2uN13aA6h6RFq2t2uiY8MV3LigPcx6zkfOss4UfgyONrJZXonIrtergWmuf
iT7rlyaarnHH9CKJg8qKyyrGEoR6ZvG7fk+cVH55/mTTvPcSUTtYIvlZ7wsP4cc5
ahO3AoGBAO6bUfRhrrAKuKQpZ5HHmcvPuuWV008jkTugzBA2cL4N6US7t1Z3xxlW
R2WUAXMZIhUR2zpZxv4ub9F4Y4JylilIquNvcc0f28bzcjb1V9/+IW7351npzgQQ
VdFjvuB9TlubaceJOLG5qc2ok5oNTEbIr4wgCtTfFkKO3BBx+QF0
-----END RSA PRIVATE KEY-----





 #software installed
 
   1 - Apache webserver using Flask framework and bootstrap formatting.
 
   2 - Data is saved to a Postgresql database on the server.
 
 
 
 #Configurations made
 
   1. Root access disabled
 
   2. Postgresql user called 'catalog' added, with password 'password'

   3. An additional superuser called 'grader' was added to allow Udacity grader to access the server

   4. Password access to the server disabled

   5. Access limited to private rsa key authentication

   6. Enabled firewall to restrict ports to 2200 for ssh, 80 for webservice, 123 for NTP. All others ports have been blocked.

   7. The ssh port is 2200 - a non-default port. The normal port (22) has been disabled.
   

 #Third Party Resources
  
   1. https://github.com/mulligan121/Udacity-Linux-Configuration

   2. https://github.com/mulligan121/Udacity-Linux-Configuration
 
 
 
 
