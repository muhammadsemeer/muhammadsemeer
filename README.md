<div align="center">

```text
 ____  _____ __  __ _____ _____ ____        ___  ____
/ ___||  ___|  \/  | ____| ____|  _ \      / _ \/ ___|
\___ \| |__ | |\/| |  _| |  _| | |_) |____| | | \___ \
 ___) |  __|| |  | | |___| |___|  _ <_____| |_| |___) |
|____/|_____|_|  |_|_____|_____|_| \_\     \___/|____/
```

**[`>> boot the full dashboard at semeer.me <<`](https://semeer.me)**

*interactive shell included. htop too.*

</div>

---

```console
semeer@infra:~$ neofetch

        ┌──────────────┐    muhammadsemeer@infra
        │   ╔══════╗   │    ─────────────────────────────────
        │   ║  MS  ║   │    role:    Infrastructure & DevOps Engineer
        │   ╚══════╝   │    host:    Kochi, Kerala — IN
        │      >_      │    org:     ClusterDev
        └──────────────┘    region:  ap-south-1
                            shell:   bash
                            state:   ● operational
```

```console
semeer@infra:~$ whoami --verbose

Happiest when nothing is on fire — which usually means a lot of
quiet work happened first. I run production on AWS and a fleet of
self-hosted services: databases, dashboards, log pipelines, and
the proxies in front of them.

I care most about the boring parts: sane limits, restorable
backups, and the one graph that matters being a single click away.
```

## `$ systemctl list-units --type=target`

```console
UNIT                   LOAD    ACTIVE  SUB      DESCRIPTION
cloud-infra.target     loaded  active  running  AWS · EC2 · IAM · S3 · Identity Center · Terraform · Ansible · Cloudflare
data.target            loaded  active  running  MySQL · ClickHouse · Redis · Kafka · XtraBackup
observability.target   loaded  active  running  Grafana · Prometheus · Loki · Promtail · Sentry · Uptime Kuma · Metabase · Healthchecks
platform-net.target    loaded  active  running  Linux · systemd · Nginx · Docker · Tailscale · bash
backend.target         loaded  active  running  Node.js · TypeScript · Express · Python · MongoDB

5 loaded units listed. Pass --all to see every unit, including the experiments.
```

## `$ dmesg | tail`

```console
[  OK  ] Mounted /home/semeer/portfolio
[  OK  ] Started Nginx reverse proxy (workers balanced)
[  OK  ] Verified backups are actually restorable
[  OK  ] Suppressed all pages — nothing is on fire
[  OK  ] Reached target Boring Production
```

## `$ contact --list`

| command | destination |
|---|---|
| `open portfolio` | [semeer.me](https://semeer.me) |
| `open email` | [mail@semeer.me](mailto:mail@semeer.me) |
| `open github` | [github.semeer.me](https://github.semeer.me) |
| `open gitlab` | [gitlab.semeer.me](https://gitlab.semeer.me) |
| `open linkedin` | [in.semeer.me](https://in.semeer.me) |
| `open instagram` | [insta.semeer.me](https://insta.semeer.me) |
| `open dev.to` | [dev.to/muhammadsemeer](https://www.dev.to/muhammadsemeer) |
| `open medium` | [medium.com/@muhammadsemeer](http://www.medium.com/@muhammadsemeer) |
| `open stackoverflow` | [stackoverflow](https://www.stackoverflow.com/users/14274552/muhammad-semeer-a) |

```console
semeer@infra:~$ sudo make me a coffee
semeer is not in the sudoers file. This incident will be reported.
semeer@infra:~$ # fine, you can do it the easy way:
```

<a href="https://www.buymeacoffee.com/muhammadsemeer"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" height="40"></a>

---

<div align="center">

```console
semeer@infra:~$ exit
nice try — there is no exit from infrastructure.
```

</div>
