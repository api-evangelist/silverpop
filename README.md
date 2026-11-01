# Silverpop

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

Silverpop Engage is the email marketing, marketing automation and transactional messaging API now sold as Acoustic Campaign, and one of the longest-lived commercial marketing APIs still in production. The operation names an integrator calls today — AddRecipient, ScheduleMailing, RawRecipientDataExport — are the original Silverpop names, unchanged through acquisition by IBM in 2014 (as Watson Campaign Automation) and the carve-out to Acoustic in 2019; silverpop.com now 301s to acoustic.com and the developer portal lives at developer.goacoustic.com. Two surfaces sit behind one per-tenant host: a single-endpoint XML API at /XMLAPI carrying roughly sixty operations across contact databases, contact lists, relational tables, scoring models, templates and mailings, dynamic content and reporting, and a narrower JSON REST API at /rest with eleven resources including gdpr_jobs. Authentication is OAuth 2.0 with the refresh_token grant only and no scope model; the binding runtime limit is a cap of ten concurrent requests per organization rather than a request rate.

**Areas:** Email Marketing · Marketing Automation · Campaign Management · Digital Marketing · Transactional Email · SMS · Customer Data · Contact Management · Mobile Push · Marketing Analytics

## Silverpop on APIs.io

Everything profiled for Silverpop is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/silverpop/](https://apis.io/providers/silverpop/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Silverpop Authentication API](https://apis.io/apis/silverpop/silverpop-authentication-api/) — OAuth 2.0 token management
- [Silverpop Campaigns API](https://apis.io/apis/silverpop/silverpop-campaigns-api/) — Email campaign management
- [Silverpop Contacts API](https://apis.io/apis/silverpop/silverpop-contacts-api/) — Contact (recipient) list management
- [Silverpop Programs API](https://apis.io/apis/silverpop/silverpop-programs-api/) — Marketing automation program management
- [Silverpop Reports API](https://apis.io/apis/silverpop/silverpop-reports-api/) — Campaign reporting and analytics
- [Silverpop Transactional API](https://apis.io/apis/silverpop/silverpop-transactional-api/) — Transactional email and SMS messaging

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [silverpop-mcp.yml](https://apis.io/servers/silverpop/silverpop-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Silverpop Agentic Access](https://apis.io/agentic-access/silverpop/silverpop-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Silverpop Contact](https://apis.io/schemas/silverpop/silverpop-contact/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Silverpop Contact Structure](https://apis.io/json-structure/silverpop/silverpop-contact-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Silverpop Context](https://apis.io/jsonld/silverpop/silverpop-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Silverpop Vocabulary](https://apis.io/vocabularies/silverpop/silverpop-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Silverpop Add Contact Example](https://apis.io/examples/silverpop/silverpop-add-contact-example/)

#### Collections (7)

Postman and Open Collection request collections.

- [Silverpop Engage API (Acoustic Campaign)](https://apis.io/collections/silverpop/open-silverpop/)
- [Silverpop Engage API (Acoustic Campaign) Authentication API](https://apis.io/collections/silverpop/open-silverpop-authentication-api/)
- [Silverpop Engage API (Acoustic Campaign) Authentication Campaigns API](https://apis.io/collections/silverpop/open-silverpop-campaigns-api/)
- [Silverpop Engage API (Acoustic Campaign) Authentication Contacts API](https://apis.io/collections/silverpop/open-silverpop-contacts-api/)
- [Silverpop Engage API (Acoustic Campaign) Authentication Programs API](https://apis.io/collections/silverpop/open-silverpop-programs-api/)
- [Silverpop Engage API (Acoustic Campaign) Authentication Reports API](https://apis.io/collections/silverpop/open-silverpop-reports-api/)
- [Silverpop Engage API (Acoustic Campaign) Authentication Transactional API](https://apis.io/collections/silverpop/open-silverpop-transactional-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Silverpop — jsonschema rules](https://apis.io/rules/silverpop/silverpop-jsonschema-spectral-rules/)
- [Silverpop API Rules](https://apis.io/rules/silverpop/silverpop-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Silverpop Authentication](https://apis.io/security/silverpop/silverpop-authentication/)
- [Silverpop Domain Security](https://apis.io/security/silverpop/silverpop-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Silverpop Plans Pricing](https://apis.io/plans/silverpop/silverpop-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Silverpop Rate Limits](https://apis.io/rate-limits/silverpop/silverpop-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Silverpop Finops](https://apis.io/finops/silverpop/silverpop-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://developer.goacoustic.com/acoustic-campaign/reference/overview)
- [Getting started](https://developer.goacoustic.com/acoustic-campaign/reference/getting-started-with-oauth)
- [API reference](https://developer.goacoustic.com/acoustic-campaign/reference/overview)
- [Pricing](https://www.acoustic.com/pricing)
- [Sign up](https://www.acoustic.com/demo)
- [Support](https://help.goacoustic.com)
- [Blog](https://www.acoustic.com/resources/blog)
- [Terms of service](https://www.acoustic.com/terms-conditions)
- [Privacy policy](https://www.acoustic.com/privacy-notice)
- [GitHub](https://github.com/Silverpop)
- [Status](https://status.goacoustic.com)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Silverpop: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/silverpop/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
