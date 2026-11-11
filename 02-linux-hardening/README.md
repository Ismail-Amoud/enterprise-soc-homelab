# Linux Server Hardening and SSH Security

**Type:** Personal cybersecurity home lab; not professional SOC employment.  
**Focus:** Host administration and attack-surface reduction

## Objective

Document the hands-on infrastructure and security-operations work performed in the Proxmox-based SOC home lab.

## Documented milestones

### 05 — Privileged user
Created a separate Linux administrative account with sudo privileges.

### 06 — ED25519
Configured passphrase-protected ED25519 public-key SSH authentication.

### 07 — SSH hardening
Disabled direct root SSH access and password-based SSH authentication.

### 08 — Fail2Ban
Installed, configured and tested Fail2Ban protection.

### 09 — Exposed services
Investigated an exposed-service warning and restricted an unnecessary service to local access.

## Reported outcome

Administrative access and service exposure were reviewed and hardened.

## Evidence and limitations

The information above is drawn from the previously documented home-lab timeline. Raw server logs, exact commands and authenticated dashboard screenshots are **not** included in this public version. Reported results should be supported with personally verified, redacted artefacts before making more specific claims. Do not invent test outcomes or pass synthetic examples off as real logs.

## Security before publishing further artefacts

Never expose public/private IP addresses, hostnames, SSH keys, accounts, secrets, domain identifiers, exact access methods, sensitive configuration, or private course/exam material. See [SECURITY.md](../SECURITY.md) and [evidence template](../docs/EVIDENCE-TEMPLATE.md).

[← Back to repository overview](../README.md)
