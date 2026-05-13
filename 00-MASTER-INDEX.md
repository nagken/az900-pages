# AZ-900 - Microsoft Azure Fundamentals - Visual Study Guide

> Concept-only study aid. No exam questions reproduced. Source PDF (if any) stays local + gitignored.

**Skills outline:** https://learn.microsoft.com/credentials/certifications/resources/study-guides/az-900

## Concept mindmap

```mermaid
mindmap
  root((AZ-900))
    Cloud Concepts
      Shared responsibility
      Public/Private/Hybrid/Multi
      IaaS/PaaS/SaaS
      Benefits: HA scale elasticity
    Architecture and Services
      Hierarchy MG-Sub-RG-Resource
      Regions and AZs
      Compute VM ACI AKS Functions
      Networking VNet VPN ExpressRoute
      Storage Blob Disk File LRS GRS
      Identity Entra MFA RBAC
    Management and Governance
      Cost Pricing TCO Cost Mgmt
      Policy Locks Purview
      Deploy Portal CLI Bicep Arc
      Monitor Advisor Service Health App Insights
```

## Domain map

```mermaid
flowchart LR
    Master["AZ-900 Master Index"]
    D01["Cloud Concepts"]
    Master --> D01
    D02["Azure Architecture and Services"]
    Master --> D02
    D03["Azure Management and Governance"]
    Master --> D03
```

## Domain weights

```mermaid
pie showData
    title AZ-900 domain weights
    "Cloud Concepts" : 28
    "Azure Architecture and Services" : 37
    "Azure Management and Governance" : 35
```

> Click a slice / legend label to jump to that chapter.

## Recommended study order

```mermaid
gantt
    title Suggested study plan
    dateFormat X
    axisFormat Day %d
    section Plan
    Cloud Concepts :t1, 0, 1d
    Azure Architecture and Services :t2, after t1, 2d
    Azure Management and Governance :t3, after t2, 1d
```

---

**Next:** open [01-cloud-concepts.md](01-cloud-concepts.md)

<!-- TODO: fill remaining sections via Copilot chat. Target structure mirrors c:\az305\study-guide\00-MASTER-INDEX.md. -->
