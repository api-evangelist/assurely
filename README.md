# Assurely (assurely)

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
