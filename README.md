# Philipp Haussleiter

Software Engineer in Essen, Germany, working at [inspired-consulting](https://github.com/inspired-consulting).
I build tooling that runs close to the metal: Proxmox and Traefik providers, gokrazy appliances,
framebuffer dashboards for headless machines, and a backup client for 20-year-old PowerPC Macs.

**Focus:** Agentic Coding · Local AI / LLMs · Infrastructure Tooling · Automation

[GitHub](https://github.com/phaus) · [GitLab (self-hosted)](https://git-lab.de/philipp) · [Mastodon](https://ruhr.social/@phaus) · [Links](https://links.philipp.haussleiter.de)

<p align="left">
  <img width="49%" alt="Profile summary" src="./metrics.plugin.header.svg" />
  <img width="49%" alt="Contributions over the last six months" src="./metrics.plugin.iso_calender.svg" />
</p>

---

## Currently

- **Bare-metal dashboards** — [sys-wall](https://github.com/phaus/sys-wall) (Rust) and [gokrazy-syswall](https://github.com/phaus/gokrazy-syswall) (Go): statically linked TUIs that render system metrics, network info and a registration QR code straight onto the framebuffer console at boot.
- **PowerPC Mac revival** — [kopia-darwin-ppc](https://github.com/phaus/kopia-darwin-ppc), a native kopia backup client for Mac OS X 10.4/10.5 in ~3,000 lines of C99, plus [wallinfo-darwin-ppc](https://github.com/phaus/wallinfo-darwin-ppc) for wallpaper info overlays.
- **gokrazy router** — [router firmware](https://github.com/consolving/gokrazy-router), custom [A20](https://github.com/consolving/gokrazy-kernel-a20) and [Milk-V Duo](https://github.com/consolving/gokrazy-milkv-duo-kernel) kernels, and the [scanopy](https://github.com/consolving/gokrazy-scanopy) discovery daemon, under [consolving](https://github.com/consolving).
- **Homelab glue** — [app-store](https://github.com/phaus/app-store) and [umbrel-ssh](https://github.com/phaus/umbrel-ssh) for Umbrel, [zfs-snap-stats](https://github.com/phaus/zfs-snap-stats) for snapshot monitoring, [deliverer](https://github.com/phaus/deliverer) as a minimal PXE DHCP server.

## Tech Stack

**Languages:** Go, Rust, Java, C, JavaScript, Shell  
**Agentic / Local AI:** Ollama, llama.cpp, vLLM, Claude Code, Cursor  
**Infrastructure:** Proxmox, Kubernetes, NixOS, gokrazy, Podman, systemd, GitLab CI/CD

## Selected Projects

| Project | ⭐ | What it is |
|---------|---:|------------|
| [**traefik-proxmox-plugin**](https://github.com/phaus/traefik-proxmox-plugin) | 19 | Proxmox as a service-discovery provider for Traefik |
| [**play-bootstrap**](https://github.com/phaus/play-bootstrap) | 11 | Bootstrap scaffold module for the Play Framework |
| [**app-store**](https://github.com/phaus/app-store) | 5 | Personal Umbrel app store |
| [**error-service**](https://github.com/phaus/error-service) | 4 | EaaS — serves HTTP errors on purpose, or at random |
| [**kopia-darwin-ppc**](https://github.com/phaus/kopia-darwin-ppc) | | kopia backup client for PowerPC Macs, ~3k lines of C99 |
| [**sys-wall**](https://github.com/phaus/sys-wall) | | Framebuffer TUI dashboard for Linux consoles |
| [**go-proxmox**](https://github.com/phaus/go-proxmox) | | Fork of the Go client for the Proxmox VE API, maintained for the Traefik plugin |

<details>
<summary><b>More repositories</b></summary>

**GitHub ([phaus](https://github.com/phaus))**

- [**deliverer**](https://github.com/phaus/deliverer) – minimal DHCP server in Rust for PXE booting
- [**nextcloud-sync**](https://github.com/phaus/nextcloud-sync) – bidirectional WebDAV sync CLI for Nextcloud
- [**umbrel-ssh**](https://github.com/phaus/umbrel-ssh) – web UI to manage SSH keys on an Umbrel box
- [**zfs-snap-stats**](https://github.com/phaus/zfs-snap-stats) – TUI for 30 days of ZFS snapshot statistics
- [**wallinfo-darwin-ppc**](https://github.com/phaus/wallinfo-darwin-ppc) – wallpaper info overlay for Mac OS X 10.5 (PowerPC)
- [**gokrazy-syswall**](https://github.com/phaus/gokrazy-syswall) – framebuffer dashboard for gokrazy appliances
- [**serial**](https://github.com/phaus/serial) – serial-bridge: balenaOS serial stream terminal for the Raspberry Pi 1
- [**memory-vibes**](https://github.com/phaus/memory-vibes) – memory bandwidth benchmark tool
- [**room.ventures**](https://github.com/phaus/room.ventures) – Hugo static site for hotel room reviews
- [**flynn-tuf-repo**](https://github.com/phaus/flynn-tuf-repo) – TUF repository for the Flynn reconstruction
- Maintained forks: [nvml-wrapper](https://github.com/phaus/nvml-wrapper) (safe Rust wrapper for NVML), [vagrant-proxmox](https://github.com/phaus/vagrant-proxmox), [qemu-ga-container](https://github.com/phaus/qemu-ga-container), [umbrel-apps](https://github.com/phaus/umbrel-apps)

**Self-hosted GitLab ([philipp](https://git-lab.de/philipp))**

- [**Fritzbox-Unifi-Device-Agent**](https://git-lab.de/philipp/Fritzbox-Unifi-Device-Agent) – device tracking between Fritzbox & UniFi
- [**user-stats**](https://git-lab.de/philipp/user-stats) – user statistics collector
- [**amun-oc-efi**](https://git-lab.de/philipp/amun-oc-efi) – OpenCore EFI for an AMD Hackintosh
- [**docker-gitlab**](https://git-lab.de/philipp/docker-gitlab) – GitLab Docker deployment
- [**java-zfs**](https://git-lab.de/philipp/java-zfs) – Java ZFS integration
- [**docker-openfire**](https://git-lab.de/philipp/docker-openfire) – OpenFire XMPP server Docker image
- [**ui-test**](https://git-lab.de/philipp/ui-test) – Go UI testing experiments

**consolving** (contributor/maintainer)

- [**gokrazy-router**](https://github.com/consolving/gokrazy-router) (2⭐) – router firmware on gokrazy
- [**gokrazy-kernel-a20**](https://github.com/consolving/gokrazy-kernel-a20) – custom kernel for gokrazy on Allwinner A20
- [**gokrazy-milkv-duo-kernel**](https://github.com/consolving/gokrazy-milkv-duo-kernel) – gokrazy kernel for the Milk-V Duo
- [**gokrazy-scanopy**](https://github.com/consolving/gokrazy-scanopy) – network discovery daemon for gokrazy (Banana Pi R1)
- [**autodns.go**](https://github.com/consolving/autodns.go) – Go binding for the AutoDNS XML API
- [**flynn-infra**](https://github.com/consolving/flynn-infra) – infrastructure tooling for the Flynn PaaS rebuild
- [**gitlab-review-bot**](https://git-lab.de/consolving/gitlab-review-bot) – automated merge request review bot

</details>

## Upstream Contributions

117 merged pull requests out of 155 public ones (as of November 2026); 90 of them landed in
34 repositories outside my own account. Mostly Go, Java and Rust, with some JavaScript and Perl.

| Repository | Merged PRs | Project |
|------------|-----------:|---------|
| [innoq/LiQID](https://github.com/innoq/LiQID) | 14 | Java identity management |
| [consolving/flynn](https://github.com/consolving/flynn) | 13 | Flynn PaaS (Go) |
| [offlinehoster/kickster](https://github.com/offlinehoster/kickster) | 7 | JavaScript project scaffolding |
| [Games-for-Hire/bullshit-memory](https://github.com/Games-for-Hire/bullshit-memory) | 7 | Memory game |
| [consolving/flynn-infra](https://github.com/consolving/flynn-infra) | 7 | Flynn infrastructure |
| [munin-monitoring/contrib](https://github.com/munin-monitoring/contrib) | 4 | Munin plugins (Perl) |
| [mojbro/gocoa](https://github.com/mojbro/gocoa) | 4 | Objective-C Cocoa wrapper |
| [curiosdevcookie/taskmaster](https://github.com/curiosdevcookie/taskmaster) | 4 | Elixir task runner |
| [google/martian](https://github.com/google/martian) | 2 | Go HTTP proxy |
| [google/go-replayers](https://github.com/google/go-replayers) | 2 | Go replay mock library |
| [EmDee/moneymoney-bondora](https://github.com/EmDee/moneymoney-bondora) | 2 | MoneyMoney extension for Bondora |
| [consolving/gokrazy-router](https://github.com/consolving/gokrazy-router) | 2 | gokrazy router firmware |

<details>
<summary>Single merged PRs (22 repositories) and open PRs</summary>

**One merged PR each:**
[appwrite/sdk-generator](https://github.com/appwrite/sdk-generator),
[consolving/autodns.go](https://github.com/consolving/autodns.go),
[coreos/docs](https://github.com/coreos/docs),
[dskad/qemu-ga-container](https://github.com/dskad/qemu-ga-container),
[faabiosr/docker-golang-glide](https://github.com/faabiosr/docker-golang-glide),
[feststelltaste/awesome-software-analytics](https://github.com/feststelltaste/awesome-software-analytics),
[getumbrel/umbrel](https://github.com/getumbrel/umbrel),
[gschueler/vagrant-rundeck-ldap](https://github.com/gschueler/vagrant-rundeck-ldap),
[innoq/helloworld_play](https://github.com/innoq/helloworld_play),
[innoq/iQpdfutil](https://github.com/innoq/iQpdfutil),
[innoq/lvm-roca-prototype](https://github.com/innoq/lvm-roca-prototype),
[innoq/oathkeeper](https://github.com/innoq/oathkeeper),
[innoq/search-aggregator](https://github.com/innoq/search-aggregator),
[innoq/statuses](https://github.com/innoq/statuses),
[inspired-consulting/profiles](https://github.com/inspired-consulting/profiles),
[inspired-consulting/threat-shield-website](https://github.com/inspired-consulting/threat-shield-website),
[inspired-consulting/unbox-pdf](https://github.com/inspired-consulting/unbox-pdf),
[jdiemke/delaunay-triangulator](https://github.com/jdiemke/delaunay-triangulator),
[jscraftcamp/website](https://github.com/jscraftcamp/website),
[tabler/tabler-webjar](https://github.com/tabler/tabler-webjar),
[tiborvass/go-jsx](https://github.com/tiborvass/go-jsx),
[victorjacobs/tweetnest](https://github.com/victorjacobs/tweetnest)

**Open PRs (16):**
[gokrazy/tools](https://github.com/gokrazy/tools) (2),
[gokrazy/internal](https://github.com/gokrazy/internal) (2),
[mojbro/gocoa](https://github.com/mojbro/gocoa) (2),
[anodino-dev/bbb-download](https://github.com/anodino-dev/bbb-download),
[consolving/gokrazy-router](https://github.com/consolving/gokrazy-router),
[innoq/search-aggregator](https://github.com/innoq/search-aggregator),
[machine-drivers/docker-machine-driver-qemu](https://github.com/machine-drivers/docker-machine-driver-qemu),
[mashup-fm/play-jobs](https://github.com/mashup-fm/play-jobs),
[rust-nvml/nvml-wrapper](https://github.com/rust-nvml/nvml-wrapper),
[smartrevolution/gnupg-for-java](https://github.com/smartrevolution/gnupg-for-java),
[teamon/play-airbrake](https://github.com/teamon/play-airbrake),
[wernight/docker-kubectl](https://github.com/wernight/docker-kubectl)

</details>

<details>
<summary><b>Detailed statistics</b></summary>

<p align="center">
  <img width="49%" alt="Issues, PRs and languages" src="./metrics.plugin.issue_pr_lang.svg" />
  <img width="49%" alt="Lines of code" src="./metrics.plugin.lines-of-code.svg" />
</p>
<p align="center">
  <img width="49%" alt="Activity and community" src="./metrics.plugin.acti_comm.svg" />
  <img width="49%" alt="Repository traffic" src="./metrics.plugin.repositories-traffic.svg" />
</p>
<p align="center">
  <img width="49%" alt="Stargazers over time" src="./metrics.plugin.stargazers.svg" />
  <img width="49%" alt="Achievements" src="./metrics.plugin.achievements.svg" />
</p>
<p align="center">
  <img width="98%" alt="Notable contributions" src="./metrics.plugin.notable-contributions.svg" />
</p>

</details>
