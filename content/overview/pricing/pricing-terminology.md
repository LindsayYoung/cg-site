---
menu:
  overview:
    parent: pricing
title: Terms we use in pricing
weight: 90
aliases:
  - /docs/intro/terminology/pricing-terminology
  - /intro/terminology/pricing-terminology
  - /overview/terminology/pricing-terminology/
  - /overview/pricing/pricing-terminology/

---

These terms, among others, define a number of products and services offered by cloud.gov and 18F. The billing structure that 18F applies to cloud.gov is built around them. If other terms present frequent points of confusion, clarifications will be added to this page.

### System

A “system” roughly corresponds to a product or project team, including all the individual spaces, apps, and services necessary to deliver your product to users. Simply put, it’s everything you need to deliver a product.

A system maps to an [“org” in cloud.gov and Cloud Foundry](http://docs.cloudfoundry.org/concepts/roles.html#orgs).

### Support {#support}

“Support” is support to use the platform as intended, on a best-effort basis. We have no existing service-level agreement. We plan to always publish metrics that give agencies the ability to make an informed choice about whether to use cloud.gov or an alternative PaaS solution based on our actual track record.

### Consulting

“Consulting” is providing advice, development, documentation, and other resources that are custom or specific to the context of your application, system, or organization. If the outcome of the activity would not be reusable for our entire community of users, it’s consulting. Base platform fees for cloud.gov do not include consulting, and our team does not offer cloud-focused consulting outside of projects directly undertaken on behalf of a partner agency. This includes, for example, general information about migrating your products to the cloud. (All cloud.gov documentation and deployment are open source, so you may use this information to your benefit at any time.)

### Access package

The “access package” component covers access to the cloud.gov Platform as a Service (PaaS) and [support]({{< relref "#support" >}}) for it to stay up and available in its current form, as well as expanded over time. The access package component is paid 12 months at a time, and scales along with the number of systems being hosted and the impact level of the systems being launched on the platform, as defined by [Federal Information Processing Standard (FIPS) 199](http://csrc.nist.gov/publications/fips/fips199/FIPS-PUB-199-final.pdf).

The access package component is “non-severable” and therefore non-refundable. As a result, a payment in one fiscal year does not expire regardless of the status of the underlying appropriation.

### Resource usage quota

To support tenant applications and managed service instances, cloud.gov allocates resources (like compute nodes and memory) from an underlying Infrastructure as a Service provider. What we charge for this component covers the costs for the resources that cloud.gov allocates to hosted systems and teams. It also includes a small margin that covers our labor in managing those resources.

Resource usage fees on-demand are understood to be “severable” as they can be controlled in a self-service manner by provisioning more or fewer apps, and therefore must be treated accordingly.

Agencies can purchase reserved capacity via 18F as well, which is understood to be “non-severable”.

### Managed services

[Managed services]({{< relref "docs/apps/managed-services.md" >}}) are services that cloud.gov can spin up quickly and run on your behalf (databases, storage, caching, etc.).
