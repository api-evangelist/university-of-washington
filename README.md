# University of Washington (university-of-washington)

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
