# Google Workspace APIs (google-suites)

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

Collection of APIs for Google Workspace (formerly G Suite) services including Gmail, Calendar, Drive, Docs, Sheets, and more.

**APIs.json:** [https://workspace.google.com/](https://workspace.google.com/)

## Scope

- **Type:** Index

## Tags

- Cloud Storage
- Collaboration
- Email
- Office Suite
- Productivity

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Gmail API

Access Gmail mailboxes and send mail.

- **Human URL:** [https://developers.google.com/gmail/api](https://developers.google.com/gmail/api)
- **Base URL:** `https://gmail.googleapis.com`

#### Tags

- Email
- Messaging

#### Properties

- [OpenAPI](https://gmail.googleapis.com/$discovery/rest?version=v1) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developers.google.com/gmail/api/guides)
- [Authentication](https://developers.google.com/gmail/api/auth/about-auth)
- [Postman Collection](collections/google-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Calendar API

Manage calendars and events.

- **Human URL:** [https://developers.google.com/calendar](https://developers.google.com/calendar)
- **Base URL:** `https://www.googleapis.com/calendar/v3`

#### Tags

- Calendar
- Events
- Scheduling

#### Properties

- [OpenAPI](https://www.googleapis.com/discovery/v1/apis/calendar/v3/rest) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developers.google.com/calendar/api/guides/overview)
- [Quickstart](https://developers.google.com/calendar/api/quickstart)
- [Postman Collection](collections/google-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Drive API

Store and share files in the cloud.

- **Human URL:** [https://developers.google.com/drive](https://developers.google.com/drive)
- **Base URL:** `https://www.googleapis.com/drive/v3`

#### Tags

- Cloud
- Files
- Storage

#### Properties

- [OpenAPI](https://www.googleapis.com/discovery/v1/apis/drive/v3/rest) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developers.google.com/drive/api/guides/about-sdk)
- [Pricing](https://workspace.google.com/pricing)
- [Postman Collection](collections/google-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Docs API

Create and edit documents programmatically.

- **Human URL:** [https://developers.google.com/docs/api](https://developers.google.com/docs/api)
- **Base URL:** `https://docs.googleapis.com`

#### Tags

- Documents
- Word Processing

#### Properties

- [OpenAPI](https://docs.googleapis.com/$discovery/rest?version=v1) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developers.google.com/docs/api/how-tos/overview)
- [Samples](https://developers.google.com/docs/api/samples)
- [Postman Collection](collections/google-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Sheets API

Read and write spreadsheet data.

- **Human URL:** [https://developers.google.com/sheets/api](https://developers.google.com/sheets/api)
- **Base URL:** `https://sheets.googleapis.com`

#### Tags

- Data
- Spreadsheets

#### Properties

- [OpenAPI](https://sheets.googleapis.com/$discovery/rest?version=v4) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developers.google.com/sheets/api/guides/concepts)
- [Quickstart](https://developers.google.com/sheets/api/quickstart)
- [Postman Collection](collections/google-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Slides API

Create and edit presentations.

- **Human URL:** [https://developers.google.com/slides](https://developers.google.com/slides)
- **Base URL:** `https://slides.googleapis.com`

#### Tags

- Presentations
- Slides

#### Properties

- [OpenAPI](https://slides.googleapis.com/$discovery/rest?version=v1) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developers.google.com/slides/how-tos/overview)
- [Postman Collection](collections/google-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Google Meet API

Manage video conferencing.

- **Human URL:** [https://developers.google.com/meet](https://developers.google.com/meet)
- **Base URL:** `https://meet.googleapis.com`

#### Tags

- Meetings
- Video Conferencing

#### Properties

- [Documentation](https://developers.google.com/meet/api)
- [Postman Collection](collections/google-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Admin SDK Directory API

Manage users, groups, and organizational units.

- **Human URL:** [https://developers.google.com/admin-sdk/directory](https://developers.google.com/admin-sdk/directory)
- **Base URL:** `https://admin.googleapis.com`

#### Tags

- Administration
- Groups
- Users

#### Properties

- [OpenAPI](https://admin.googleapis.com/$discovery/rest?version=directory_v1) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developers.google.com/admin-sdk/directory/reference/rest)
- [Postman Collection](collections/google-suites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-suites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/googleworkspace)
- [LinkedIn](https://www.linkedin.com/showcase/googleworkspace)
- [Authentication](https://developers.google.com/workspace/guides/auth-overview)
- [Console](https://console.cloud.google.com)
- [Pricing](https://workspace.google.com/pricing)
- [Support](https://workspace.google.com/support)
- [Terms of Service](https://workspace.google.com/terms)
- [S D Ks](https://developers.google.com/workspace/guides/client-libraries)
- [Integrations](https://workspace.google.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
