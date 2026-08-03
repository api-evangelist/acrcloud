# ACRCloud (acrcloud)

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

ACRCloud provides automatic content recognition (ACR) APIs for music and audio. The HMAC-signed Identification API recognizes music, custom audio, live channels, and humming from short audio samples or fingerprints, while the bearer-token Console and Metadata APIs manage buckets, file-scanning containers, broadcast-monitoring projects, and rich third-party music metadata.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/acrcloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/acrcloud/refs/heads/main/apis.yml)

## Tags

- Audio
- Music Recognition
- Audio Fingerprinting
- Broadcast Monitoring
- Metadata

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### ACRCloud Identification API

HMAC-SHA1 signed recognition endpoint that identifies music, custom audio, live channels, humming, and music/speech segments from a short audio sample or a precomputed fingerprint, returning matched track metadata.

- **Human URL:** [https://docs.acrcloud.com/reference/identification-api](https://docs.acrcloud.com/reference/identification-api)
- **Base URL:** `https://identify-eu-west-1.acrcloud.com/v1`

#### Tags

- Identification
- Music Recognition
- Audio Fingerprinting

#### Properties

- [Documentation](https://docs.acrcloud.com/reference/identification-api)
- [API Reference](https://docs.acrcloud.com/reference/identification-api/identification-api)
- [OpenAPI](openapi/acrcloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/acrcloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/acrcloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ACRCloud File Scanning API

Bearer-token managed file-scanning containers that detect recognized content from configured buckets across whole files, supporting both clean line-in audio and recorded/noisy audio.

- **Human URL:** [https://docs.acrcloud.com/reference/console-api/file-scanning](https://docs.acrcloud.com/reference/console-api/file-scanning)
- **Base URL:** `https://api-v2.acrcloud.com/api`

#### Tags

- File Scanning
- Content Detection
- Buckets

#### Properties

- [Documentation](https://docs.acrcloud.com/reference/console-api/file-scanning)
- [OpenAPI](openapi/acrcloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/acrcloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/acrcloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ACRCloud Broadcast Monitoring API

Broadcast-monitoring projects that continuously identify content across radio, TV, and custom streams, with channel management and realtime or delayed result callbacks.

- **Human URL:** [https://docs.acrcloud.com/reference/console-api/bm-projects/broadcast-database-projects](https://docs.acrcloud.com/reference/console-api/bm-projects/broadcast-database-projects)
- **Base URL:** `https://api-v2.acrcloud.com/api`

#### Tags

- Broadcast Monitoring
- Channels
- Realtime

#### Properties

- [Documentation](https://docs.acrcloud.com/reference/console-api/bm-projects/broadcast-database-projects)
- [OpenAPI](openapi/acrcloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/acrcloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/acrcloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ACRCloud Buckets & Metadata API

Manage custom recognition buckets, upload and manage audio files and fingerprints, and enrich tracks via the external Metadata API by ISRC, ACRID, source URL, or free-text query across Spotify, Deezer, YouTube, and Apple Music.

- **Human URL:** [https://docs.acrcloud.com/reference/console-api/buckets](https://docs.acrcloud.com/reference/console-api/buckets)
- **Base URL:** `https://api-v2.acrcloud.com/api`

#### Tags

- Buckets
- Audio Files
- Metadata

#### Properties

- [Documentation](https://docs.acrcloud.com/reference/console-api/buckets)
- [API Reference](https://docs.acrcloud.com/reference/metadata-api)
- [OpenAPI](openapi/acrcloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/acrcloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/acrcloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ACRCloud Console API

Bearer-token administrative API for managing projects, base/UCF projects, access keys, and the developer access tokens used to authenticate the Console, file-scanning, and broadcast-monitoring resources.

- **Human URL:** [https://docs.acrcloud.com/reference/console-api](https://docs.acrcloud.com/reference/console-api)
- **Base URL:** `https://api-v2.acrcloud.com/api`

#### Tags

- Console
- Projects
- Access Tokens

#### Properties

- [Documentation](https://docs.acrcloud.com/reference/console-api)
- [API Reference](https://docs.acrcloud.com/reference/console-api/accesstoken)
- [OpenAPI](openapi/acrcloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/acrcloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/acrcloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/acrcloud)
- [LinkedIn](https://www.linkedin.com/company/acrcloud)
- [Website](https://www.acrcloud.com)
- [Documentation](https://docs.acrcloud.com)
- [Plans](plans/acrcloud-plans-pricing.yml)
- [Rate Limits](rate-limits/acrcloud-rate-limits.yml)
- [Fin Ops](finops/acrcloud-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
