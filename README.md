# Klarify

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

Klarify is a San Francisco and Canada based mental-health technology company building an AI assistant, "Klara", for licensed therapists. The product handles the administrative and operational work around therapy rather than the therapy itself: an AI scribe that turns recorded sessions into structured clinical notes across 20+ note formats, treatment-plan generation, clinical letters and assessment reports, insurance claim filing and form completion, session preparation, between-session client resources, supervision prep, and visual session mindmaps. Klarify also operates a public directory of licensed therapists and clinics across Canada and the US, where profiles and articles are authored by the clinicians themselves.

Founded in 2024 by Moody Abdul (CEO) and Alexander Bergholm (CTO). Backed by: y-combinator (Spring 2026 batch).

- Website: https://www.klarify.ca/
- Help center: https://intercom.help/klarify/en/
- Blog: https://www.klarify.ca/blogs

## API surface

**Klarify publishes no public developer API.** Its `llms.txt` explicitly marks paths under `/api/` as internal infrastructure, and no OpenAPI, SDKs, CLI, MCP server, webhooks, sandbox, or `/.well-known/` discovery documents were found. Spec-dependent artifacts (openapi, overlays, scopes, errors, data model, agent skills, Arazzo) are therefore not applicable rather than missing.

## Artifacts

- `llms/klarify-llms.txt` — the provider's own `llms.txt`, saved verbatim (a genuinely well-authored one).
- `conformance/klarify-conformance.yml` — self-asserted HIPAA / PIPEDA / PHIPA / UK GDPR posture, data-handling commitments, and disclosed subprocessors.
- `security/klarify-domain-security.yml` — probed TLS / HSTS / DNSSEC / CAA / SPF / DMARC.
- `well-known/klarify-well-known.yml` — negative result: no `/.well-known/` documents published.
