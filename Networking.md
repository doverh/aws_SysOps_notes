# DNS

Domain Name system. Provides IP address for website requests(DNS NAMES).
DNS Zone files contain website records.There are 13 root servers managed by 12 large organizations.Root zone is managed by IANA. DNS Record Type A converts a HOST into an IPv4 Address. DNS Record type NS is how the root zone delegates control of .org to the .org registry. Registry maintains the zones for a TLD (e.g .ORG)  
Registar has relationships with the .org TLD zone manager allowing domain registration

How it works

Once a request is made to DNS, server locates the zone where that record is and returns the IP address for the given address.
1.Local and cache DNS files are queried first.
2.Then query is sent to DNS Resolver, home router or internet provides(non authoritative response)
3.Root Zone (OS) contains records with name service. Return .com NS
4. .com registry contast DNS NS returns NS and returns the DNS record.
5. IP CIDR of a default VPC is 172.31.0.0/16
