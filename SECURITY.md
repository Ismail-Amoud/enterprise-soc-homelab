# Publication Security Policy

This is a **public** personal SOC home-lab repository. It intentionally omits actionable infrastructure-access details.

## Never publish

- SSH private keys, passwords, tokens, API keys, recovery codes or environment files.
- Public or private IP addresses, internal hostnames, domains, usernames, sensitive paths or provider account identifiers.
- Exact firewall rules, exposure paths, access-control configurations or management URLs that would aid targeting.
- Unredacted screenshots, original server logs, user data or private course/exam material.

## Evidence checklist

1. Use evidence from your **own** laboratory only.
2. Redact identifiable and access-enabling fields, including metadata.
3. Preserve just enough event context to explain the investigation.
4. Clearly label synthetic samples as **synthetic**; never pass them off as observed logs.
5. Avoid claiming a successful attack from failed authentication events alone.

If a secret is accidentally committed, rotate or revoke it immediately: deleting the file from the latest commit does not remove it from Git history.
