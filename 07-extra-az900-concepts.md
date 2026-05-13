# Extra AZ-900 concepts

Deeper-dive concepts beyond the basics.

## Shared responsibility tiers

On-prem: customer owns everything. IaaS: provider physical/host; customer OS up. PaaS: provider OS/runtime; customer apps/data. SaaS: provider everything except identity/data.

## Defense in depth

Multiple layers: physical security, identity/access, perimeter (DDoS protection), network (firewall/NSG), compute (endpoint protection), application (secure SDLC), data (encryption).

## Zero Trust

Verify explicitly, use least-privilege access, assume breach. Microsoft Entra + Conditional Access + Defender XDR is the toolchain.

## Encryption

At rest (Storage Service Encryption, Azure Disk Encryption, TDE), in transit (TLS), in use (Azure Confidential Computing). Customer-managed keys via Key Vault.

## SLAs and composite SLAs

Per-service uptime promise. Composite = multiplied across components. App Service 99.95% + SQL DB 99.99% = 99.94% combined.
