# EnergyHub

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

EnergyHub is a Brooklyn, New York distributed energy resource management system (DERMS) vendor and an independent subsidiary of Alarm.com (Nasdaq ALRM), operating in its home market of the United States. Its Edge DERMS platform (formerly marketed as Mercury DERMS) lets electric utilities enroll, forecast, dispatch, and measure customer-owned distributed energy resources - smart thermostats, batteries, electric vehicles and EV chargers, solar inverters, and commercial and industrial loads - as virtual power plants, and the company says it has been running load control programs since 2009. EnergyHub sits squarely in the private middle layer of the energy value chain. It is not a utility, not a retailer, and not a market operator, so no consumer energy data mandate applies to it: there is no Green Button obligation, no Consumer Data Right designation, and no Ontario regulation in play. Its API posture is honestly partner-only and entirely undocumented in public. Two APIs are publicly announced by the company - the Mercury Edge Connect API, which EnergyHub states is "based on the Open ADR standard", and a Marketplace API for demand-response pre-enrollment at the device point of sale - but neither has public reference documentation, a published base URI, a schema, or a self-serve signup. The knowledge base at help.energyhub.com serves a public landing page while every technical guide and device-partner integration article behind it is gated by an Okta SSO login. A live host at mec.energyhub.com answers TLS with a valid DigiCert certificate and rejects every anonymous request with "400 No required SSL certificate was sent", which is mutual-TLS client-certificate enforcement rather than a public API. No consumer usage or billing data API exists for third parties, and no open grid or market data is published, so EnergyHub is closed on both the consumer-data and the market-data axis, and a developer gets in only by signing a commercial or DER partner agreement.

**Areas:** Energy · United States · Utilities · Electricity · Grid · DERMS · Distributed Energy Resources · Demand Response · Virtual Power Plant · OpenADR · EV Charging · Solar

## EnergyHub on APIs.io

Everything profiled for EnergyHub is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/energyhub/](https://apis.io/providers/energyhub/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [EnergyHub Mercury Edge Connect API](https://apis.io/apis/energyhub/mercury-edge-connect-api/) — Mercury Edge Connect is EnergyHub's standardized integration framework for connecting DER providers (thermostat, battery, EV, EV charger, and solar inverter…
- [EnergyHub Marketplace API](https://apis.io/apis/energyhub/marketplace-api/) — The Marketplace API integrates the Mercury/Edge DERMS platform with utility marketplace providers and online retailers so that a consumer buying a DER…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Energyhub Authentication](https://apis.io/security/energyhub/energyhub-authentication/)
- [Energyhub Domain Security](https://apis.io/security/energyhub/energyhub-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.energyhub.com/)
- [Documentation](https://help.energyhub.com/home/en-us/)
- [Support](https://www.energyhub.com/contact)
- [Blog](https://www.energyhub.com/news-announcements)
- [Terms of service](https://www.energyhub.com/terms)
- [Privacy policy](https://www.energyhub.com/privacy-policy)
- [GitHub](https://github.com/energyhub)

## API Evangelist rating

**Kin Score 22.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 2.6 |
| Developer ergonomics | 28.6 |
| Access clarity | 34.2 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.5** — Energy & Utilities

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/energyhub/](https://apis.io/providers/energyhub/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for EnergyHub: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/energyhub/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
