# IPWhois.net Blacklist Feed (daily mirror)

Daily GitHub mirror of the [IPWhois.net community blacklist](https://ipwhois.net/blacklist) feed.

- **Canonical source (updated every 30 min):** https://bl.ipwhois.net/feed.txt
- **This mirror:** [`feed.txt`](feed.txt), refreshed daily
- **First-party data only:** community reports, fail2ban/CSF/IDS integrations
  and honeypots. No re-aggregated third-party feeds, so aggregators can
  ingest it without circular data.
- Criteria: confidence >= 50, seen in the last 90 days, one IPv4 per line.
- Free to use with attribution.

Docs and integration guides (fail2ban, CSF, Nginx, WordPress, ...):
[ipwhois.net/blacklist/docs](https://ipwhois.net/blacklist/docs)

Report an abusive IP: [ipwhois.net/blacklist/report](https://ipwhois.net/blacklist/report)

Code examples: [ipwhois-blacklist-examples](https://github.com/brkicsivan-wq/ipwhois-blacklist-examples)
