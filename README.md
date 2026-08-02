# Debitura

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
