# Roadmap

```text
Infrastructure → Golden image → RHCSA clones → RHCSA (EX200) → Hardening → RHCE (EX294)
```

## Repository status

| Repo | Status |
| --- | --- |
| linux-platform-engineering (portal) | In progress |
| rhel-golden-image | Bootstrapped (Kickstart + build script) |
| linux-lab | Planned |
| hypervisor-hardening | Planned |

## Next steps

1. Finalize the KVM host (libvirt access, wired network, RHEL 9 DVD in place).
2. Build the RHEL 9 golden image with Kickstart.
3. Document linked cloning and the local repo node (`linux-lab`).
4. Sit the RHCSA (EX200).
5. Harden the Ubuntu host (`hypervisor-hardening`).
