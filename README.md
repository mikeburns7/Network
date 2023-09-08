# Network

| file | description |
|---|---|
|[EdgeRouter.ios](EdgeRouter.ios)| a best practice config for an edge router connect to ISP WAN. includes acl to management via ssh over the internet from explicit NOC public address. includes acl to allow icmp from NOC address and drop all other icmp.|
|[switch.ios](switch.ios)| best practice edge switch config that can be used an a DMZ switch. same management config as router. include acl to access management from internal network |
|[Get-NSLookup.ps1](Get-NSLookup.ps1)|The script imports a CSV file with a list of IP addresses, performs an NSlookup on each IP address, and outputs the IP address, DNS name, destination port, and hits to a CSV file. Can be used to review ip based traffic from an endpoint, convert ips to dns entries and make an explicit firewall config. Can also be used to gain more information about an IP during a incident response situation.  |
|[check-networkSlowness.ps1](check-networkSlowness.ps1)|The script will perform DNS lookups and ping commands to mulitple servers and report results for each. Can be embedded into other scripts to provide statistics on network performance.|
