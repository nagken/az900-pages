# Cloud Concepts

**Domain weight on the exam:** ~28% (for AZ-900).


## Domain mind map

```mermaid
mindmap
  root((Cloud Concepts))
    Skills measured
    Concept map
    Decision reference
    Key services and concepts
    Common pitfalls
    Microsoft Learn
    Domain flashcards
```

## Skills measured

- Describe cloud computing: shared responsibility model, cloud models (public/private/hybrid/multicloud), consumption-based pricing.
- Benefits of cloud services: high availability, scalability, elasticity, reliability, predictability, security, governance, manageability.
- Cloud service types: IaaS (Infrastructure as a Service), PaaS (Platform as a Service), SaaS (Software as a Service); when to use each.

## Concept map

```mermaid
flowchart TD
  CloudFundamentals[Cloud Concepts]
  CloudFundamentals --> DeploymentModels[Public / Private / Hybrid / Multicloud]
  CloudFundamentals --> ServiceModels[IaaS / PaaS / SaaS]
  CloudFundamentals --> Benefits[HA, scale, elasticity, reliability, security]
```

## Decision reference

| Use this | When |
| --- | --- |
| **IaaS** | Need OS-level control, lift-and-shift VMs, custom networking |
| **PaaS** | Want managed runtime / database / app platform; focus on code |
| **SaaS** | Just consume an app (M365, Dynamics, Power BI) |
| **Public cloud** | Pay-per-use, fastest to provision, shared infra |
| **Private cloud** | Dedicated hardware, full control, compliance/sovereignty |
| **Hybrid** | Connect on-prem + cloud, gradual migration, data residency |
| **Multicloud** | Avoid vendor lock-in, best-of-breed services |

## Key services and concepts

| Name | Role |
| --- | --- |
| **Shared Responsibility Model** | Defines who secures what: physical (always Microsoft) vs OS/data (varies by service model) |
| **Capital Expense (CapEx)** | Upfront hardware purchase - traditional datacenter |
| **Operational Expense (OpEx)** | Pay-as-you-go subscription - cloud |
| **Consumption-based pricing** | Pay only for resources used; scale up/down |
| **Elasticity** | Auto-scale up and DOWN based on demand |
| **Scalability** | Add capacity (vertical or horizontal) |
| **High Availability** | Service stays up despite failures (SLA) |
| **Disaster Recovery** | Restore service after region/site failure |

## Common pitfalls

- Confusing scalability (add capacity) with elasticity (also remove capacity).
- Thinking hybrid = multicloud. Hybrid = mix of cloud + on-prem. Multicloud = multiple cloud providers.
- Assuming Microsoft secures customer data in IaaS - YOU secure OS, apps, data; Microsoft secures host/network/physical.
- Mixing up CapEx (buy hardware) and OpEx (rent/subscribe).

## Microsoft Learn

- [Describe cloud computing](https://learn.microsoft.com/training/modules/describe-cloud-compute/)
- [Benefits of using cloud services](https://learn.microsoft.com/training/modules/describe-benefits-use-cloud-services/)
- [Describe cloud service types](https://learn.microsoft.com/training/modules/describe-cloud-service-types/)

## Domain flashcards

<section class="fc-section" data-fc-title="Cloud Concepts quick-fire">
<div class="flashcard-grid">
<div class="flashcard"><div class="fc-q">Q: Define the shared responsibility model.</div><div class="fc-a">A: Splits security duties between customer + cloud provider. Customer always owns data and access; provider always owns physical. Middle layers depend on IaaS/PaaS/SaaS.</div></div>
<div class="flashcard"><div class="fc-q">Q: Which cloud model has no on-prem at all?</div><div class="fc-a">A: Public cloud.</div></div>
<div class="flashcard"><div class="fc-q">Q: Scalability vs elasticity?</div><div class="fc-a">A: Scalability = add capacity. Elasticity = add AND remove capacity automatically based on demand.</div></div>
<div class="flashcard"><div class="fc-q">Q: CapEx vs OpEx?</div><div class="fc-a">A: CapEx = upfront hardware (datacenter). OpEx = subscription/pay-as-you-go (cloud).</div></div>
<div class="flashcard"><div class="fc-q">Q: When pick PaaS over IaaS?</div><div class="fc-a">A: When you want managed runtime, do not want to patch OS, and focus on code instead of infrastructure.</div></div>
<div class="flashcard"><div class="fc-q">Q: Example of SaaS from Microsoft?</div><div class="fc-a">A: Microsoft 365, Dynamics 365, Power BI service.</div></div>
</div>
</section>
