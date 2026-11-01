# Chatgpt DNS Maintenance Report

Generated: `2026-11-01T22:15:57Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 320 |
| Pending | 1 |
| Suspect | 2 |
| Quarantine | 6 |
| Excluded | 0 |
| Expired | 17 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 307 |
| Unknown | 0 |
| Suspect | 8 |
| Dead | 5 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **320**
Average stability: **96.4%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 29 |
| TLS_CERT_ERROR | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 68 | TLS_CERT_ERROR | 150.171.109.227, 150.171.109.230, 150.171.110.3 | 0.0 | 48 |
| `codex-portals.gateway.unified-101.api.openai.com` | alive | `2026-10-30T22:35:24Z` | 7 | TIMEOUT | 4.201.200.182 | 41.7 | 12 |
| `codex-portals.gateway.unified-11.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 9 | TIMEOUT | 172.183.35.77 | 81.2 | 48 |
| `codex-portals.gateway.unified-119.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 9 | TIMEOUT | 51.57.76.34 | 81.2 | 48 |
| `codex-portals.gateway.unified-12.api.openai.com` | alive | `2026-10-30T22:35:24Z` | 7 | TIMEOUT | 172.214.151.156 | 85.4 | 48 |
| `codex-portals.gateway.unified-120.api.openai.com` | alive | `2026-10-30T22:35:24Z` | 7 | TIMEOUT | 4.242.230.113 | 85.4 | 48 |
| `codex-portals.gateway.unified-134.api.openai.com` | alive | `2026-10-30T22:35:24Z` | 7 | TIMEOUT | 74.248.133.45 | 85.4 | 48 |
| `codex-portals.gateway.unified-143.api.openai.com` | alive | `2026-10-30T22:35:24Z` | 7 | TIMEOUT | 74.248.123.18 | 85.4 | 48 |
| `codex-portals.gateway.unified-156.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 10 | TIMEOUT | 20.211.198.50 | 79.2 | 48 |
| `codex-portals.gateway.unified-158.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 10 | TIMEOUT | 85.211.195.189 | 79.2 | 48 |
| `codex-portals.gateway.unified-160.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 9 | TIMEOUT | 20.206.107.238 | 81.2 | 48 |
| `codex-portals.gateway.unified-166.api.openai.com` | alive | `2026-10-30T22:35:24Z` | 7 | TIMEOUT | 52.234.28.116 | 85.4 | 48 |
| `codex-portals.gateway.unified-24.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 9 | TIMEOUT | 74.248.138.237 | 81.2 | 48 |
| `codex-portals.gateway.unified-26.api.openai.com` | alive | `2026-10-30T22:35:24Z` | 7 | TIMEOUT | 72.146.36.89 | 85.4 | 48 |
| `codex-portals.gateway.unified-41.api.openai.com` | dead | `2026-10-23T01:48:02Z` | 33 | TIMEOUT | 52.248.65.112 | 31.2 | 48 |
| `codex-portals.gateway.unified-42.api.openai.com` | suspect | `2026-10-28T22:46:28Z` | 13 | TIMEOUT | 13.84.242.214 | 72.9 | 48 |
| `codex-portals.gateway.unified-43.api.openai.com` | suspect | `2026-10-29T06:17:46Z` | 12 | TIMEOUT | 13.65.189.203 | 75.0 | 48 |
| `codex-portals.gateway.unified-73.api.openai.com` | suspect | `2026-10-29T06:17:46Z` | 12 | TIMEOUT | 172.204.24.16 | 0.0 | 12 |
| `codex-portals.gateway.unified-74.api.openai.com` | suspect | `2026-10-28T22:46:28Z` | 13 | TIMEOUT | 4.197.236.184 | 72.9 | 48 |
| `codex-portals.gateway.unified-75.api.openai.com` | suspect | `2026-10-29T06:17:46Z` | 12 | TIMEOUT | 48.218.32.133 | 75.0 | 48 |
| `codex-portals.gateway.unified-80.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 10 | TIMEOUT | 20.68.52.70 | 79.2 | 48 |
| `codex-portals.gateway.unified-84.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 9 | TIMEOUT | 4.201.114.119 | 81.2 | 48 |
| `codex-portals.gateway.unified-87.api.openai.com` | alive | `2026-10-30T22:35:24Z` | 7 | TIMEOUT | 4.190.157.198 | 85.4 | 48 |
| `codex-portals.gateway.unified-92.api.openai.com` | suspect | `2026-10-28T22:46:28Z` | 13 | TIMEOUT | 4.201.225.205 | 72.9 | 48 |
| `codex-portals.gateway.unified-93.api.openai.com` | suspect | `2026-10-29T06:17:46Z` | 12 | TIMEOUT | 4.201.180.103 | 75.0 | 48 |
| `codex-portals.gateway.unified-94.api.openai.com` | alive | `2026-10-29T22:55:07Z` | 10 | TIMEOUT | 4.194.136.111 | 79.2 | 48 |
| `codex-portals.gateway.unified-95.api.openai.com` | suspect | `2026-10-29T06:17:46Z` | 12 | TIMEOUT | 4.197.163.90 | 75.0 | 48 |
| `codex-portals.gateway.unified-96.api.openai.com` | alive | `2026-10-30T06:17:53Z` | 9 | TIMEOUT | 4.190.201.17 | 81.2 | 48 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 262 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 48 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 269 | TIMEOUT | 13.65.2.22 | 0.0 | 48 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 173 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 48 |

## Discovery

Discovery state updated: `2026-11-01T22:15:57Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
