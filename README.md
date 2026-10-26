# Cflow (cflow)

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

Cflow is a cloud-based workflow automation platform that helps organizations streamline and optimize business processes. It offers a drag-and-drop workflow builder, customizable forms, rule-based routing, approval flows, integrations with popular business applications, and real-time analytics. Cflow exposes a REST API allowing developers to list workflows, submit and manage requests, approve or reject tasks, and manage users and roles programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Automations
- Business Process Automation
- Integrations
- No-Code
- Platform
- Protocols
- Rules
- Workflows

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Cflow Workflow API

The Cflow Workflow API provides REST endpoints for retrieving workflows, creating and managing requests, approving or rejecting requests at each stage, creating draft requests, and administering users and roles. All business objects and integration objects are exposed as JSON resources and authentication is handled via API key, user key, and username headers.

- **Human URL:** [https://www.cflowapps.com](https://www.cflowapps.com)
- **Base URL:** `https://us.cflowapps.com`

#### Tags

- Approvals
- Automation
- Integrations
- Protocols
- Requests
- Roles
- Rules
- Users
- Workflows

#### Properties

- [Documentation](https://www.cflowapps.com/workflow/workflow-api/)
- [OpenAPI](openapi/cflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/workflow.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/stage.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/request.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/user.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/role.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cflow-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cflowapps)
- [Website](https://www.cflowapps.com)
- [Documentation](https://www.cflowapps.com/workflow/workflow-api/)
- [Sign Up](https://www.cflowapps.com/sign-up/)
- [Pricing](https://www.cflowapps.com/pricing/)
- [Blog](https://www.cflowapps.com/blog/)
- [Support](https://help.cflowapps.com/)
- [Terms of Service](https://www.cflowapps.com/terms-of-use/)
- [Privacy Policy](https://www.cflowapps.com/privacy-policy/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.cflowapps.com/integrations/)
- [L L Ms Txt](https://cflowapps.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
