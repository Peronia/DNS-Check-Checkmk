# DYNDNS-Check-Checkmk
All checks use the bash and the defaultpath for the checks is /usr
Don't forget to make them executable.

## check_dns_website
This check checks, if an ipaddress from a website are the same as the one from a dyndnsdomain.<br>
The check_dns_website uses 3 types of placeholders:<br>
DOMAINTOCHECK = The domain that should be checked, e. g. google.com<br>
DYNDNSDOMAIN = The domain that the dyndns update contains, e. g. mydyndns.com<br>
NAMEOFWEBSITE = The name of the website. Can be anything, only for naming and output
