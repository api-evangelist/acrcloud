# ACRCloud (acrcloud)

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
