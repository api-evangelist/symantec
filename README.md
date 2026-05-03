# Symantec

This repository profiles the Symantec (Broadcom) enterprise cybersecurity APIs, covering endpoint protection management, threat detection, data loss prevention, and cloud-delivered security services.

## APIs

| API | Description | Base URL |
|-----|-------------|----------|
| Symantec SEPM API | Symantec Endpoint Protection Manager REST API for managing endpoints, groups, policies, and administrators | https://{sepm-host}:8446/sepm/api/v1 |
| Symantec SES API | Symantec Endpoint Security cloud platform API for cloud-delivered endpoint protection | https://api.sep.securitycloud.symantec.com/v1 |
| Symantec EDR API | Endpoint Detection and Response API for threat hunting, incident investigation, and behavioral analytics | https://api.edr.securitycloud.symantec.com/v1 |
| Symantec DLP API | Data Loss Prevention API for policy management, incident tracking, and endpoint monitoring | https://protect.symantec.com/webservices |

## Authentication

The SEPM API uses Bearer token authentication. Obtain a token via `POST /identity/authenticate` with username and password credentials, then include `Authorization: Bearer {token}` in all subsequent API calls.

Cloud APIs (SES, EDR, DLP) use OAuth 2.0 via the Integrated Cyber Defense Manager (ICDm) portal.

## OpenAPI Specifications

- [Symantec SEPM API](openapi/symantec-sepm-api-openapi.yml) — Endpoint management, computer inventory, group management, policy assignment, administrator management

## Capabilities

Naftiko capability files for AI agent integration:

| Capability | Description | REST Port | MCP Port |
|------------|-------------|-----------|----------|
| [endpoint-security](capabilities/endpoint-security.yaml) | Unified endpoint security management workflow | 8080 | 9090 |
| [shared/symantec-sepm](capabilities/shared/symantec-sepm.yaml) | SEPM API operations consumer | 8100 | 9100 |

## Rules

Spectral linting rules: [symantec-rules.yml](rules/symantec-rules.yml)

## Schemas

- [symantec-computer-schema.json](json-schema/symantec-computer-schema.json) — Managed endpoint computer schema

## Examples

- [Authenticate to SEPM](examples/symantec-authenticate-example.json) — Obtain Bearer token
- [List Managed Computers](examples/symantec-list-computers-example.json) — List managed endpoints

## Vocabulary

Domain vocabulary: [symantec-vocabulary.yml](vocabulary/symantec-vocabulary.yml)

Key terms: SEPM, SEP Client, SES, EDR, DLP, ICDm, Behavioral Analytics, Threat Hunting, Global Intelligence Network, Bearer Token

## Properties

- [Website](https://www.broadcom.com/products/cybersecurity/endpoint)
- [Developer Portal](https://apidocs.securitycloud.symantec.com/)
- [SEPM API Documentation](https://knowledge.broadcom.com/external/article/162195/symantec-endpoint-protection-manager-re.html)
