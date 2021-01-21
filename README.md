# DYNDNS-Check-Checkmk
All checks use the bash and the defaultpath for the checks is /usr
Don't forget to make them executable.

## check_dns_website
This check checks if an ipaddress from a website are the same as the one from a dyndnsdomain.<br>
There are 3 types of placeholders:<br>
`DOMAINTOCHECK` = The domain that should be checked, e. g. google.com<br>
`DYNDNSDOMAIN` = The domain that the dyndns update contains, e. g. mydyndns.com<br>
`NAMEOFWEBSITE` = The name of the website. Can be anything, only for naming and output<br>
<br>
## check_dyndns
This script checks if the ipaddress from your gateway is equal to your dyndnsdomain.<br>
I use https://v4.ident.me for that, you can replace it if you want.<br>
There is only one placeholder:<br>
`DYNDNSDOMAIN` = The domain that the dyndns update contains and should be checked, e. g. mydyndns.com<br>
