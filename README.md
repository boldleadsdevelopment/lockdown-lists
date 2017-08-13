# Lockdown Lists
## An up to date set of public blacklists and country IP CIDR ranges


## Synopsis

This repository is updated daily with the latest public blacklists, bogons and
country CIDR ranges.  These lists are used by the
[Lockdown](https://github.com/boldleadsdevelopment/lockdown) cron job when
use_github is set to 1 in the configuration file or `git pull` is run from
`/etc/lockdown/lists/`.


## Sources

* [IPv4 Full Bogons](http://www.team-cymru.org/Services/Bogons/fullbogons-ipv4.txt)
* [IPv4 Full Bogons - alternate](https://www.countryipblocks.net/bogons/cidr_ipv4_bogons.txt)
* [The German's Blocklist](https://lists.blocklist.de/lists/all.txt)

* [Country Lists - All - Compressed](http://www.ipdeny.com/ipblocks/data/countries/all-zones.tar.gz)
* [Country Lists - Alternate -Singles](http://ipdeny.com/ipblocks/data/aggregated/xx-aggregated.zone)
* [Country Lists - Alternate - Singles](http://www.iwik.org/ipcountry/XX.cidr)


## Currently Unused but Useful

* [Country Lists IPv6](http://www.ipdeny.com/ipv6/ipaddresses/blocks/ipv6-all-zones.tar.gz)
* [GeoIP ASN](http://geolite.maxmind.com/download/geoip/database/GeoLite2-ASN-CSV.zip)
* [GeoIP Country](http://geolite.maxmind.com/download/geoip/database/GeoLite2-City-CSV.zip)
* [IPv6 Full Bogons - future use](http://www.team-cymru.org/Services/Bogons/fullbogons-ipv6.txt)
