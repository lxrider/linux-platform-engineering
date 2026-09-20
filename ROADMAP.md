# Roadmap

Current path:

```text
KVM host
    |
    v
RHEL golden image
    |
    v
RHCSA lab
    |
    v
RHCSA / EX200
    |
    v
host hardening
    |
    v
Ansible / RHCE
```

## Done

- [x] Ubuntu Server 24.04 installed on the KVM host
- [x] Hardware virtualization verified
- [x] KVM / QEMU / libvirt installed and tested
- [x] RHEL 9 installation media staged
- [x] RHEL 9 golden image built and sealed
- [x] Golden image validated with a clone

## In progress

- [ ] Build the RHCSA topology with linked QCOW2 clones
- [ ] Configure the `repo` node
  - local DNF repository
  - NFS
  - time services
- [ ] Add two disposable practice nodes

## Next

- [ ] Work through the RHCSA objectives
- [ ] Keep notes and useful configurations in the repository
- [ ] Sit the RHCSA / EX200 exam
- [ ] Harden the Ubuntu KVM host
- [ ] Document the hardening work

## Later

- [ ] Introduce Ansible progressively
- [ ] Move toward RHCE objectives
