# Information Gathering API [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
List of API for Information Gathering

## List API ##

- Reverse IP 		    
- DNS Record History 		  
- Subdomain Checker 	
- DNS Lookup 		    
- Get HTTP Headers  	
- IP Geolocation 	  
- IP Netblocks   	  
- Reverse NS     	  
- Reverse MX  
- SSL Checker
- Website Scanner
- IP Address Blacklist Checker
- SPF Checker
- Port Scanner
- Website IPv6 Support Checker

## Usage Example ##

Reverse IP

```bash
$ curl https://api.hack.co.id/reverseip/?ip=8.8.8.8
```

DNS Record History

```bash
$ curl https://api.hack.co.id/dnshistory/?domain=google.com
```

Subdomain Check

```bash
$ curl https://api.hack.co.id/subdomain/?domain=google.com
```

DNS Lookup

```bash
$ curl https://api.hack.co.id/dnslookup/?domain=google.com
```

Get HTTP Headers 

```bash
$ curl https://api.hack.co.id/header/?domain=https://google.com
```

IP Geolocation

```bash
$ curl https://api.hack.co.id/ipgeo/?domain=google.com
```

IP Netblocks

```bash
$ curl https://api.hack.co.id/netblocks/?ip=8.8.8.8
```

Reverse NS

```bash
$ curl https://api.hack.co.id/reversens/?nameserver=ns1.google.com
```

Reverse MX

```bash
$ curl https://api.hack.co.id/reversemx/?mx=mx.yandex.com
```

SSL Checker

```bash
$ curl https://api.hack.co.id/ssl/?domain=google.com
```

Website Scanner

```bash
$ curl https://api.hack.co.id/web/?domain=google.com
```

IP Address Blacklist Checker

```bash
$ curl https://api.hack.co.id/blacklist/?ip=8.8.8.8
```

SPF Checker

```bash
$ curl https://api.hack.co.id/spf/?domain=google.com
```

Port Scanner 

```bash
$ curl https://api.hack.co.id/port/?ip=8.8.8.8&port=80
```

Website IPv6 Support Checker

```bash
$ curl https://api.hack.co.id/ipv6/?domain=google.com
```

## Response Example from Get HTTP Header ##

```bash
$ curl https://api.hack.co.id/header/?domain=https://google.com
```

![Get HTTP Header Response](https://raw.githubusercontent.com/secgron/Information-Gathering-API/master/screenshoot.png)

## Author

- [Teguh Aprianto](https://teguh.co)

## License

This project is open source and available under the [MIT License](LICENSE).
