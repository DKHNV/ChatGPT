# Chatgpt DNS Maintenance Report

Generated: `2026-11-08T18:01:35Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 325 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 9 |
| Excluded | 0 |
| Expired | 17 |

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
Average stability: **92.4%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 30 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 83 | TLS_CERT_ERROR | 150.171.110.180, 150.171.110.3, 150.171.110.8 | 0.0 | 37 |
| `codex-portals.gateway.unified-101.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 22 | TIMEOUT | 4.201.200.182 | 18.5 | 27 |
| `codex-portals.gateway.unified-11.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 24 | TIMEOUT | 172.183.35.77 | 35.1 | 37 |
| `codex-portals.gateway.unified-119.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 24 | TIMEOUT | 51.57.76.34 | 35.1 | 37 |
| `codex-portals.gateway.unified-12.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 22 | TIMEOUT | 172.214.151.156 | 40.5 | 37 |
| `codex-portals.gateway.unified-120.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 22 | TIMEOUT | 4.242.230.113 | 40.5 | 37 |
| `codex-portals.gateway.unified-134.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 22 | TIMEOUT | 74.248.133.45 | 40.5 | 37 |
| `codex-portals.gateway.unified-143.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 22 | TIMEOUT | 74.248.123.18 | 40.5 | 37 |
| `codex-portals.gateway.unified-156.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 25 | TIMEOUT | 20.211.198.50 | 32.4 | 37 |
| `codex-portals.gateway.unified-158.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 25 | TIMEOUT | 85.211.195.189 | 32.4 | 37 |
| `codex-portals.gateway.unified-160.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 24 | TIMEOUT | 20.206.107.238 | 35.1 | 37 |
| `codex-portals.gateway.unified-166.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 22 | TIMEOUT | 52.234.28.116 | 40.5 | 37 |
| `codex-portals.gateway.unified-219.api.openai.com` | unknown | `2026-11-08T18:01:35Z` | 1 | TIMEOUT | 134.138.50.72 | 0.0 | 1 |
| `codex-portals.gateway.unified-24.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 24 | TIMEOUT | 74.248.138.237 | 35.1 | 37 |
| `codex-portals.gateway.unified-249.api.openai.com` | unknown | `2026-11-08T18:01:35Z` | 1 | TIMEOUT | 172.190.64.37 | 0.0 | 1 |
| `codex-portals.gateway.unified-26.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 22 | TIMEOUT | 72.146.36.89 | 40.5 | 37 |
| `codex-portals.gateway.unified-41.api.openai.com` | dead | `2026-10-23T01:48:02Z` | 48 | TIMEOUT | 52.248.65.112 | 0.0 | 37 |
| `codex-portals.gateway.unified-42.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 28 | TIMEOUT | 13.84.242.214 | 24.3 | 37 |
| `codex-portals.gateway.unified-43.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 27 | TIMEOUT | 13.65.189.203 | 27.0 | 37 |
| `codex-portals.gateway.unified-73.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 27 | TIMEOUT | 172.204.24.16 | 0.0 | 27 |
| `codex-portals.gateway.unified-74.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 28 | TIMEOUT | 4.197.236.184 | 24.3 | 37 |
| `codex-portals.gateway.unified-75.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 27 | TIMEOUT | 48.218.32.133 | 27.0 | 37 |
| `codex-portals.gateway.unified-80.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 25 | TIMEOUT | 20.68.52.70 | 32.4 | 37 |
| `codex-portals.gateway.unified-84.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 24 | TIMEOUT | 4.201.114.119 | 35.1 | 37 |
| `codex-portals.gateway.unified-87.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 22 | TIMEOUT | 4.190.157.198 | 40.5 | 37 |
| `codex-portals.gateway.unified-92.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 28 | TIMEOUT | 4.201.225.205 | 24.3 | 37 |
| `codex-portals.gateway.unified-93.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 27 | TIMEOUT | 4.201.180.103 | 27.0 | 37 |
| `codex-portals.gateway.unified-94.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 25 | TIMEOUT | 4.194.136.111 | 32.4 | 37 |
| `codex-portals.gateway.unified-95.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 27 | TIMEOUT | 4.197.163.90 | 27.0 | 37 |
| `codex-portals.gateway.unified-96.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 24 | TIMEOUT | 4.190.201.17 | 35.1 | 37 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 277 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 37 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 284 | TLS_ERROR | 13.65.2.22 | 0.0 | 37 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 188 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 37 |

## Discovery

Discovery state updated: `2026-11-08T18:01:35Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
