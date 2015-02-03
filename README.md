# SQL-Scanner
SQL Scanner via Google
This is a very small perl script that requires the Google::Search and LWP::Simple modules from CPAN.

Usage should be pretty obvious, but here is an example or two:

./scan.pl inurl:".php?cat="+intext:"/Buy

perl scan.pl inurl:".php?cat="+intext:"/Buy sqli.txt
