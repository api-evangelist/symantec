# Symantec (symantec)

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

Symantec (now part of Broadcom) is a leading enterprise cybersecurity company providing endpoint security, threat detection, data loss prevention, identity security, and network protection products. Symantec offers REST APIs for Endpoint Protection Manager (SEPM), Endpoint Security Cloud (SES), Endpoint Detection and Response (EDR), Data Loss Prevention (DLP), and the Integrated Cyber Defense Manager (ICDm) platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Broadcom
- Cybersecurity
- DLP
- EDR
- Endpoint Protection
- Endpoint Security
- Security
- Symantec

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Symantec Endpoint Protection Manager API

The SEPM REST API enables programmatic access to Symantec Endpoint Protection Manager for managing computers, groups, policies, and server configuration. Requires OAuth 2.0 authentication via the SEPM identity endpoint. Base URL is https://{sepm-host}:8446/sepm/api/v1.

- **Human URL:** [https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-protection/all/APIsSEP/Symantec-Endpoint-Security-API-commands1.html](https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-protection/all/APIsSEP/Symantec-Endpoint-Security-API-commands1.html)
- **Base URL:** `https://{sepm-host}:8446/sepm/api/v1`

#### Tags

- Computers
- Endpoint Protection
- Groups
- Policies
- Security Management
- SEPM

#### Properties

- [Documentation](https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-protection/all/APIsSEP/Symantec-Endpoint-Security-API-commands1.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/symantec/refs/heads/main/openapi/symantec-sepm-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://apidocs.symantec.com/home/SAEP)
- [Postman Collection](collections/symantec-sepm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/symantec-sepm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Symantec Endpoint Security API

The Symantec Endpoint Security (SES) REST API provides access to cloud-based endpoint security management including device inventory, threat events, incident management, and behavioral analytics. Requires OAuth 2.0 authentication. Documentation at apidocs.securitycloud.symantec.com.

- **Human URL:** [https://apidocs.securitycloud.symantec.com/](https://apidocs.securitycloud.symantec.com/)

#### Tags

- Behavioral Analytics
- Cloud Security
- Devices
- Endpoint Security
- Events
- Incidents
- SES

#### Properties

- [Documentation](https://apidocs.securitycloud.symantec.com/)
- [Documentation](https://techdocs.broadcom.com/us/en/symantec-security-software/endpoint-security-and-management/endpoint-security/sescloud/APIs/accessing-the-api-reference-v125094769-d4155e11.html)
- [Postman Collection](collections/symantec-sepm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/symantec-sepm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Symantec Endpoint Detection and Response API

The Symantec EDR REST API enables programmatic access to endpoint detection and response capabilities including incident management, threat hunting, forensics, and entity queries. Uses OAuth 2.0 with client credentials grant type.

- **Human URL:** [https://apidocs.symantec.com/home/SymantecEDR_4.2](https://apidocs.symantec.com/home/SymantecEDR_4.2)

#### Tags

- EDR
- Endpoint Security
- Forensics
- Incidents
- Threat Hunting

#### Properties

- [Documentation](https://apidocs.symantec.com/home/SymantecEDR_4.2)
- [Postman Collection](collections/symantec-sepm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/symantec-sepm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Symantec Data Loss Prevention API

The Symantec DLP REST API enables integration with the DLP Enforce platform for incident management, policy management, and data discovery. Supports retrieving incidents, updating remediation status, and managing DLP policies.

- **Human URL:** [https://apidocs.symantec.com/home/DLP15.7](https://apidocs.symantec.com/home/DLP15.7)

#### Tags

- Compliance
- DLP
- Data Loss Prevention
- Incidents
- Policy Management

#### Properties

- [Documentation](https://apidocs.symantec.com/home/DLP15.7)
- [Postman Collection](collections/symantec-sepm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/symantec-sepm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/symantec)
- [Website](https://www.broadcom.com/products/cybersecurity/endpoint)
- [A P I Documentation](https://apidocs.securitycloud.symantec.com/)
- [A P I Documentation](https://apidocs.symantec.com/)
- [Documentation](https://techdocs.broadcom.com/us/en/symantec-security-software)
- [Support](https://support.broadcom.com)
- [Community](https://community.broadcom.com/symantecenterprise)
- [Git Hub](https://github.com/Symantec)
- [Login](https://sep.securitycloud.symantec.com)
- [Terms of Service](https://www.broadcom.com/company/legal/terms-of-use)
- [Privacy Policy](https://www.broadcom.com/company/legal/privacy)
- [Status Page](https://status.broadcom.com/services/symantec-endpoint-security-enterprise/)
- [Blog](https://www.broadcom.com/blog/category/cybersecurity)
- [Tech Docs](https://techdocs.broadcom.com)
- [L L Ms Txt](https://apidocs.securitycloud.symantec.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
