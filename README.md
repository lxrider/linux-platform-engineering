# Linux Platform Engineering

A hands-on Linux lab built around **KVM, RHEL 9 and automation**.

I started this project for a simple reason: I wanted an environment where I could
work on Linux the way I like to learn it, by building things myself, understanding
what happens underneath, breaking things occasionally, and rebuilding them better.

RHCSA and RHCE provide part of the learning path, but the goal goes beyond
certification.

I want this lab to behave like a small infrastructure platform that can be
rebuilt, documented, automated and progressively secured.

## Why this lab exists

Reading documentation is useful.

Having to understand why a VM does not boot, why networking behaves differently
than expected, or why an automated installation fails is where things become
really interesting :)

This project gives me a place to experiment with:

- Linux system administration
- RHEL
- KVM, QEMU and libvirt
- networking and storage
- unattended provisioning
- golden images
- Bash
- Ansible
- hardening
- automation
- troubleshooting

## Architecture

The lab currently runs on an x86 mini-PC with **Ubuntu Server 24.04 LTS**
as the KVM hypervisor.

```text
Ubuntu Server 24.04 LTS
        |
        +-- KVM / QEMU / libvirt
                |
                +-- RHEL 9 golden image
                |
                +-- repo node
                |
                +-- practice node 1
                |
                +-- practice node 2
```

More details in [ARCHITECTURE.md](ARCHITECTURE.md).

## Golden image

The base RHEL image is built separately here:

[rhel-golden-image](https://github.com/lxrider/rhel-golden-image)

I prefer keeping image creation separate from the lab itself.

The image stays clean and reproducible, while the lab is where configuration,
experimentation and automation happen.


## Current status

| Component | Status |
|---|---|
| KVM host | Working |
| RHEL 9 golden image | Working |
| Linked clones | In progress |
| RHCSA topology | In progress |
| Ansible | Planned |
| Hardening | Planned |

## How I work

Start from a blank page.

Understand first.  
Build it.  
Test it.  
Break it if necessary.  
Fix it.  
Document it.  
Automate it.

## Build. Break. Understand. Rebuild better.
