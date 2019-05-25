# Information Gathering API
List of API for Information Gathering

## List API ##

- Reverse IP 		    
- DNS Record History 		  
- Subdomain check 	
- DNS Lookup 		    
- Response Headers 	
- IP Geolocation 	  
- IP Netblocks   	  
- Reverse NS     	  
- Reverse MX        

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

## Author

- [Teguh Aprianto](https://teguh.co)

## License

This project is open source and available under the [MIT License](LICENSE).
