# Chatgpt DNS Maintenance Report

Generated: `2026-10-30T06:17:53Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 320 |
| Pending | 1 |
| Suspect | 1 |
| Quarantine | 6 |
| Excluded | 0 |
| Expired | 18 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 314 |
| Unknown | 1 |
| Suspect | 0 |
| Dead | 5 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **320**
Average stability: **97.8%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 20 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 60 | TLS_CERT_ERROR | 150.171.109.183, 150.171.110.194, 150.171.110.210 | 0.0 | 51 |
| `codex-portals.gateway.unified-11.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 1 | TIMEOUT | 172.183.35.77 | 98.0 | 51 |
| `codex-portals.gateway.unified-119.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 1 | TIMEOUT | 51.57.76.34 | 98.0 | 51 |
| `codex-portals.gateway.unified-156.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 2 | TIMEOUT | 20.211.198.50 | 96.1 | 51 |
| `codex-portals.gateway.unified-158.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 2 | TIMEOUT | 85.211.195.189 | 96.1 | 51 |
| `codex-portals.gateway.unified-160.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 1 | TIMEOUT | 20.206.107.238 | 98.0 | 51 |
| `codex-portals.gateway.unified-24.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 1 | TIMEOUT | 74.248.138.237 | 98.0 | 51 |
| `codex-portals.gateway.unified-41.api.openai.com` | dead | `2026-10-23T01:48:02Z` | 25 | TIMEOUT | 52.248.65.112 | 51.0 | 51 |
| `codex-portals.gateway.unified-42.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 5 | TIMEOUT | 13.84.242.214 | 90.2 | 51 |
| `codex-portals.gateway.unified-43.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 4 | TIMEOUT | 13.65.189.203 | 92.2 | 51 |
| `codex-portals.gateway.unified-73.api.openai.com` | unknown | `2026-10-29T06:17:46Z` | 4 | TIMEOUT | 172.204.24.16 | 0.0 | 4 |
| `codex-portals.gateway.unified-74.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 5 | TIMEOUT | 4.197.236.184 | 90.2 | 51 |
| `codex-portals.gateway.unified-75.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 4 | TIMEOUT | 48.218.32.133 | 92.2 | 51 |
| `codex-portals.gateway.unified-80.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 2 | TIMEOUT | 20.68.52.70 | 96.1 | 51 |
| `codex-portals.gateway.unified-84.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 1 | TIMEOUT | 4.201.114.119 | 98.0 | 51 |
| `codex-portals.gateway.unified-92.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 5 | TIMEOUT | 4.201.225.205 | 90.2 | 51 |
| `codex-portals.gateway.unified-93.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 4 | TIMEOUT | 4.201.180.103 | 92.2 | 51 |
| `codex-portals.gateway.unified-94.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 2 | TIMEOUT | 4.194.136.111 | 96.1 | 51 |
| `codex-portals.gateway.unified-95.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 4 | TIMEOUT | 4.197.163.90 | 92.2 | 51 |
| `codex-portals.gateway.unified-96.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 1 | TIMEOUT | 4.190.201.17 | 98.0 | 51 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 254 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 51 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 261 | TLS_ERROR | 13.65.2.22 | 0.0 | 51 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 165 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 51 |

## Discovery

Discovery state updated: `2026-10-30T06:17:53Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
