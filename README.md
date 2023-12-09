# Country IP Blocks (Alternative Data)

These have a thousand and one uses but are surprisingly hard to come by in
bulk.

* IPv4 and IPv6 ranges available.
* Compiled from alternative data sources, in an attempt to improve accuracy.
* Deduplicated and subnets merged for efficiency.
* Simplified and sorted by country TLD.
* CIDR notation.
* Updated daily, commits only appear when there are changes.

**DO NOT DOWNLOAD THESE REPEATEDLY AND IN BULK!**

If you have infrastructure you'd like to use it for, download ONE COPY AS A GIT
REPOSITORY ONCE PER DAY and distribute it from your own infrastructure. It's
sad that I have to explicitly point this out but there have been instances of
operators of commercial infrastucture abusing this free resource. Repeated
excessive requests WILL get your IPs permanently blocked.

## Note on Geolocation Precision

There are more than a dozen commercial IP geolocation database providers, and
the accuracy of each provider is different. They get IP address information
from the RIRs, but the assignment changes regularly as some companies release
unwanted IP addresses and others obtain a new block of IP addresses.

The blocks of IP addresses assigned to many companies can, in turn, assign them
to their users however they want without geographic boundaries. This makes
pinpointing geolocation of an IP address rather difficult. The accuracy of
geolocation data differs by provider. You can generally expect a 95% to 99%
accuracy for the country level. The more granular you get, the less precise the
data becomes.

This projects is as accurate as the data gathered. Sometimes, the country
attached to an IP range is the one the registering company is located in. There
is no reliable way to determine the physical location of any IP without tracing
it separately.

## Further Resources

You may also be interested in my IPBL and other blocklists:

<https://ipbl.herrbischoff.com>
