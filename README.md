# Server hosting IP CIDRs

Create a list of server hosting service IP CIDRs by using a list of ASNs tagged from bgp.tools. 

This can be useful for blocking any traffic coming from a datacentre, like bots accessing an application intended for clients only (like game servers).

Note: it might also block certain traffic from VPN services.

## Server hosts listed include
- Google
- OVH
- DigitalOcean
- Akamai/linode
- Azure
- Rackspace
- Oracle Cloud
- Hetzner

... And more! See the full list here! https://bgp.tools/tags/vpsh

## Files

### `ip.txt`
A list of CIDRs from server hosting services. Updated on Sundays from [ip.guide](https://ip.guide/)

I'm using it for blocking bot traffic on my small game servers. Add `https://raw.githubusercontent.com/the-furry-hubofeverything/vps-ranges/refs/heads/main/ip.txt` to your firewall of choice.

### `vpsh.txt`
A list of ASNs tagged by bgp.tools for being server hosts. Updated on Fridays.


*Inspired by https://github.com/jhassine/server-ip-addresses.*
