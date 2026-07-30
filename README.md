# Klarify

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
