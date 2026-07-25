# Linux Platform Engineering

A home lab I'm building to prepare the **Red Hat RHCSA (EX200)** and to practise
Linux engineering the way it's done in production: automated, documented,
reproducible.

This repository is the entry point. It holds the lab architecture and tracks
progress. Work is committed as I go — including the parts that didn't work the
first time.

## Why this lab

I have a background in industrial IT, OT infrastructure and cybersecurity. This
lab is where I turn that experience into demonstrable Linux platform skills:
KVM virtualization, unattended provisioning, host hardening, and the habit of
recording decisions rather than just commands.

## What exists today

| | |
| --- | --- |
| **KVM host** | Ubuntu Server 24.04 LTS on a NUC-class mini-PC. KVM/QEMU/libvirt stack up; NAT network and storage pool operational. |
| **Storage** | Local SSD for VM disks; NAS for installation media and backups, mounted on demand via `systemd.automount`. |
| **In progress** | RHEL 9 golden image, built unattended with Kickstart, to be cloned into a small RHCSA topology. |

Details in [ARCHITECTURE.md](ARCHITECTURE.md) · progress in [ROADMAP.md](ROADMAP.md).

## Conventions

- Public repository: real hostnames, addresses and secrets are never committed —
  values are generalized (`the KVM host`, `192.0.2.x`).
- Documentation in English; decisions recorded, not just outcomes.

## License

[MIT](LICENSE) — © 2026 lxrider
