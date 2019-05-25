# Information Gathering API
API for Information Gathering

## List API ##

- Reverse IP 		    : https://api.hack.co.id/reserveip/?ip=
- DNS History 		  : https://api.hack.co.id/dnshistory/?domain=
- Subdomain check 	: https://api.hack.co.id/subdomain/?domain=
- DNS Lookup 		    : https://api.hack.co.id/dnslookup/?domain=
- Response Headers 	: https://api.hack.co.id/header/?domain=
- IP Geolocation 	  : https://api.hack.co.id/ipgeo/?domain=
- IP Netblocks   	  : https://api.hack.co.id/netblocks/?domain=
- Reserve NS     	  : https://api.hack.co.id/reservens/?ns=
- Reserve MX        : https://api.hack.co.id/reservemx/?mx=

## Usage Example ##

Reverse IP

```bash
$ curl https://api.hack.co.id/reserveip/?ip=8.8.8.8
```

DNS History

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

Response Header

```bash
$ curl https://api.hack.co.id/header/?domain=google.com
```

IP Geolocation

```bash
$ curl https://api.hack.co.id/ipgeo/?domain=google.com
```

IP Netblocks

```bash
$ curl https://api.hack.co.id/netblocks/?domain=google.com
```

Reserve NS

```bash
$ curl https://api.hack.co.id/reservens/?ns=google.com
```

Reserve MX

```bash
$ curl https://api.hack.co.id/reservemx/?mx=mx.yandex.com
```

## Author

- [Teguh Aprianto](https://teguh.co)

## License

This project is open source and available under the [MIT License](LICENSE).
