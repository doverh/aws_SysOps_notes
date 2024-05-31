# DNS

Domain Name system. Provides IP address for website requests(DNS NAMES).
DNS Zone files contain website records.

How it works

Once a request is made to DNS, server locates the zone where that record is and returns the IP address for the given address.
1.Local and cache DNS files are queried first.
2.Then query is sent to DNS Resolver, home router or internet provides(non authoritative response)
3.Root Zone (OS) contains records with name service. Return .com NS
4..com registry contast DNS NS returns NS and returns the DNS record.
    