# WIP Infrastructure 2.0

Goals:
* Update our infra regarding current status
* Move from `web3privacy.info` to `w3pn.org` domain
* Make more resilient & safe

## DNS

Let's move DNS back to Git repo management so that multiple people can edit the records.

* Domains: `web3privacy.info`, `w3pn.org`
* Repo: `@web3privacy/dns-zones` (private)
* Registrar: [Porkbun](https://porkbun.com/)
* Deployment: [Bacon](https://github.com/paulopacitti/bacon) & GitHub Actions

## Servers

TODO

## Services
### Discontinued services

| Domain | Hosted | Resolution |
| --- | --- | --- |
| [matrix.web3privacy.info](https://matrix.web3privacy.info/) | Gwei.cz | Discontinued. Only the main channel on matrix.org will remain |
| [forum.web3privacy.info](http://forum.web3privacy.info) | Gwei.cz | Discontinued. Replaced by Zulip ([commons.w3pn.org](https://commons.w3pn.org/)). |

### Services to migration

| Current Domain | New domain | Service | Hosted |
| --- | --- | --- | --- |
| [vault.web3privacy.info](https://vault.web3privacy.info) | `vault.w3pn.org` | Vaultwarden, password manager | Gwei.cz |
| [status.web3privacy.info](https://status.web3privacy.info) | `status.w3pn.org` | Uptime Kuma, monitoring tool | Gwei.cz |
| [n8n.web3privacy.info](https://n8n.web3privacy.info/) | `n8n.w3pn.org` | n8n, Workflow automatization | Mf |

### New services

| Domain | Info | Server |
| --- | --- | --- |
| [commons.w3pn.org](https://commons.w3pn.org/) | Zulip, Self-hosted forum/chat | |
| `seed.w3pn.org` | Radicle [Seed Node](https://radicle.xyz/guides/seeder) | |
| `pds.w3pn.org` | Bluesky/AT Protocol [Personal Data Server](https://atproto.com/guides/self-hosting) (PDS) | |
| `photos.w3pn.org` | [Immich](https://immich.app/), photo & video management | |
| `notes.w3pn.org` | [CodiMD](https://github.com/hackmdio/codimd), markdown notes | |
| `meet.w3pn.org` | [Jitsi](https://jitsi.org/), video conferencing software | |
| `ci.w3pn.org` | [Woodpecker](https://woodpecker-ci.org/), CI/CD engine | |
| `grafana.w3pn.org` | [Grafana](https://grafana.com/grafana/), Visualisations dashboards | |
| `sftp.w3pn.org` | [SFTPGo]([https://](https://sftpgo.com/)), flexible file server | |
| `dns.w3pn.org` | [DNSCrypt](https://www.dnscrypt.org/), secure DNS resolver | |
| `tor.w3pn.org` | [Tor relay](https://community.torproject.org/relay/) | |
| `btcpay.w3pn.org` | [BTCPayServer](https://btcpayserver.org/) | |
| `frp.w3pn.org` | [frp](https://github.com/fatedier/frp), fast reverse-proxy | |
