---
date: 2026-03-21
platforms: ["linkedin", "substack"]
crosspost:
  linkedin: "https://www.linkedin.com/posts/vaibhavkalekar_datagovernance-digitalsafety-privacybydesign-activity-7440977677206941696-SPDv?utm_source=share&utm_medium=member_desktop&rcm=ACoAAARplHoBSEjk934E9OvHZNNDp0tGG_i1qi4"
  substack: "https://substack.com/@vaibhavkalekar/note/c-230962123?r=tod0q&utm_source=notes-share-action&utm_medium=web"
---

California now requires all OS providers to collect age data just to run an operating system.

Australia's Online Safety Act mandates age verification for social media and R-rated gaming.

The Digital ID push is accelerating across both countries.

Noble intent. Genuinely.

But every one of these policies has the same blind spot:

They legislate what data to collect. Not what happens to it after.

From a data governance and engineering perspective, this isn't just a privacy concern — it's a platform stress test that most organisations are not ready for.

Three gaps nobody is talking about:

— Compliance and regulatory checks are being bolted onto platforms not designed to carry them. Age verification data has different retention, access, and audit requirements to behavioural data. Treating them the same way is a governance failure waiting to happen.

— Scalability assumptions are broken. Verifying age at onboarding for hundreds of millions of users, in real time, without friction, while maintaining data segregation — that is not a feature you bolt on. That is an architecture decision.

— Security perimeters just got wider. Every new identity data store is a new attack surface. The platforms being asked to hold this data have mixed track records on protecting far less sensitive information.

The Australian eSafety Commissioner's own 2023 Roadmap recommended against mandating age verification technology — noting the space was too immature. Two years later, the legislation passed anyway.

The gap between what regulators recommended and what Parliament enacted is where the real risk lives.

A double-blind token approach is technically elegant. But it requires governance maturity, platform discipline, and regulatory oversight that most of the ecosystem simply doesn't have yet.

We keep building policy on the assumption that the data infrastructure will catch up.

It won't. Not without deliberate design.

What's your read on how platforms should be handling the data side of this?