# Debitura

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

API Evangelist catalog entry for [Debitura](https://debitura.com) — an API-first international debt
collection platform for cross-border B2B and B2C receivables.

Debitura publishes three separate public REST APIs, one per role in the network:

| API | Paths | Operations | Schemas |
|---|---|---|---|
| [Customer](https://docs.debitura.com/clients) — creditors uploading invoices to collection | 44 | 53 | 81 |
| [Referral Partner](https://docs.debitura.com/referral-partners) — platforms embedding collection | 17 | 22 | 81 |
| [Collection Partner](https://docs.debitura.com/collection-partners) — agencies operating cases | 38 | 48 | 68 |

All three are OpenAPI 3.0.4, each on its own host, authenticating with an API key in the `XApiKey`
header. Debitura publishes its own [APIs.json](https://docs.debitura.com/apis.json), which is what
this profile was built from.

## What is in this repo

- `apis.yml` — the APIs.json 0.21 descriptor behind the [APIs.io](https://apis.io) listing
- `openapi/` — the OpenAPI definitions, harvested from Debitura and split one per tag
- `openapi/_original/` — the specs exactly as published, kept for provenance

## This is a catalog entry, not Debitura

This repo is API Evangelist's profile *about* Debitura. It is not operated by Debitura, and issues
here do not reach their team — for the product or an API key, go to
[debitura.com](https://debitura.com) or [docs.debitura.com](https://docs.debitura.com).

If something in this profile is wrong or out of date, an issue here is exactly the right place, and
so is the [APIs.io Inbox](https://github.com/api-search/inbox).
