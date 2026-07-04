# Linux Platform Engineering

A hands-on Linux engineering portfolio built around a reproducible KVM lab.
Focus: **RHCSA → RHCE certification** and **DevSecOps** practices.

## Goals

- Prepare and pass the Red Hat **RHCSA (EX200)**, then **RHCE**.
- Build a fully reproducible Linux lab — infrastructure as documentation.
- Demonstrate **DevSecOps** fundamentals: automation, hardening, secret hygiene.

## Lab

A single KVM host runs an isolated virtual lab. One RHEL 9 golden image is
cloned into a small set of practice nodes. See [ARCHITECTURE.md](ARCHITECTURE.md).

## Repositories

| Repo | Purpose |
| --- | --- |
| **linux-platform-engineering** | This portal — architecture, roadmap, links |
| **rhel-golden-image** | RHEL 9 reference image (RHCSA base), built with Kickstart |
| **linux-lab** | KVM lab — linked cloning, local repo node, storage, network |
| **hypervisor-hardening** | Ubuntu host hardening (CIS / ANSSI) |

All repositories share the `linux-platform-engineering` topic. The same pattern
(a portal plus focused repositories) can seed other programs.

## Skills demonstrated

- **RHCSA** — users & permissions, LVM, XFS, systemd, SELinux, firewalld,
  containers (Podman), scheduled tasks, storage management.
- **DevSecOps** — Kickstart automation, Bash tooling, host hardening,
  reproducible builds, keeping secrets out of version control.

## Conventions

Public repositories never expose real hostnames, addresses or secrets — such
values are always generalized (e.g. `the KVM host`, `192.0.2.x`).

---

[github.com/lxrider](https://github.com/lxrider)
