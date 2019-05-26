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

```json
[
  {
    "statusCode": 301,
    "statusMessage": "Moved Permanently",
    "headers": {
      "location": "http://www.google.com/",
      "content-type": "text/html; charset=UTF-8",
      "date": "Sun, 26 May 2019 20:00:36 GMT",
      "expires": "Sun, 26 May 2019 20:00:36 GMT",
      "cache-control": "private, max-age=2592000",
      "server": "gws",
      "content-length": "219",
      "x-xss-protection": "0",
      "x-frame-options": "SAMEORIGIN",
      "set-cookie": [
        "CONSENT=WP.27a518; expires=Fri, 01-Jan-2038 00:00:00 GMT; path=/; domain=.google.com"
      ],
      "p3p": "CP=\"This is not a P3P policy! See g.co/p3phelp for more info.\"",
      "connection": "close"
    },
    "timingPhases": {
      "wait": 0.4475460001267493,
      "dns": 13.128208999987692,
      "tcp": 1.9614629996940494,
      "firstByte": 4.075387000106275,
      "download": 0.27787999995052814,
      "total": 19.890484999865294
    },
    "body": "<HTML><HEAD><meta http-equiv=\"content-type\" content=\"text/html;charset=utf-8\">\n<TITLE>301 Moved</TITLE></HEAD><BODY>\n<H1>301 Moved</H1>\nThe document has moved\n<A HREF=\"http://www.google.com/\">here</A>.\r\n</BODY></HTML>\r\n"
  }
]
```

## Author

- [Teguh Aprianto](https://teguh.co)

## License

This project is open source and available under the [MIT License](LICENSE).
