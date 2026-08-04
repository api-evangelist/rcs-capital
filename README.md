# RCS Capital (rcs-capital)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

RCS Capital Corporation (RCAP) was a publicly traded holding company focused on the financial services industry, founded by Nicholas Schorsch and taken public in June 2013. The firm assembled Cetera Financial Group to become the second largest network of independent broker-dealers in the United States, with approximately 9,100 financial advisors managing $220 billion in assets under administration for 2.5 million clients.

RCS Capital filed for Chapter 11 bankruptcy protection in January 2016, citing $1.39 billion in debts, and emerged in May 2016 as Aretec Group, Inc., the holding company of Cetera Financial Group. No public developer APIs were offered under the RCS Capital brand.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/rcs-capital/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Broker-Dealer, Cetera Financial Group, Defunct, Financial Services, Independent Advisor, Investment Banking, Wealth Management

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [Financial Advisor Schema](json-schema/rcs-capital-financial-advisor-schema.json) | Schema for a financial advisor in a broker-dealer network |
| [Broker-Dealer Entity Schema](json-schema/rcs-capital-broker-dealer-schema.json) | Schema for a registered broker-dealer entity |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [Financial Advisor Structure](json-structure/rcs-capital-financial-advisor-structure.json) | Field-level documentation for the financial advisor object |

## JSON-LD Context

| Context | Description |
|---------|-------------|
| [RCS Capital Context](json-ld/rcs-capital-context.jsonld) | JSON-LD context mapping financial services concepts to schema.org and FIBO |

## Examples

| Example | Description |
|---------|-------------|
| [Financial Advisor Example](examples/rcs-capital-financial-advisor-example.json) | Example financial advisor record from a broker-dealer network |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [RCS Capital Vocabulary](vocabulary/rcs-capital-vocabulary.yml) | Domain vocabulary for independent broker-dealer financial services |

## References

- [Cetera Financial Group](https://www.cetera.com) — Successor entity
- [SEC EDGAR Filings](https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001568832&type=&dateb=&owner=include&count=40)
- [Chapter 11 Case Information](https://cases.ra.kroll.com/rcscapital/)

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
