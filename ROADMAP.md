# Roadmap

```text
KVM host → golden image → RHCSA clones → RHCSA (EX200) → host hardening → RHCE
```

## Done

- Ubuntu Server 24.04 on the KVM host; hardware virtualization verified.
- KVM / QEMU / libvirt stack installed and validated.

## In progress

- RHEL 9 Binary DVD staged on the host.
- RHEL 9 golden image, built unattended with Kickstart.

## Next

- Linked QCOW2 cloning into the RHCSA topology: a `repo` node (local dnf repo,
  NFS, time) and two practice nodes.
- Work through the RHCSA objectives on the clones; commit notes as I go.
- Sit the RHCSA (EX200).
- Harden the Ubuntu host (CIS / ANSSI), in a dedicated repository.
