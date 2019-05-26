# Information Gathering API
List of API for Information Gathering

## List API ##

- Reverse IP 		    
- DNS Record History 		  
- Subdomain check 	
- DNS Lookup 		    
- Get HTTP Headers  	
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

Get HTTP Headers 

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

## Response Example from Reverse IP ##

```json
{
   "current_page": "1",
   "size": 7,
   "result": [
      {
         "name": "engelmeier.info",
         "first_seen": "1530492412",
         "last_visit": "1532914202"
      },
      {
         "name": "expired86.namebrightdns.com",
         "first_seen": "1530911981",
         "last_visit": "1532721797"
      },
      {
         "name": "kathrynmcevoy.com",
         "first_seen": "1530513133",
         "last_visit": "1532933936"
      },
      {
         "name": "trufidelabs.com",
         "first_seen": "1530555136",
         "last_visit": "1532978406"
      },
      {
         "name": "tunnelguru.net",
         "first_seen": "1530556835",
         "last_visit": "1532978092"
      },
      {
         "name": "www.tunnelguru.net",
         "first_seen": "1530956327",
         "last_visit": "1530956327"
      },
      {
         "name": "zech.dyndns.org",
         "first_seen": "1530575988",
         "last_visit": "1532999862"
      }
   ]
}
```

## Author

- [Teguh Aprianto](https://teguh.co)

## License

This project is open source and available under the [MIT License](LICENSE).
