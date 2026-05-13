# AZ-900 Exam Cheatsheet

Quick-reference highlights. Skim before the exam.

- Cloud models: Public (shared), Private (dedicated), Hybrid (both), Multicloud (>1 provider).
- Service models: IaaS (you: OS/apps/data) -> PaaS (you: code+data) -> SaaS (you: just data/use).
- Scalability = add capacity. Elasticity = add AND remove based on demand.
- Region Pair = GRS replication target + sequential patching. AZ = separate DC in 1 region.
- Hierarchy: Management Group -> Subscription -> Resource Group -> Resource.
- Redundancy: LRS (1 DC, 3 copies) < ZRS (3 AZs) < GRS (region pair) < RA-GRS (read paired).
- Storage tiers: Hot (frequent) < Cool (30d) < Cold (90d) < Archive (180d+, hours retrieval).
- VPN Gateway = internet, ExpressRoute = private dedicated link.
- Entra ID = identity. RBAC = role-based authz. Conditional Access = signal-based gate.
- Defense in depth layers: physical -> identity -> perimeter -> network -> compute -> app -> data.
- Pricing Calc = pre-buy estimate; TCO = cloud vs on-prem; Cost Management = actual spend.
- Policy = config rules. RBAC = identity permissions. Both apply at MG/sub/RG/resource scope.
- Locks: CanNotDelete vs ReadOnly. Inherit downward but cannot be overridden upward.
- Service Trust Portal = compliance docs. Service Health = outage info. Advisor = recommendations.
- Azure Arc = manage hybrid + multicloud resources from Azure control plane.
