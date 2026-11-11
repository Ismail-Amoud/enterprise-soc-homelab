# Public SOC Lab Architecture

This is a **logical and intentionally simplified** representation of the personal Proxmox/Wazuh laboratory. It is **not** a production network diagram or a disclosure of actual routing or exposure rules.

```mermaid
flowchart TD
    A[Dedicated lab host - identity withheld] --> B[Proxmox VE]
    B --> C[Windows Server / Active Directory]
    B --> D[Windows 11 + Sysmon]
    B --> E[Linux / Wazuh]
    C -->|security events| E
    D -->|security events| E
    E --> F[Alert triage and investigation]
```

**What is intentionally excluded:** hosting-provider identity, network ranges, VLAN IDs, routing details, internal labels, management interfaces, credentials and exposed services.

[Back to repository](../README.md)
