# University of Washington

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

The University of Washington (UW) is a public research university in Seattle, Washington, United States, and one of the few higher-education institutions in this catalog that genuinely engineers and operates its own API estate rather than only buying one. UW-IT's Enterprise Web Services (EWS) programme publishes a browsable service registry and institution-authored OpenAPI descriptions for the Student Web Service (SWS v5), the IdCard Web Service (IdCardWS v1), the Groups Web Service (GWS 2.3.x at groups.uw.edu), the Identity Registration Web Service (IRWS v2 and v3) and the Token Authentication Web Service (TAWS v2) — every one of them hosted on a University of Washington registrable domain, so the operator is the institution and not a platform vendor. The honest limit matters as much as the footprint: the specifications and Swagger UIs are public, but essentially every data resource behind them is gated by UW NetID (Microsoft Entra ID OIDC), an X.509 InCommon client certificate and named ASTRA authorisation roles, and the IRWS and TAWS runtimes are not reachable from the public internet at all. UW additionally operates two open, unauthenticated machine-readable surfaces of real value — an OAI-PMH 2.0 endpoint over the ResearchWorks DSpace 9.2 repository, and a signed SAML 2.0 / Shibboleth identity-provider metadata document registered in InCommon as urn:mace:incommon:washington.edu. No central open-data portal (data.uw.edu / data.washington.edu do not resolve) and no free public developer programme were found.

**Areas:** University · Higher Education · Education · United States · Washington · Association of American Universities · Public Research University · Research · Student Information · Identity · Identity Federation · Course Catalog

## University of Washington on APIs.io

