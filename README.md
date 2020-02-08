# unbound-ads-filters

Host files to Unbound format like:

   > local-zone: "domain.com" always_nxdomain

[Unbound](https://nlnetlabs.nl/projects/unbound/download/) is a validating, recursive and caching DNS resolver.

This repository contain coverted host files from reputable link/hosts files in https://github.com/StevenBlack/hosts , https://github.com/DNSCrypt/dnscrypt-proxy/wiki/Public-blacklists and others, merges them into a unified hosts file with duplicates removed.

 The files are updated weekly.


List of all files variants

 - unbound-coin.host
 - unbound-tracking.host
 - unbound-ads-coin-tracking.host	 
 - unbound-ads-coin.host	
 - unbound-ads-fakenews-gambling-coin.host
 - unbound-ads-fakenews-gambling-porn-social.host
 - unbound-ads-fakenews-gambling-porn.host
 - unbound-ads-fakenews-gambling.host 
 - unbound-ads-fakenews.host
 - unbound-ads-porn.host 
 - unbound-ads.host 
 
 Download your favorite flavour to **/etc/unbound** and add the **include** to **unbound.conf**
 
  > include: "/etc/unbound/unbound-example.host"
  
 
  
  **That's all !**

