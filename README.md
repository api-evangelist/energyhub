# EnergyHub (energyhub)

EnergyHub is a Brooklyn, New York distributed energy resource management system (DERMS) vendor and an independent subsidiary of Alarm.com (Nasdaq ALRM), operating in its home market of the United States. Its Edge DERMS platform (formerly marketed as Mercury DERMS) lets electric utilities enroll, forecast, dispatch, and measure customer-owned distributed energy resources — smart thermostats, batteries, electric vehicles and EV chargers, solar inverters, and commercial and industrial loads — as virtual power plants, and the company says it has been running load control programs since 2009. EnergyHub sits squarely in the private middle layer of the energy value chain: it is not a utility, not a retailer, and not a market operator, so no consumer energy data mandate applies to it — there is no Green Button obligation, no Consumer Data Right designation, and no Ontario regulation in play. Its API posture is honestly partner-only and entirely undocumented in public.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/energyhub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/energyhub/refs/heads/main/apis.yml)

## Tags

- Energy
- United States
- Utilities
- Electricity
- Grid
- DERMS
- Distributed Energy Resources
- Demand Response
- Virtual Power Plant
- OpenADR
- EV Charging
- Solar
- Energy Storage
- Smart Thermostats

## Timestamps

- **Created:** 2026-07-27
- **Modified:** 2026-07-27

## APIs

### EnergyHub Mercury Edge Connect API

Mercury Edge Connect is EnergyHub's standardized integration framework for connecting DER providers to the Mercury/Edge DERMS platform. EnergyHub states that the API "is based on the Open ADR standard, with enhanced functionality around automated enrollment, monitoring, and other functionality required for managing enterprise-wide portfolios of grid-edge and customer-owned DERs." No public reference documentation, schema, or operation list is published. The host `mec.energyhub.com` was probed on 2026-07-27 and is live behind a valid DigiCert certificate, returning HTTP 400 "No required SSL certificate was sent" to every anonymous request — mutual TLS client-certificate authentication. Access requires a DER partner agreement.

- **Human URL:** [https://www.energyhub.com/news/mercury-edge-connect-announcement](https://www.energyhub.com/news/mercury-edge-connect-announcement)
- **Base URL:** `https://mec.energyhub.com`

#### Tags

- DERMS
- OpenADR
- Demand Response
- Distributed Energy Resources
- Partner

#### Properties

- [Announcement](https://www.energyhub.com/news/mercury-edge-connect-announcement)
- [Documentation](https://help.energyhub.com/articles/mec/mec-overview) — Okta SSO gated
- [Partner Program](https://www.energyhub.com/der-partner-ecosystem/become-a-partner)

### EnergyHub Marketplace API

The Marketplace API integrates the Mercury/Edge DERMS platform with utility marketplace providers and online retailers so that a consumer buying a DER device can be pre-enrolled in a utility demand-response program at the point of sale. EnergyHub says it "automates the verification of DER program eligibility, incentive processing, and enrollment." Named launch integrators are EFI, Enervee, and Uplight. Despite being called "open" in the announcement, no public documentation, base URI, schema, authentication scheme, or signup was found.

- **Human URL:** [https://www.energyhub.com/news/marketplace-api-announcement](https://www.energyhub.com/news/marketplace-api-announcement)

#### Tags

- Demand Response
- Enrollment
- Marketplace
- Incentives
- Partner

#### Properties

- [Announcement](https://www.energyhub.com/news/marketplace-api-announcement)
- [Partner Program](https://www.energyhub.com/der-partner-ecosystem/become-a-partner)

## Mandate and Access Posture

| Dimension | Finding |
| --- | --- |
| Home market | United States |
| Mandate regime | none |
| Mandate status | not-applicable — EnergyHub is a DERMS vendor, not a utility, retailer, DNO, or market operator, so no Green Button, CDR, or Ontario obligation attaches to it. No compliance claim was made, so there is no claim-versus-implementation gap. |
| Data standard | OpenADR — vendor-stated basis for the Mercury Edge Connect API, version not stated, no OpenADR Alliance certification found. |
| Consumer data API | No. There is no documented way for a third party or a consumer to obtain an individual customer's usage or billing data from EnergyHub. |
| Open market data | No. No grid, market, program, or system datasets are published; no data portal exists. |
| Access gate | partner-only. No self-serve signup exists. A DER manufacturer submits the "become a partner" contact form, then integrates under a commercial partner agreement. |
| Auth model | Mutual TLS (X.509 client certificate) at the runtime endpoint; Okta SSO with MFA for the documentation knowledge base. No public API keys, no public OAuth, no `.well-known/openid-configuration`. |
| Specs harvested | 0 — no OpenAPI, AsyncAPI, JSON Schema, or Postman collection exists on any EnergyHub property or in its GitHub organization. |

## Common Properties

- [Website](https://www.energyhub.com/)
- [Documentation](https://help.energyhub.com/home/en-us/) — knowledge base, article bodies Okta gated
- [Platform](https://www.energyhub.com/edge-derms-platform/platform-overview)
- [Integrations](https://www.energyhub.com/edge-derms-platform/utility-integrations)
- [Partners](https://www.energyhub.com/der-partner-ecosystem)
- [Signup](https://www.energyhub.com/der-partner-ecosystem/become-a-partner)
- [Blog](https://www.energyhub.com/news-announcements)
- [About](https://www.energyhub.com/company)
- [Careers](https://www.energyhub.com/careers)
- [Support](https://www.energyhub.com/contact)
- [Privacy Policy](https://www.energyhub.com/privacy-policy)
- [GitHub Organization](https://github.com/energyhub)
- [LinkedIn](https://www.linkedin.com/company/energyhub/)

## Maintainers

- Kin Lane — kin@apievangelist.com
