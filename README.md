# wiki-nginx-conf
Our nginx configuration for MediaWiki.

WARNING: since MediaWiki's MobileFrontend doesn't support file cache, we moved to a different configuration which involves `proxy_cache` and is quite specific to our servers, so this one is no longer maintained. It's still useful (and very efficient) for those who have simpler setups and lighter request loads.
