# vibrantty.com → www redirect

The Vibrantty store lives on Cloudflare Pages at **www.vibrantty.com**.
The bare domain `vibrantty.com` is registered at Wix, which doesn't allow nameserver changes,
so its root A records point here (GitHub Pages) and this page forwards every URL to the www site.

Temporary: once the domain is transferred to Cloudflare (eligible 60 days after registration, early Dec 2026)
the root can be served by Pages directly and this repo can be deleted.