Everything profiled for University of Washington is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-washington/](https://apis.io/providers/university-of-washington/)** — or go straight to one of the APIs or properties below.

### APIs (65)

- [UW-IT Enterprise Web Services Registry](https://apis.io/apis/university-of-washington/enterprise-web-services/) — Enterprise Web Services (EWS) is UW-IT's secure collection of REST/SOAP web services that let enterprise business applications access commonly shared source…
- [UW Shibboleth Identity Provider (InCommon)](https://apis.io/apis/university-of-washington/identity-federation/) — UW's Shibboleth identity provider publishes signed SAML 2.0 metadata at a stable URL — entityID urn:mace:incommon:washington.edu, scope washington.edu,…
- [ResearchWorks Repository (DSpace REST + OAI-PMH)](https://apis.io/apis/university-of-washington/researchworks-dspace/) — ResearchWorks is UW Libraries' institutional repository, running DSpace 9.2 on UW's own host. The DSpace REST root document is public (HTTP 200) and item…
- [Student Web Service (SWS) Campus API](https://apis.io/apis/university-of-washington/university-of-washington-campus-api/) — Student Web Service (SWS) Campus API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [IdCard Web Service (IdCardWS) Card API](https://apis.io/apis/university-of-washington/university-of-washington-card-api/) — IdCard Web Service (IdCardWS) Card API — a resource of the UW-IT IdCard Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) College API](https://apis.io/apis/university-of-washington/university-of-washington-college-api/) — Student Web Service (SWS) College API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Course API](https://apis.io/apis/university-of-washington/university-of-washington-course-api/) — Student Web Service (SWS) Course API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Curriculum API](https://apis.io/apis/university-of-washington/university-of-washington-curriculum-api/) — Student Web Service (SWS) Curriculum API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Degree API](https://apis.io/apis/university-of-washington/university-of-washington-degree-api/) — Student Web Service (SWS) Degree API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Degree Audit API](https://apis.io/apis/university-of-washington/university-of-washington-degreeaudit-api/) — Student Web Service (SWS) Degree Audit API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Degree Audit Exception API](https://apis.io/apis/university-of-washington/university-of-washington-degreeauditexception-api/) — Student Web Service (SWS) Degree Audit Exception API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step…
- [Student Web Service (SWS) Degree Audit Program API](https://apis.io/apis/university-of-washington/university-of-washington-degreeauditprogram-api/) — Student Web Service (SWS) Degree Audit Program API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step…
- [Student Web Service (SWS) Degree Audit Status API](https://apis.io/apis/university-of-washington/university-of-washington-degreeauditstatus-api/) — Student Web Service (SWS) Degree Audit Status API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step…
- [Student Web Service (SWS) Department API](https://apis.io/apis/university-of-washington/university-of-washington-department-api/) — Student Web Service (SWS) Department API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Enrollment API](https://apis.io/apis/university-of-washington/university-of-washington-enrollment-api/) — Student Web Service (SWS) Enrollment API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Enrollment Major API](https://apis.io/apis/university-of-washington/university-of-washington-enrollmentmajor-api/) — Student Web Service (SWS) Enrollment Major API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from…
- [Student Web Service (SWS) Major Students API](https://apis.io/apis/university-of-washington/university-of-washington-majorstudents-api/) — Student Web Service (SWS) Major Students API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from…
- [Student Web Service (SWS) Notice API](https://apis.io/apis/university-of-washington/university-of-washington-notice-api/) — Student Web Service (SWS) Notice API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Person API](https://apis.io/apis/university-of-washington/university-of-washington-person-api/) — Student Web Service (SWS) Person API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Personal Financial API](https://apis.io/apis/university-of-washington/university-of-washington-personalfinancial-api/) — Student Web Service (SWS) Personal Financial API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step…
- [IdCard Web Service (IdCardWS) Photo API](https://apis.io/apis/university-of-washington/university-of-washington-photo-api/) — IdCard Web Service (IdCardWS) Photo API — a resource of the UW-IT IdCard Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Program API](https://apis.io/apis/university-of-washington/university-of-washington-program-api/) — Student Web Service (SWS) Program API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Registration API](https://apis.io/apis/university-of-washington/university-of-washington-registration-api/) — Student Web Service (SWS) Registration API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [UW Enterprise Web Services Resource List API](https://apis.io/apis/university-of-washington/university-of-washington-resourcelist-api/) — UW Enterprise Web Services Resource List API — a discovery resource published at the root of both the Student Web Service and the IdCard Web Service.…
- [Student Web Service (SWS) Schedule API](https://apis.io/apis/university-of-washington/university-of-washington-schedule-api/) — Student Web Service (SWS) Schedule API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Section API](https://apis.io/apis/university-of-washington/university-of-washington-section-api/) — Student Web Service (SWS) Section API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Term API](https://apis.io/apis/university-of-washington/university-of-washington-term-api/) — Student Web Service (SWS) Term API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [Student Web Service (SWS) Test Score API](https://apis.io/apis/university-of-washington/university-of-washington-testscore-api/) — Student Web Service (SWS) Test Score API — a resource of the UW-IT Student Web Service, split out per resource by the API Evangelist refine step from the…
- [UW Enterprise Web Services Version API](https://apis.io/apis/university-of-washington/university-of-washington-version-api/) — UW Enterprise Web Services Version API — a discovery resource published at the root of both the Student Web Service and the IdCard Web Service. Per-path…
- [University of Washington Account API](https://apis.io/apis/university-of-washington/university-of-washington-account-api/) — The Account API from University of Washington — 3 operation(s) for account.
- [University of Washington Account.canonical API](https://apis.io/apis/university-of-washington/university-of-washington-account-canonical-api/) — The account.canonical API from University of Washington — 1 operation(s) for account.canonical.
- [University of Washington Account.gps API](https://apis.io/apis/university-of-washington/university-of-washington-account-gps-api/) — The account.gps API from University of Washington — 1 operation(s) for account.gps.
- [University of Washington Account.history API](https://apis.io/apis/university-of-washington/university-of-washington-account-history-api/) — The account.history API from University of Washington — 1 operation(s) for account.history.
- [University of Washington Account.mail API](https://apis.io/apis/university-of-washington/university-of-washington-account-mail-api/) — The account.mail API from University of Washington — 1 operation(s) for account.mail.
- [University of Washington Account.subscription API](https://apis.io/apis/university-of-washington/university-of-washington-account-subscription-api/) — The account.subscription API from University of Washington — 1 operation(s) for account.subscription.
- [University of Washington Account.subscription.history API](https://apis.io/apis/university-of-washington/university-of-washington-account-subscription-history-api/) — The account.subscription.history API from University of Washington — 1 operation(s) for account.subscription.history.
- [University of Washington Account.subscription.pac API](https://apis.io/apis/university-of-washington/university-of-washington-account-subscription-pac-api/) — The account.subscription.pac API from University of Washington — 1 operation(s) for account.subscription.pac.
- [University of Washington Account.subscription.rule API](https://apis.io/apis/university-of-washington/university-of-washington-account-subscription-rule-api/) — The account.subscription.rule API from University of Washington — 1 operation(s) for account.subscription.rule.
- [University of Washington Auth API](https://apis.io/apis/university-of-washington/university-of-washington-auth-api/) — The Auth API from University of Washington — 1 operation(s) for auth.
- [University of Washington Crn API](https://apis.io/apis/university-of-washington/university-of-washington-crn-api/) — The Crn API from University of Washington — 1 operation(s) for crn.
- [University of Washington D Subscription.compat API](https://apis.io/apis/university-of-washington/university-of-washington-d-subscription-compat-api/) — The D_subscription.compat API from University of Washington — 1 operation(s) for d_subscription.compat.
- [University of Washington Entity API](https://apis.io/apis/university-of-washington/university-of-washington-entity-api/) — The entity API from University of Washington — 2 operation(s) for entity.
- [University of Washington Entity.canonical API](https://apis.io/apis/university-of-washington/university-of-washington-entity-canonical-api/) — The entity.canonical API from University of Washington — 1 operation(s) for entity.canonical.
- [University of Washington Entity.category API](https://apis.io/apis/university-of-washington/university-of-washington-entity-category-api/) — The entity.category API from University of Washington — 1 operation(s) for entity.category.
- [University of Washington Entity.history API](https://apis.io/apis/university-of-washington/university-of-washington-entity-history-api/) — The entity.history API from University of Washington — 1 operation(s) for entity.history.
- [University of Washington Entity.join API](https://apis.io/apis/university-of-washington/university-of-washington-entity-join-api/) — The entity.join API from University of Washington — 1 operation(s) for entity.join.
- [University of Washington Entity.name API](https://apis.io/apis/university-of-washington/university-of-washington-entity-name-api/) — The entity.name API from University of Washington — 1 operation(s) for entity.name.
- [University of Washington Entity.pac API](https://apis.io/apis/university-of-washington/university-of-washington-entity-pac-api/) — The entity.pac API from University of Washington — 1 operation(s) for entity.pac.
- [University of Washington Entity.pds API](https://apis.io/apis/university-of-washington/university-of-washington-entity-pds-api/) — The entity.pds API from University of Washington — 1 operation(s) for entity.pds.
- [University of Washington Entity.profile.name API](https://apis.io/apis/university-of-washington/university-of-washington-entity-profile-name-api/) — The entity.profile.name API from University of Washington — 1 operation(s) for entity.profile.name.
- [University of Washington Entity.profile.pronoun API](https://apis.io/apis/university-of-washington/university-of-washington-entity-profile-pronoun-api/) — The entity.profile.pronoun API from University of Washington — 1 operation(s) for entity.profile.pronoun.
- [University of Washington Entity.profile.recovery API](https://apis.io/apis/university-of-washington/university-of-washington-entity-profile-recovery-api/) — The entity.profile.recovery API from University of Washington — 1 operation(s) for entity.profile.recovery.
- [University of Washington Entity.sponsor API](https://apis.io/apis/university-of-washington/university-of-washington-entity-sponsor-api/) — The entity.sponsor API from University of Washington — 1 operation(s) for entity.sponsor.
- [University of Washington Entity.sponsor.avf API](https://apis.io/apis/university-of-washington/university-of-washington-entity-sponsor-avf-api/) — The entity.sponsor.avf API from University of Washington — 1 operation(s) for entity.sponsor.avf.
- [University of Washington Entity.verify API](https://apis.io/apis/university-of-washington/university-of-washington-entity-verify-api/) — The entity.verify API from University of Washington — 1 operation(s) for entity.verify.
- [University of Washington Groups API](https://apis.io/apis/university-of-washington/university-of-washington-groups-api/) — Group information--except membership
- [University of Washington Membership API](https://apis.io/apis/university-of-washington/university-of-washington-membership-api/) — Group membership information
- [University of Washington Name API](https://apis.io/apis/university-of-washington/university-of-washington-name-api/) — The Name API from University of Washington — 1 operation(s) for name.
- [University of Washington Pdsentry API](https://apis.io/apis/university-of-washington/university-of-washington-pdsentry-api/) — The Pdsentry API from University of Washington — 2 operation(s) for pdsentry.
- [University of Washington Reference.subscription.rule API](https://apis.io/apis/university-of-washington/university-of-washington-reference-subscription-rule-api/) — The reference.subscription.rule API from University of Washington — 1 operation(s) for reference.subscription.rule.
- [University of Washington Regid API](https://apis.io/apis/university-of-washington/university-of-washington-regid-api/) — The Regid API from University of Washington — 3 operation(s) for regid.
- [University of Washington Searches API](https://apis.io/apis/university-of-washington/university-of-washington-searches-api/) — Group and member searches
- [University of Washington Social API](https://apis.io/apis/university-of-washington/university-of-washington-social-api/) — The Social API from University of Washington — 1 operation(s) for social.
- [University of Washington Subscription.compat API](https://apis.io/apis/university-of-washington/university-of-washington-subscription-compat-api/) — The Subscription.compat API from University of Washington — 1 operation(s) for subscription.compat.
- [University of Washington Pre Auth API](https://apis.io/apis/university-of-washington/university-of-washington-pre-auth-api/) — The Pre Auth API from University of Washington — 1 operation(s) for pre auth.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [University Of Washington Agentic Access](https://apis.io/agentic-access/university-of-washington/university-of-washington-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Course](https://apis.io/schemas/university-of-washington/university-of-washington-course/)
- [Photo](https://apis.io/schemas/university-of-washington/university-of-washington-photo/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [University Of Washington Course Structure](https://apis.io/json-structure/university-of-washington/university-of-washington-course-structure/)
- [University Of Washington Photo Structure](https://apis.io/json-structure/university-of-washington/university-of-washington-photo-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Washington Context](https://apis.io/jsonld/university-of-washington/university-of-washington-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Washington Enterprise Web Services Vocabulary](https://apis.io/vocabularies/university-of-washington/university-of-washington-vocabulary/)

#### Examples (2)

Example requests and responses.

- [University Of Washington Get Course Example](https://apis.io/examples/university-of-washington/university-of-washington-get-course-example/)
- [University Of Washington Get Photo Example](https://apis.io/examples/university-of-washington/university-of-washington-get-photo-example/)

#### Collections (26)

Postman and Open Collection request collections.

- [IdCard Web Service (IdCardWS) Campus API](https://apis.io/collections/university-of-washington/open-university-of-washington-campus-api/)
- [IdCard Web Service (IdCardWS) Campus Card API](https://apis.io/collections/university-of-washington/open-university-of-washington-card-api/)
- [IdCard Web Service (IdCardWS) Campus College API](https://apis.io/collections/university-of-washington/open-university-of-washington-college-api/)
- [IdCard Web Service (IdCardWS) Campus Course API](https://apis.io/collections/university-of-washington/open-university-of-washington-course-api/)
- [IdCard Web Service (IdCardWS) Campus Curriculum API](https://apis.io/collections/university-of-washington/open-university-of-washington-curriculum-api/)
- [IdCard Web Service (IdCardWS) Campus Degree API](https://apis.io/collections/university-of-washington/open-university-of-washington-degree-api/)
- [IdCard Web Service (IdCardWS) Campus DegreeAudit API](https://apis.io/collections/university-of-washington/open-university-of-washington-degreeaudit-api/)
- [IdCard Web Service (IdCardWS) Campus DegreeAuditException API](https://apis.io/collections/university-of-washington/open-university-of-washington-degreeauditexception-api/)
- [IdCard Web Service (IdCardWS) Campus DegreeAuditProgram API](https://apis.io/collections/university-of-washington/open-university-of-washington-degreeauditprogram-api/)
- [IdCard Web Service (IdCardWS) Campus DegreeAuditStatus API](https://apis.io/collections/university-of-washington/open-university-of-washington-degreeauditstatus-api/)
- [IdCard Web Service (IdCardWS) Campus Department API](https://apis.io/collections/university-of-washington/open-university-of-washington-department-api/)
- [IdCard Web Service (IdCardWS) Campus Enrollment API](https://apis.io/collections/university-of-washington/open-university-of-washington-enrollment-api/)
- [IdCard Web Service (IdCardWS) Campus EnrollmentMajor API](https://apis.io/collections/university-of-washington/open-university-of-washington-enrollmentmajor-api/)
- [IdCard Web Service (IdCardWS) Campus MajorStudents API](https://apis.io/collections/university-of-washington/open-university-of-washington-majorstudents-api/)
- [IdCard Web Service (IdCardWS) Campus Notice API](https://apis.io/collections/university-of-washington/open-university-of-washington-notice-api/)
- [IdCard Web Service (IdCardWS) Campus Person API](https://apis.io/collections/university-of-washington/open-university-of-washington-person-api/)
- [IdCard Web Service (IdCardWS) Campus PersonalFinancial API](https://apis.io/collections/university-of-washington/open-university-of-washington-personalfinancial-api/)
- [IdCard Web Service (IdCardWS) Campus Photo API](https://apis.io/collections/university-of-washington/open-university-of-washington-photo-api/)
- [IdCard Web Service (IdCardWS) Campus Program API](https://apis.io/collections/university-of-washington/open-university-of-washington-program-api/)
- [IdCard Web Service (IdCardWS) Campus Registration API](https://apis.io/collections/university-of-washington/open-university-of-washington-registration-api/)
- [IdCard Web Service (IdCardWS) Campus ResourceList API](https://apis.io/collections/university-of-washington/open-university-of-washington-resourcelist-api/)
- [IdCard Web Service (IdCardWS) Campus Schedule API](https://apis.io/collections/university-of-washington/open-university-of-washington-schedule-api/)
- [IdCard Web Service (IdCardWS) Campus Section API](https://apis.io/collections/university-of-washington/open-university-of-washington-section-api/)
- [IdCard Web Service (IdCardWS) Campus Term API](https://apis.io/collections/university-of-washington/open-university-of-washington-term-api/)
- [IdCard Web Service (IdCardWS) Campus TestScore API](https://apis.io/collections/university-of-washington/open-university-of-washington-testscore-api/)
- …and 1 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of Washington — jsonschema rules](https://apis.io/rules/university-of-washington/university-of-washington-jsonschema-spectral-rules/)
- [University of Washington API Rules](https://apis.io/rules/university-of-washington/university-of-washington-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Washington Authentication](https://apis.io/security/university-of-washington/university-of-washington-authentication/)
- [University Of Washington Domain Security](https://apis.io/security/university-of-washington/university-of-washington-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Washington Plans Pricing](https://apis.io/plans/university-of-washington/university-of-washington-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Washington Rate Limits](https://apis.io/rate-limits/university-of-washington/university-of-washington-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Washington Finops](https://apis.io/finops/university-of-washington/university-of-washington-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.washington.edu/)
- [Documentation](https://it.uw.edu/summary/enterprise-web-services/)
- [API reference](https://webservices.washington.edu/service/browse/index.html)
- [Support](https://it.uw.edu/)
- [Blog](https://www.washington.edu/news/feed/)
- [Terms of service](https://www.washington.edu/online/terms/)
- [Privacy policy](https://www.washington.edu/online/privacy/)

## API Evangelist rating

**Kin Score 38.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 49.6 |
| Contract governance | 23.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 45.2 |
| Access clarity | 26.3 |

**Agent readiness 26.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-washington/](https://apis.io/providers/university-of-washington/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Washington: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-washington/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
