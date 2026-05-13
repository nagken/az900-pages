# AZ-900 Pitfalls

Mistakes that lose easy points on the exam.

- Confusing scalability (add capacity) vs elasticity (add AND remove).
- Mixing hybrid (cloud+on-prem) with multicloud (multiple cloud providers).
- Confusing Region Pair (GRS partner) vs AZ (separate DC within a region).
- Thinking RGs are security boundaries; they're lifecycle/management boundaries.
- Using VPN for high-throughput links - use ExpressRoute.
- CanNotDelete lock still allows changes; only ReadOnly blocks both.
- Pricing Calc (estimate) vs Cost Management (actuals) vs TCO (cloud vs on-prem).
- Policy vs RBAC: Policy = what config; RBAC = who can act.
- Free Azure tier is NOT the same as Free Account; account gives credits + free services.
- Not all regions have AZs - always check region capabilities map.
