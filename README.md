# Born2beRoot

> **42 cursus** · System administration · Debian/Linux on a virtual machine.

A system administration project: setting up a hardened Linux server inside a virtual machine, configured from scratch with security best practices.

## Features

- Virtual machine running Debian (or Rocky) with LVM partitioning
- Encrypted partitions and a strict password policy
- UFW/firewall, SSH on a non-default port, `sudo` rules and logging
- A monitoring script broadcasting system stats at a fixed interval

## Usage

```bash
# Check the monitoring script output
sudo systemctl status
# Verify SSH port, UFW rules, sudo config as required by the subject
```

## Key concepts

Virtualization, partitioning (LVM), system hardening, services and shell scripting.

---

*42 cursus project — [github.com/rjacquet31](https://github.com/rjacquet31)*
