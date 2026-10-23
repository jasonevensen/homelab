# My Home Lab
Documentation of my personal homelab infrastructure, including Linux servers, networking, storage, containerization, and security.

This repo tracks my config, troubleshooting notes, architectural decisions, and what I have learned while building everything.

## Infrastructure
- Networking: Main ISP router in passthrough mode running to a Protectli v1210 OPNsense firewall, WireGuard VPN, local DNS, and DHCP

- NAS Server: Supermicro x10sll-f running a minimal Debian 13 (Trixie) install with 16 GB DDR3 ECC ram
    - Storage: Two 10 TB WD Red drives running in a ZFS pool and an 8 TB WD white label helium filled drive shucked
    - Virtualization: KVM running Rocky Linux 10 for RHCSA practice

- Media Server: Dell Optiplex 3050 with 8 GB of ram running a minimal Debian 13 (Trixie) install
    - Services: Jellyfin, Navidrome, FreshRSS, Syncthing, Vaultwarden, Nextcloud, Caddy, Uptime Kuma

## Documentation
My Documentation in this repo will be organized by infrastructure components, with configuration examples and troubleshooting notes added as the lad develops. This lab is under current construction so I will be adding documentation as I build and break things.

## Related
More detailed writeups and project explanations can be found on my website [LostPackets.dev](https://lostpackets.dev) where I also share my thoughts and why I chose to do things a certain way.

## Status
Currently in build/break mode so it is a work in progress.
