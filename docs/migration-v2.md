# W3PN Infrastructure 2.0

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

| Name | Purpose | Configuration | Price/month | Hosting |
| --- | ---     | --- | --- | --- |
| X   | Secure  | 2 vCore, 2GB RAM, 40GB SSD | €5.43 | [Alwyzon](https://www.alwyzon.com/en), Austria |
| G   | General | 4 vCore, 8GB RAM, 160GB SSD | €15.72 | [Alwyzon](https://www.alwyzon.com/en), Austria |
| S   | Storage | 2 vCore, 4GB RAM, 2TB HDD | €14.51 | [Alwyzon](https://www.alwyzon.com/en), Austria |
| B   | Backup  | ??? | ??? | ??? |

TODO

## Services
### Discontinued services

| Domain | Hosted | Resolution |
| --- | --- | --- |
| [matrix.web3privacy.info](https://matrix.web3privacy.info/) | Gwei.cz | Discontinued. Only the main channel on matrix.org will remain |
| [forum.web3privacy.info](http://forum.web3privacy.info) | Gwei.cz | Discontinued. Replaced by Zulip ([commons.w3pn.org](https://commons.w3pn.org/)). |

### Services to migration

| Current Domain | New domain | Service | Current | Server |
| --- | --- | --- | --- | --- |
| [vault.web3privacy.info](https://vault.web3privacy.info) | `vault.w3pn.org` | [Vaultwarden](https://github.com/dani-garcia/vaultwarden), password manager | Gwei.cz | X |
| [status.web3privacy.info](https://status.web3privacy.info) | `status.w3pn.org` | [Uptime Kuma](https://uptime.kuma.pet/), monitoring tool | Gwei.cz | X |
| [www.web3privacy.info](https://www.web3privacy.info) | `www.w3pn.org` | [Caddy](https://caddyserver.com/), webserver with automatic HTTPS | Gwei.cz | G |
| [n8n.web3privacy.info](https://n8n.web3privacy.info/) | `n8n.w3pn.org` | [n8n](https://n8n.io/), Workflow automatization | Mf | G |
| [commons.w3pn.org](https://commons.w3pn.org/) | - | Zulip, Self-hosted forum/chat | PP0 | G |

### New services

| Domain | Info | Server |
| --- | --- | --- |
| `auth.w3pn.org` | [Authentik](https://goauthentik.io/), authentification server, single sign-on (SSO) | X |
| `dns.w3pn.org` | [DNSCrypt](https://www.dnscrypt.org/), secure DNS resolver | X |
| `notes.w3pn.org` | [CodiMD](https://github.com/hackmdio/codimd), markdown notes | G |
| `meet.w3pn.org` | [Jitsi](https://jitsi.org/), video conferencing software | G |
| `windmill.w3pn.org` | [Windmill](https://www.windmill.dev/), workflow engine | G |
| `ci.w3pn.org` | [Woodpecker](https://woodpecker-ci.org/), CI/CD engine | G |
| `grafana.w3pn.org` | [Grafana](https://grafana.com/grafana/), Visualisations dashboards | G |
| `tor.w3pn.org` | [Tor relay](https://community.torproject.org/relay/) | G |
| `btcpay.w3pn.org` | [BTCPayServer](https://btcpayserver.org/) | G |
| `frp.w3pn.org` | [frp](https://github.com/fatedier/frp), fast reverse-proxy | G |
| `pds.w3pn.org` | Bluesky/AT Protocol [Personal Data Server](https://atproto.com/guides/self-hosting) (PDS) | S |
| `photos.w3pn.org` | [Immich](https://immich.app/), photo & video management | S |
| `sftp.w3pn.org` | [SFTPGo]([https://](https://sftpgo.com/)), flexible file server | S |
| `git.w3pn.org` | [Forgejo](https://forgejo.org/), git hosting | S |
| `seed.w3pn.org` | Radicle [Seed Node](https://radicle.xyz/guides/seeder) | S |

## Backup

We will use [Kopia](https://kopia.io/) or [BorgBackup](https://www.borgbackup.org/) & [Borgmatic](https://torsion.org/borgmatic/).

## GitHub

- [ ] archive old repositories like for example: [`news`](https://github.com/web3privacy/news), [`h25ber`](https://github.com/web3privacy/h25ber), [`w3pnnowstore`](https://github.com/web3privacy/w3pnowstore), [`pagency`](https://github.com/web3privacy/pagency) etc.
- [ ] update [Teams](https://github.com/orgs/web3privacy/teams) (= delete all current teams, add new ones)
- [ ] update [People](https://github.com/orgs/web3privacy/people), so all members have access + remove non-members
- [ ] only Stewards + Infra Guild Stewards should be Owners
- [ ] update [`.github`](https://github.com/web3privacy/.github/blob/main/profile/README.md) & [`.github-private`](https://github.com/web3privacy/.github-private/blob/main/profile/README.md) repo and info in GitHub Organization
