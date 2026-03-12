---
author: Leo Traven
pubDatetime: 2026-03-10T19:00:00Z
modDatetime: 2026-03-10T19:00:00Z
title: The infrastructure of AI
slug: infrastructure-of-ai
featured: false
draft: false
tags:
  - ai
  - layers
  - infrastructure
description: How AI value creation spans from models down to data, platforms, chips, facilities, and energy.
---

<!-- Situation -> Complication -> Question -> Answer -->

### TL;DR:

- Many people talk about AI models, but there are many infrastructure layers below it
- If one wants to build scalable AI systems, mastering its infrastructure is a prerequisite
- The infrastructure is what makes AI so interesting for the whole economy, not just software companies

### Building out AI is more than building great models

- There is a reason for why AI has been able to push major capital markets indices to all time highs over the last couple of years
- It's economic impact can be divided into two areas: the buildout and the payoff
- Anticipating major opportunities for selling AI solutions in the future, companies have been investing unimaginable amounts of capital into the buildout
- While frontier models mostly come from AI labs, those labs are mostly financed by MAG7 companies
- After using their cashflow in the beginning, especially MAG7 began financing this buildout by taking on debt
- Their investments cause a ripple effect that matters to the whole economy

Make this a text


### From data to energy
Optimize this

```text
   AI
   |
  Data
   |
 Platform
   |
 Silicon
   |
Facilities
   |
 Energy
```

### Data

At the AI level, you have frontier models training the latest AI models.
Those models are trained using data on the scale of the entire internet.
Being relatively generic after training, companies need to provide the AI models with context to create actually business value when using them, making data the first layer below the AI models trained by frontier labs.
Extensive knowledge databases need to be created, giving companies the opportunity to retrieve context relevant for a request.
In enterprise systems, companies like Databricks and Snowflake provide platforms for this.

### Platform

AI models deployed at scale need to be managed by an underlying software infrastructure that e.g. routes user requests to different models and monitors for errors.
These platforms ensure AI does not crash under high demands, while meeting highest security standards.
They can be built using orchestration softwares like Kubernetes, who are able to balance loads efficiently and scale model deployments depending on current demand.
Winners in this space are the cloud hyperscalers, namingly Amazon, Microsoft and Google who provide these platforms on a highly scalable pay-per-use basis.
They dynamically allocate cloud resources where they are needed most by using a layer of abstraction over classical servers while ensuring customer privacy.
Many companies chose them because this way, they do not have to build data centers themselves.
Additionally, the pay-per-use model is highly attractive as it gives companies the options to start and stop cloud services as they like in no time.
In case of a deleted service, the underlying infrastructure is used for other purposes.

### Silicon

AI models basically work on matrix multiplication.
They operate on highly specialized microchips that enable parallel processing.
Access to these highly demanded and therefore very expensive chips defines who can train and run the most advances AI models.
Equipped with huge cashflows, hyperscalers buy chips from e.g. Nvidia or AMD.
As Nvidia only designs chips, they are usually built by TSMC, a taiwanese company that heavily relies on lithographic machines from ASML, a company from the netherlands.
At the heart of ASML's lithography machines lie laser systems manufactured by Trumpf and highly specialized mirrors manufactured by Zeiss.
Both are private engineering companies from Germany!

### Facilities

The AI supercomputers used by the big cloud providers need to be housed somewhere.
They require huge data centers equipped with advanced cooling systems.
Therefore, massive, multi-year construction investments are needed.
In the end, data centers are just massive buildings host hardware and make sure it runs safely.
Those buildings need to be built.
In this space, Equinix and Digital Realty are the major data center developers.
They buy the land, secure the power permits and design the architecture.

### Energy

Meta currently plans to build Hyperion, a data center for which they bought an area of roughly 14.8 km^2.
The area will host not only data center buildings, but also cooling systems, power infrastructure, security buffer zones and more.
Hyperion will draw up to 5 GW, the equivalent of roughly 3 million homes in that region.
In January 2026, Meta signed a nuclear power procurement deal.
Additionally, the facility will host three natural gas turbines and Meta has committed to adding 1.5 GW of new solar and wind energy to the region.
Winners in this space are Siemens Energy and GE Vernova who provide gas turbines and grid infrastructure.



- especially companies at the top of the value chain begin to integrate vertically to reduce long term costs