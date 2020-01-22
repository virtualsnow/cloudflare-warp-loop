##Cloudflare Warp Loop

Cloudflare is:
- Highly centralized, very popular, and built on _trust_.
- Making much of the web unusable for hardened browsers & Tor user (_yes, even with the recent improvements_).
- Likely a state censorship/monitoring tool.
- Entirely unneeded by most of it's users.

With the introduction of their "free" proxy, Warp, they can be on your line even when you don't opt-in as the website owner. But now you have a chance to impersonate them; the tables have turned.

Make your Cloudflare Warp users fill out pointless reCAPTCHAs and give them some confusing Cloudflare branded messages with just a tiny Haproxy.

![error page example](https://raw.githubusercontent.com/virtualsnow/cloudflare-warp-loop/master/sample-page.png)
