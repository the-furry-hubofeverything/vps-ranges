# Server hosting IP CIDRs

Create a list of server hosting service IP CIDRs by using a list of ASNs tagged from bgp.tools (https://bgp.tools/tags/vpsh.csv). Inspired by https://github.com/jhassine/server-ip-addresses.

Github workflows are set up to update this list every week.

Can be useful for blocking bot traffic, but might also block VPN traffic as well.

## Files

### `ip.txt`
A list of CIDRs from server hosting services. Updated weekly from [ip.guide](https://ip.guide/)

I'm using it for blocking bot traffic on my small game servers. Add `https://raw.githubusercontent.com/the-furry-hubofeverything/vps-ranges/refs/heads/main/ip.txt` to your firewall of choice.

### `vpsh.txt`
A list of ASNs tagged by bgp.tools for being server hosts. Updated on odd months.
