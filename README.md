
# Vulnerabiliy for MIFX

these doc contains vulnerability web for MIFX 149.129.221.80

#check open port on ip using nmap
nmap -Pn -v 149.129.221.80
Starting Nmap 7.92 ( https://nmap.org ) at 2023-04-05 21:11 PDT
Initiating Parallel DNS resolution of 1 host. at 21:11
Completed Parallel DNS resolution of 1 host. at 21:11, 0.02s elapsed
Initiating Connect Scan at 21:11
Scanning 149.129.221.80 [1000 ports]
Discovered open port 80/tcp on 149.129.221.80
Stats: 0:00:01 elapsed; 0 hosts completed (1 up), 1 undergoing Connect Scan
Connect Scan Timing: About 0.80% done
Discovered open port 443/tcp on 149.129.221.80
Discovered open port 8008/tcp on 149.129.221.80
Discovered open port 2000/tcp on 149.129.221.80
Discovered open port 5060/tcp on 149.129.221.80
Completed Connect Scan at 21:11, 4.71s elapsed (1000 total ports)
Nmap scan report for 149.129.221.80
Host is up (0.0077s latency).
Not shown: 991 filtered tcp ports (no-response)
PORT     STATE  SERVICE
80/tcp   open   http
113/tcp  closed ident
389/tcp  closed ldap
443/tcp  open   https
636/tcp  closed ldapssl
2000/tcp open   cisco-sccp
3389/tcp closed ms-wbt-server
5060/tcp open   sip
8008/tcp open   http

Read data files from: /usr/bin/../share/nmap
Nmap done: 1 IP address (1 host up) scanned in 4.85 seconds

#check whois
whois 149.129.221.80

#
# ARIN WHOIS data and services are subject to the Terms of Use
# available at: https://www.arin.net/resources/registry/whois/tou/
#
# If you see inaccuracies in the results, please report at
# https://www.arin.net/resources/registry/whois/inaccuracy_reporting/
#
# Copyright 1997-2023, American Registry for Internet Numbers, Ltd.
#


NetRange:       149.129.0.0 - 149.129.255.255
CIDR:           149.129.0.0/16
NetName:        APNIC
NetHandle:      NET-149-129-0-0-1
Parent:         NET149 (NET-149-0-0-0-0)
NetType:        Early Registrations, Transferred to APNIC
OriginAS:       
Organization:   Asia Pacific Network Information Centre (APNIC)
RegDate:        2014-05-21
Updated:        2014-05-21


