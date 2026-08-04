# University of Washington (university-of-washington)

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

The University of Washington (UW) is a public research university in Seattle, Washington, United States, ranked #52 in the QS World University Rankings 2025. UW maintains a mature, institutionally documented developer footprint through UW-IT Enterprise Web Services (EWS), a public registry of REST/SOAP web services with Swagger/OpenAPI documentation, plus an open DSpace repository (ResearchWorks) and active public GitHub organizations.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-washington/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-washington-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, United States, Student Information, Identity, Library, Open Data

## APIs

- **Student Web Service (SWS)** — Course, registration, section, person, and term data from the UW Student database (public/private API split; production access gated).
  - Docs: https://webservices.washington.edu/sws/
  - OpenAPI: https://ws.admin.washington.edu/student/swagger/index.html
- **IdCard Web Service** — Husky ID Card information such as cardholder photos (authenticated/gated).
  - Docs: https://webservices.washington.edu/idcardws/index.html
  - OpenAPI: https://ws.admin.washington.edu/idcard/swagger/index.html
- **Identity Registration Web Service (IRWS)** — UW-IT Identity Registry REST API (V1 and V2) for identity/person registry data (authenticated/gated).
  - Docs V2: https://iam-tools.u.washington.edu/apis/irwsv2/
  - Docs V1: https://iam-tools.u.washington.edu/apis/irwsv1/
- **UW-IT Enterprise Web Services Registry** — Public registry cataloging EWS services (Student, Person, Groups, HRP, IdCard, Financial, Space).
  - Docs: https://webservices.washington.edu/
  - Overview: https://it.uw.edu/summary/enterprise-web-services/
- **ResearchWorks Repository (DSpace REST + OAI-PMH)** — UW institutional repository for scholarly works with a public DSpace REST API and OAI-PMH metadata harvesting.
  - Docs: https://digital.lib.washington.edu/researchworks/
  - OAI-PMH: https://digital.lib.washington.edu/server/oai/request?verb=Identify

## Plans

- [plans/university-of-washington-plans-pricing.yml](plans/university-of-washington-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-washington-rate-limits.yml](rate-limits/university-of-washington-rate-limits.yml)

## FinOps

- [finops/university-of-washington-finops.yml](finops/university-of-washington-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.washington.edu/
- Developer Portal: https://webservices.washington.edu/
- GitHub: https://github.com/uw-it-aca
- GitHub: https://github.com/uwwebservices
- LinkedIn: https://www.linkedin.com/school/university-of-washington/

## Notes

- All documentation, registry, and repository URLs were verified live (HTTP 200) on 2026-06-03.
- UW Enterprise Web Services expose both public and private APIs; production data endpoints require a UW NetID, certificate-based authentication, and approved access. Only the documentation, registry, and Swagger specs are publicly browsable.
- The `uwwebservices` GitHub org had no public repositories at review time; `uw-it-aca` (Student & Educational Technology Services) hosts numerous public repositories.
- No endpoints were fabricated; only confirmed, reachable URLs are cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
