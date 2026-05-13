# AZ-900 Flashcards

Click each card to flip.

<section class="fc-section" data-fc-title="Cloud Concepts">
<div class="flashcard-grid">
<div class="flashcard"><div class="fc-q">Q: Define the shared responsibility model.</div><div class="fc-a">A: Splits security duties between customer + cloud provider. Customer always owns data and access; provider always owns physical. Middle layers depend on IaaS/PaaS/SaaS.</div></div>
<div class="flashcard"><div class="fc-q">Q: Which cloud model has no on-prem at all?</div><div class="fc-a">A: Public cloud.</div></div>
<div class="flashcard"><div class="fc-q">Q: Scalability vs elasticity?</div><div class="fc-a">A: Scalability = add capacity. Elasticity = add AND remove capacity automatically based on demand.</div></div>
<div class="flashcard"><div class="fc-q">Q: CapEx vs OpEx?</div><div class="fc-a">A: CapEx = upfront hardware (datacenter). OpEx = subscription/pay-as-you-go (cloud).</div></div>
<div class="flashcard"><div class="fc-q">Q: When pick PaaS over IaaS?</div><div class="fc-a">A: When you want managed runtime, do not want to patch OS, and focus on code instead of infrastructure.</div></div>
<div class="flashcard"><div class="fc-q">Q: Example of SaaS from Microsoft?</div><div class="fc-a">A: Microsoft 365, Dynamics 365, Power BI service.</div></div>
</div>
</section>

<section class="fc-section" data-fc-title="Azure Architecture and Services">
<div class="flashcard-grid">
<div class="flashcard"><div class="fc-q">Q: What is the Azure resource hierarchy?</div><div class="fc-a">A: Management Group -> Subscription -> Resource Group -> Resource.</div></div>
<div class="flashcard"><div class="fc-q">Q: What does an Availability Zone protect against?</div><div class="fc-a">A: Datacenter-level failure within a region. 3 zones per AZ-enabled region.</div></div>
<div class="flashcard"><div class="fc-q">Q: What's the cheapest storage redundancy?</div><div class="fc-a">A: LRS (Locally Redundant Storage) - 3 copies, 1 datacenter.</div></div>
<div class="flashcard"><div class="fc-q">Q: When use ExpressRoute over VPN Gateway?</div><div class="fc-a">A: When you need private connection, high bandwidth, predictable latency, no internet.</div></div>
<div class="flashcard"><div class="fc-q">Q: What is Conditional Access?</div><div class="fc-a">A: Entra policy that allows/blocks/MFA-prompts based on user/device/location/risk signals.</div></div>
<div class="flashcard"><div class="fc-q">Q: Which serverless compute pays only per execution?</div><div class="fc-a">A: Azure Functions in Consumption plan.</div></div>
<div class="flashcard"><div class="fc-q">Q: Which storage tier for rarely accessed data with longer retrieval?</div><div class="fc-a">A: Cool (30+ day) or Cold (90+ day); Archive for >180 day and OK with hours of retrieval latency.</div></div>
<div class="flashcard"><div class="fc-q">Q: What is Microsoft Entra ID (formerly)?</div><div class="fc-a">A: Azure Active Directory; cloud identity and access management service.</div></div>
</div>
</section>

<section class="fc-section" data-fc-title="Azure Management and Governance">
<div class="flashcard-grid">
<div class="flashcard"><div class="fc-q">Q: Difference between Pricing Calculator and TCO Calculator?</div><div class="fc-a">A: Pricing Calc = estimate cost of resources you plan to buy. TCO = compare full 3-yr cloud cost vs on-prem datacenter.</div></div>
<div class="flashcard"><div class="fc-q">Q: What does Azure Policy do?</div><div class="fc-a">A: Enforces rules (e.g., allowed regions, required tags, allowed SKUs) at MG/sub/RG scope.</div></div>
<div class="flashcard"><div class="fc-q">Q: Difference between Policy and RBAC?</div><div class="fc-a">A: RBAC = who can do actions on resources. Policy = what configurations resources can have.</div></div>
<div class="flashcard"><div class="fc-q">Q: Two types of resource locks?</div><div class="fc-a">A: CanNotDelete (allow change, block delete) and ReadOnly (block change AND delete).</div></div>
<div class="flashcard"><div class="fc-q">Q: Where to find SOC/ISO compliance reports?</div><div class="fc-a">A: Service Trust Portal.</div></div>
<div class="flashcard"><div class="fc-q">Q: What gives best-practice recommendations across cost/security/reliability/performance/ops?</div><div class="fc-a">A: Azure Advisor.</div></div>
<div class="flashcard"><div class="fc-q">Q: Bring on-prem servers under Azure control plane?</div><div class="fc-a">A: Azure Arc.</div></div>
<div class="flashcard"><div class="fc-q">Q: Where to set a budget alert?</div><div class="fc-a">A: Azure Cost Management + Billing.</div></div>
</div>
</section>
