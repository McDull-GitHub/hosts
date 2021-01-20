### A simple DNS proxy server, support wilcard hosts, IPv6, cache and so on. 

Usage: Edit /etc/hosts
```
127.0.0.1 *.local
127.0.0.1 *.google.com
```
`$ sudo python dns.py -s 8.8.8.8`
