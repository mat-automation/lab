# Mat (Mathias) Lemke

🚀 aspiring DevOps Engineer

Storage Engineer, Storage Admin. I work mainly with Linux as well as w/ NetApp & DELL-EMC PowerScale.

Also I'm an open source enthusiast #Arch #Linux 🐧


## Things I've Built

I'm in love with my HomeLab because there is always something exciting and new to learn.
At the core runs Proxmox and Docker (LXC Container, soon to be run by Kubernetes) to serve several basic IT needs:

- PVE x2 (Minis Forum MS-01 & HUNSN RJ03)
- PBS (HUNSN RJ42)

Routing and firewall is handled by an virt OPNsense and 3x multi-gig switches.

I host these services:
- OPNsense Firewall
- AdGuard/ Pi-hole & Win Srv (DC/DNS)
- phpIPAM
- Heimdall, a bookmark manager
- virt NAS (incl. the media server Jellyfin)
- Nextcloud
- Vaultwarden, a private hosted password manager based on Bitwarden
- Immich, an automatic private photo & video backup for all mobile devices
- home assistant
- audiobookshelf, a web app to manage my audiobooks and podcasts
- Paperless ngx
- Uptime Kuma, CheckMK & Pulse, simple monitoring of all services and IT appliances

In order to stay up2date:
- a few Linux VM to catch up with their latest developments
- 2x Kubernetes cluster: Talos & K3S on Debian 13
- virt 3x node PVE cluster w/ ceph storage

Further projects in the near future:
- VMware 9 & Veeam BR trials
- Prometheus, Grafana
- Helm, Terraform, Ansible 

The QNAP hosts all my personal data as well as the 2nd PBS weekly backups on to an all flash based NFS share. It runs daily snapshots and weekly backups on to a Terramaster nested DSM7 🤫

Monthly backups are send to TrueNAS Scale hosted on an aging DELL T320. Quarterly dumps (in case I do remember) go on to LTO tapes via Acronis which are swapped over regularly and stored externally.
