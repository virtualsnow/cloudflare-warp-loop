## Cloudflare Warp Loop

Cloudflare is:
- Highly centralized, very popular, and built on _trust_.
- Making much of the web unusable for hardened browsers & Tor user (_yes, even with the recent improvements_).
- Likely a state censorship/monitoring tool.
- Entirely unneeded by most of it's users.

With the introduction of their "free" proxy, Warp, they can be on your line even when you don't opt-in as the website owner. But now you have a chance to impersonate them; the tables have turned.

__Make your Cloudflare Warp users fill out pointless reCAPTCHAs and give them some confusing Cloudflare branded messages with just a tiny Haproxy addition.__

![error page example](https://raw.githubusercontent.com/virtualsnow/cloudflare-warp-loop/master/sample-page.png)


## Want to know more?

 - [Cloudflare's announcement of Warp and discussion of monetization.](https://blog.cloudflare.com/1111-warp-better-vpn/)
 - [The Great Cloudwall / Stop Cloudflare](https://git.openprivacy.ca/you/stop_cloudflare)
 - [I don’t trust Cloudflare’s 1.1.1.1 App and Warp VPN](https://blog.kareldonk.com/i-dont-trust-cloudflares-1-1-1-1-app-and-warp-vpn/)
 - [Warp packet storms as a feature](https://community.cloudflare.com/t/my-server-keeps-getting-tcp-rst-packets-from-cloudflare-warp-addresses/122763)
