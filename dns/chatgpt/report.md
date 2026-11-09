# Chatgpt DNS Maintenance Report

Generated: `2026-11-09T07:03:10Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 325 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 7 |
| Excluded | 0 |
| Expired | 19 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 292 |
| Unknown | 2 |
| Suspect | 0 |
| Dead | 31 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **325**
Average stability: **92.0%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 30 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 85 | TLS_CERT_ERROR | 150.171.109.148, 150.171.109.150, 150.171.109.154 | 0.0 | 37 |
| `codex-portals.gateway.unified-101.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 24 | TIMEOUT | 4.201.200.182 | 17.2 | 29 |
| `codex-portals.gateway.unified-11.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 26 | TIMEOUT | 172.183.35.77 | 29.7 | 37 |
| `codex-portals.gateway.unified-119.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 26 | TIMEOUT | 51.57.76.34 | 29.7 | 37 |
| `codex-portals.gateway.unified-12.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 24 | TIMEOUT | 172.214.151.156 | 35.1 | 37 |
| `codex-portals.gateway.unified-120.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 24 | TIMEOUT | 4.242.230.113 | 35.1 | 37 |
| `codex-portals.gateway.unified-134.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 24 | TIMEOUT | 74.248.133.45 | 35.1 | 37 |
| `codex-portals.gateway.unified-143.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 24 | TIMEOUT | 74.248.123.18 | 35.1 | 37 |
| `codex-portals.gateway.unified-156.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 27 | TIMEOUT | 20.211.198.50 | 27.0 | 37 |
| `codex-portals.gateway.unified-158.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 27 | TIMEOUT | 85.211.195.189 | 27.0 | 37 |
| `codex-portals.gateway.unified-160.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 26 | TIMEOUT | 20.206.107.238 | 29.7 | 37 |
| `codex-portals.gateway.unified-166.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 24 | TIMEOUT | 52.234.28.116 | 35.1 | 37 |
| `codex-portals.gateway.unified-219.api.openai.com` | unknown | `2026-11-08T18:01:35Z` | 3 | TIMEOUT | 134.138.50.72 | 0.0 | 3 |
| `codex-portals.gateway.unified-24.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 26 | TIMEOUT | 74.248.138.237 | 29.7 | 37 |
| `codex-portals.gateway.unified-249.api.openai.com` | unknown | `2026-11-08T18:01:35Z` | 3 | TIMEOUT | 172.190.64.37 | 0.0 | 3 |
| `codex-portals.gateway.unified-26.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 24 | TIMEOUT | 72.146.36.89 | 35.1 | 37 |
| `codex-portals.gateway.unified-41.api.openai.com` | dead | `2026-10-23T01:48:02Z` | 50 | TIMEOUT | 52.248.65.112 | 0.0 | 37 |
| `codex-portals.gateway.unified-42.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 30 | TIMEOUT | 13.84.242.214 | 18.9 | 37 |
| `codex-portals.gateway.unified-43.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 29 | TIMEOUT | 13.65.189.203 | 21.6 | 37 |
| `codex-portals.gateway.unified-73.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 29 | TIMEOUT | 172.204.24.16 | 0.0 | 29 |
| `codex-portals.gateway.unified-74.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 30 | TIMEOUT | 4.197.236.184 | 18.9 | 37 |
| `codex-portals.gateway.unified-75.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 29 | TIMEOUT | 48.218.32.133 | 21.6 | 37 |
| `codex-portals.gateway.unified-80.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 27 | TIMEOUT | 20.68.52.70 | 27.0 | 37 |
| `codex-portals.gateway.unified-84.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 26 | TIMEOUT | 4.201.114.119 | 29.7 | 37 |
| `codex-portals.gateway.unified-87.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 24 | TIMEOUT | 4.190.157.198 | 35.1 | 37 |
| `codex-portals.gateway.unified-92.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 30 | TIMEOUT | 4.201.225.205 | 18.9 | 37 |
| `codex-portals.gateway.unified-93.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 29 | TIMEOUT | 4.201.180.103 | 21.6 | 37 |
| `codex-portals.gateway.unified-94.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 27 | TIMEOUT | 4.194.136.111 | 27.0 | 37 |
| `codex-portals.gateway.unified-95.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 29 | TIMEOUT | 4.197.163.90 | 21.6 | 37 |
| `codex-portals.gateway.unified-96.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 26 | TIMEOUT | 4.190.201.17 | 29.7 | 37 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 279 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 37 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 286 | TLS_ERROR | 13.65.2.22 | 0.0 | 37 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 190 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 37 |

## Discovery

Discovery state updated: `2026-11-09T07:03:10Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
