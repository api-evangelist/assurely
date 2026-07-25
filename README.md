# Assurely (assurely)

Assurely is a United States insurtech and managing general agent (MGA) founded by David Carpentier and Ty Sagalow that builds and distributes commercial property-and-casualty insurance for companies with unconventional funding models — most notably TigerMark, a directors-and-officers (D&O) product written for Regulation CF / Regulation A crowdfunding issuers and early-stage startups that incumbent carriers decline. Assurely positioned itself as an "Insurance-as-a-Service" (IaaS) provider embedding industry-specific products plus a multi-carrier marketplace into vertical SaaS operating systems, and stated licensing in all 50 states and Bermuda. Assurely was acquired by Equal Parts on 2025-06-26.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/assurely/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/assurely/refs/heads/main/apis.yml)

## Tags

- Insurance
- United States
- Insurtech
- Embedded Insurance
- Managing General Agent
- Property and Casualty
- Directors and Officers
- Broker
- Crowdfunding

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

**None.** Assurely publishes no public API.

There is no developer portal, no API reference, no downloadable OpenAPI or Swagger definition, no Postman workspace, no GraphQL endpoint, and no webhook or event catalog. `developer.assurely.com` and `developers.assurely.com` do not resolve. `docs.assurely.com` is an unconfigured `ghs.google.com` mapping that fails TLS on 443 and returns HTTP 404 over plain HTTP.

"Embedded" in Assurely's marketing meant a commercial revenue-share partnership with white-labeled, partner-branded quote-and-bind web pages — `tigermark.assurely.com/partner/wefunder`, `client.assurely.com/partner/coconstruct` — backed by human advisory and administration. It was a hosted-page distribution model, not a programmable one. A sweep of 188 unique archived `assurely.com` URLs found zero developer, docs, swagger, or openapi paths.

### ACORD posture

**No ACORD reference found.** No mention of ACORD, AL3, ACORD XML, NGDS, IVANS, agency download, Applied Epic, or Vertafore AMS360 anywhere on the live or archived site. Assurely distributed through partner platforms and its own hosted flows rather than the IVANS agency-download plumbing that carries ACORD standards between US carriers and independent agencies.

### Quote / bind / issue / FNOL

| Verb | Exposure |
| --- | --- |
| Quote | Hosted web flow only (now offline). No API. |
| Bind | Hosted web flow only. No API. |
| Issue | Not exposed. |
| FNOL / Claims | Not exposed. No claims surface documented or archived. |

### Current status

As of the 2026-07-25 review Assurely's public estate is offline:

- `https://www.assurely.com/` — **HTTP 404**, Squarespace "Website Expired" page
- `https://api.assurely.com/` — dangling CNAME to a deleted AWS load balancer, does not resolve
- `https://client.assurely.com/` — same dangling CNAME, unreachable
- `https://tigermark.assurely.com/` — same dangling CNAME, unreachable

This is the expected outcome for a small US MGA. The United States has no federal insurance regulator and no open-insurance mandate — insurance is regulated state by state under NAIC model laws — so nothing compels a carrier, MGA, or broker to publish an API, and Assurely never did.

## Links

- [Website](https://www.assurely.com/) (expired, HTTP 404)
- [LinkedIn](https://www.linkedin.com/company/assurely)
- [Equal Parts acquisition announcement (2025-06-26)](https://www.businesswire.com/news/home/20250626192100/en/Equal-Parts-Continues-Expansion-with-Acquisition-of-Assurely-Adding-Proprietary-DO-Platform-for-Startups)

## Review

See [review.yml](review.yml) for the full API Evangelist reviewer findings, probe log with HTTP statuses, and source list.
