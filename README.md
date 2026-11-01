# Zero Trust Network Access

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

Zero Trust Network Access (ZTNA) is a security framework and product category that grants access to private applications and resources based on identity, device posture, and context, rather than network location. ZTNA replaces the implicit trust of legacy VPNs with explicit per-request verification, creating one-to-one encrypted tunnels between authenticated users and the specific applications they are authorized to use. This topic collects the leading ZTNA vendors, the standards bodies that govern the underlying primitives, and the data schemas used to describe access policies, identities, devices, and resources.

**Areas:** Access Control · Cloud Security · Cybersecurity · Identity and Access Management · Network Access · Network Security · Security · VPN Replacement · Zero Trust · ZTNA

## Zero Trust Network Access on APIs.io

Everything profiled for Zero Trust Network Access is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/zero-trust-network-access/](https://apis.io/providers/zero-trust-network-access/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Cloudflare Zero Trust API](https://apis.io/apis/zero-trust-network-access/cloudflare-zero-trust/) — Cloudflare Zero Trust (formerly Cloudflare for Teams / Cloudflare Access) provides ZTNA, secure web gateway, browser isolation, CASB, and DLP through a…
- [Zscaler Private Access (ZPA) API](https://apis.io/apis/zero-trust-network-access/zscaler-zpa/) — Zscaler Private Access is a cloud-native ZTNA service that connects authenticated users to private applications without exposing them to the internet or…
- [Netskope Private Access API](https://apis.io/apis/zero-trust-network-access/netskope-private-access/) — Netskope Private Access provides ZTNA as part of the Netskope SASE platform, brokering authenticated access to private applications across cloud and…
- [Palo Alto Prisma Access (Prisma SASE) API](https://apis.io/apis/zero-trust-network-access/palo-alto-prisma-access/) — Palo Alto Networks Prisma Access offers cloud-delivered ZTNA, SWG, and FWaaS as part of the Prisma SASE platform. The Prisma Access REST API exposes…
- [Tailscale API](https://apis.io/apis/zero-trust-network-access/tailscale-api/) — Tailscale is a WireGuard-based mesh-VPN ZTNA platform that exposes a REST API for managing devices, ACL policies, tailnet keys, DNS, and audit logs. It…
- [Twingate API](https://apis.io/apis/zero-trust-network-access/twingate-api/) — Twingate is a software-defined ZTNA platform that exposes a GraphQL Admin API for managing remote networks, resources, groups, users, service accounts, and…
- [Zero Trust Network Access Deployment Groups API](https://apis.io/apis/zero-trust-network-access/zero-trust-network-access-deployment-groups-api/) — Account-level WARP deployment groups.
- [Zero Trust Network Access Devices API](https://apis.io/apis/zero-trust-network-access/zero-trust-network-access-devices-api/) — WARP devices enrolled in Zero Trust.
- [Zero Trust Network Access DEX Tests API](https://apis.io/apis/zero-trust-network-access/zero-trust-network-access-dex-tests-api/) — Digital Experience Monitoring tests.
- [Zero Trust Network Access IP Profiles API](https://apis.io/apis/zero-trust-network-access/zero-trust-network-access-ip-profiles-api/) — WARP device IP profiles.
- [Zero Trust Network Access Registrations API](https://apis.io/apis/zero-trust-network-access/zero-trust-network-access-registrations-api/) — Per-user WARP registrations on a device.
- [Zero Trust Network Access WARP Override API](https://apis.io/apis/zero-trust-network-access/zero-trust-network-access-warp-override-api/) — Global Cloudflare WARP override state.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/zero-trust-network-access/](https://apis.io/graphqls/zero-trust-network-access/zero-trust-network-access-graphql/)

#### JSON Schema (3)

The data models the API reads and writes.

- [ZTNA Protected Application](https://apis.io/schemas/zero-trust-network-access/zero-trust-network-access-application/)
- [ZTNA Device Posture Profile](https://apis.io/schemas/zero-trust-network-access/zero-trust-network-access-device-posture/)
- [ZTNA Access Policy](https://apis.io/schemas/zero-trust-network-access/zero-trust-network-access-policy/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Zero Trust Network Access Policy Structure](https://apis.io/json-structure/zero-trust-network-access/zero-trust-network-access-policy-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Zero Trust Network Access Context](https://apis.io/jsonld/zero-trust-network-access/zero-trust-network-access-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Zero Trust Network Access Vocabulary](https://apis.io/vocabularies/zero-trust-network-access/zero-trust-network-access-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Zero Trust Network Access Device Posture Example](https://apis.io/examples/zero-trust-network-access/zero-trust-network-access-device-posture-example/)
- [Zero Trust Network Access Policy Example](https://apis.io/examples/zero-trust-network-access/zero-trust-network-access-policy-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Cloudflare Zero Trust Network Access Deployment Groups API](https://apis.io/collections/zero-trust-network-access/open-zero-trust-network-access-deployment-groups-api/)
- [Cloudflare Zero Trust Network Access Devices API](https://apis.io/collections/zero-trust-network-access/open-zero-trust-network-access-devices-api/)
- [Cloudflare Zero Trust Network Access DEX Tests API](https://apis.io/collections/zero-trust-network-access/open-zero-trust-network-access-dex-tests-api/)
- [Cloudflare Zero Trust Network Access IP Profiles API](https://apis.io/collections/zero-trust-network-access/open-zero-trust-network-access-ip-profiles-api/)
- [Cloudflare Zero Trust Network Access Registrations API](https://apis.io/collections/zero-trust-network-access/open-zero-trust-network-access-registrations-api/)
- [Cloudflare Zero Trust Network Access WARP Override API](https://apis.io/collections/zero-trust-network-access/open-zero-trust-network-access-warp-override-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Zero Trust Network Access — jsonschema rules](https://apis.io/rules/zero-trust-network-access/zero-trust-network-access-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Zero Trust Network Access Domain Security](https://apis.io/security/zero-trust-network-access/zero-trust-network-access-domain-security/)
- [Zero Trust Network Access Vulnerability Disclosure](https://apis.io/security/zero-trust-network-access/zero-trust-network-access-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Zero Trust Network Access Plans Pricing](https://apis.io/plans/zero-trust-network-access/zero-trust-network-access-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Zero Trust Network Access Rate Limits](https://apis.io/rate-limits/zero-trust-network-access/zero-trust-network-access-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Zero Trust Network Access Finops](https://apis.io/finops/zero-trust-network-access/zero-trust-network-access-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/)
- [Compliance](https://www.cisa.gov/zero-trust-maturity-model)
- [GitHub](https://github.com/tailscale)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Zero Trust Network Access: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/zero-trust-network-access/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
