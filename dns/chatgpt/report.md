# Chatgpt DNS Maintenance Report

Generated: `2026-10-30T13:23:38Z`

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
Average stability: **97.7%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 20 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 61 | TLS_CERT_ERROR | 150.171.109.183, 150.171.110.194, 150.171.110.9 | 0.0 | 51 |
| `codex-portals.gateway.unified-11.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 2 | TIMEOUT | 172.183.35.77 | 96.1 | 51 |
| `codex-portals.gateway.unified-119.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 2 | TIMEOUT | 51.57.76.34 | 96.1 | 51 |
| `codex-portals.gateway.unified-156.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 3 | TIMEOUT | 20.211.198.50 | 94.1 | 51 |
| `codex-portals.gateway.unified-158.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 3 | TIMEOUT | 85.211.195.189 | 94.1 | 51 |
| `codex-portals.gateway.unified-160.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 2 | TIMEOUT | 20.206.107.238 | 96.1 | 51 |
| `codex-portals.gateway.unified-24.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 2 | TIMEOUT | 74.248.138.237 | 96.1 | 51 |
| `codex-portals.gateway.unified-41.api.openai.com` | dead | `2026-10-23T01:48:02Z` | 26 | TIMEOUT | 52.248.65.112 | 49.0 | 51 |
| `codex-portals.gateway.unified-42.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 6 | TIMEOUT | 13.84.242.214 | 88.2 | 51 |
| `codex-portals.gateway.unified-43.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 5 | TIMEOUT | 13.65.189.203 | 90.2 | 51 |
| `codex-portals.gateway.unified-73.api.openai.com` | unknown | `2026-10-29T06:17:46Z` | 5 | TIMEOUT | 172.204.24.16 | 0.0 | 5 |
| `codex-portals.gateway.unified-74.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 6 | TIMEOUT | 4.197.236.184 | 88.2 | 51 |
| `codex-portals.gateway.unified-75.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 5 | TIMEOUT | 48.218.32.133 | 90.2 | 51 |
| `codex-portals.gateway.unified-80.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 3 | TIMEOUT | 20.68.52.70 | 94.1 | 51 |
| `codex-portals.gateway.unified-84.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 2 | TIMEOUT | 4.201.114.119 | 96.1 | 51 |
| `codex-portals.gateway.unified-92.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 6 | TIMEOUT | 4.201.225.205 | 88.2 | 51 |
| `codex-portals.gateway.unified-93.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 5 | TIMEOUT | 4.201.180.103 | 90.2 | 51 |
| `codex-portals.gateway.unified-94.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 3 | TIMEOUT | 4.194.136.111 | 94.1 | 51 |
| `codex-portals.gateway.unified-95.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 5 | TIMEOUT | 4.197.163.90 | 90.2 | 51 |
| `codex-portals.gateway.unified-96.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 2 | TIMEOUT | 4.190.201.17 | 96.1 | 51 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 255 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 51 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 262 | TLS_ERROR | 13.65.2.22 | 0.0 | 51 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 166 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 51 |

## Discovery

Discovery state updated: `2026-10-30T13:23:38Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
