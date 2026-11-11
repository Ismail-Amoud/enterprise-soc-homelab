# SOC Lab Architecture with Proxmox

**Type:** Personal cybersecurity home lab; not professional SOC employment.  
**Focus:** Infrastructure and virtualization

## Objective

Document the hands-on infrastructure and security-operations work performed in the Proxmox-based SOC home lab.

## Documented milestones

### 01 — Dedicated host and Debian 12
Commissioned a dedicated host, installed Debian 12 and verified remote access after restart.

### 02 — Proxmox VE
Installed and accessed Proxmox VE; verified the management interface and services after troubleshooting.

### 03 — Storage validation
Checked redundant NVMe storage, RAID1 and Proxmox directory-type storage.

### 04 — Virtual networking
Configured a public-facing bridge and a separate private virtual bridge for lab workloads.

## Reported outcome

The result was a functioning virtualization foundation for the SOC lab.

## Evidence and limitations

The information above is drawn from the previously documented home-lab timeline. Raw server logs, exact commands and authenticated dashboard screenshots are **not** included in this public version. Reported results should be supported with personally verified, redacted artefacts before making more specific claims. Do not invent test outcomes or pass synthetic examples off as real logs.

## Security before publishing further artefacts

Never expose public/private IP addresses, hostnames, SSH keys, accounts, secrets, domain identifiers, exact access methods, sensitive configuration, or private course/exam material. See [SECURITY.md](../SECURITY.md) and [evidence template](../docs/EVIDENCE-TEMPLATE.md).

[← Back to repository overview](../README.md)
