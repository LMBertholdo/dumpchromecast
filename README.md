# ChromeCast dump

Pcap of chromecast trying to reach google resolver ipv4/ipv6 before reentering in 
DHCP provided resolver
4s to reenter asking for clients1.google.com (38s(google)-42s(dhcp)) when google resolver is blocked and keeps retrying from time to time.
in 38s try first google resolver and in 42s try dhcp provided resolver. It keeps trying google resolver from time to time (~25s?)
