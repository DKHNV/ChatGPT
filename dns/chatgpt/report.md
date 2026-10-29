# Chatgpt DNS Maintenance Report

Generated: `2026-10-29T13:33:19Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 320 |
| Pending | 2 |
| Suspect | 0 |
| Quarantine | 6 |
| Excluded | 0 |
| Expired | 18 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 314 |
| Unknown | 1 |
| Suspect | 1 |
| Dead | 4 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **320**
Average stability: **97.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 10 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 58 | TLS_CERT_ERROR | 150.171.109.178, 150.171.110.194, 150.171.110.210 | 0.0 | 52 |
| `codex-portals.gateway.unified-41.api.openai.com` | suspect | `2026-10-23T01:48:02Z` | 23 | TIMEOUT | 52.248.65.112 | 54.0 | 50 |
| `codex-portals.gateway.unified-42.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 3 | TIMEOUT | 13.84.242.214 | 94.0 | 50 |
| `codex-portals.gateway.unified-43.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 2 | TIMEOUT | 13.65.189.203 | 96.0 | 50 |
| `codex-portals.gateway.unified-73.api.openai.com` | unknown | `2026-10-29T06:17:46Z` | 2 | TIMEOUT | 172.204.24.16 | 0.0 | 2 |
| `codex-portals.gateway.unified-74.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 3 | TIMEOUT | 4.197.236.184 | 93.9 | 49 |
| `codex-portals.gateway.unified-75.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 2 | TIMEOUT | 48.218.32.133 | 95.9 | 49 |
| `codex-portals.gateway.unified-92.api.openai.com` | alive | `2026-10-28T22:46:28Z` | 3 | TIMEOUT | 4.201.225.205 | 93.9 | 49 |
| `codex-portals.gateway.unified-93.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 2 | TIMEOUT | 4.201.180.103 | 95.9 | 49 |
| `codex-portals.gateway.unified-95.api.openai.com` | alive | `2026-10-29T06:17:46Z` | 2 | TIMEOUT | 4.197.163.90 | 95.9 | 49 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 252 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 52 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 259 | TLS_ERROR | 13.65.2.22 | 0.0 | 52 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 163 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 52 |

## Discovery

Discovery state updated: `2026-10-29T13:33:19Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
