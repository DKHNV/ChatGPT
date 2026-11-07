# Chatgpt DNS Maintenance Report

Generated: `2026-11-07T22:12:56Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 323 |
| Pending | 0 |
| Suspect | 1 |
| Quarantine | 8 |
| Excluded | 0 |
| Expired | 17 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 292 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 31 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **323**
Average stability: **93.4%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 28 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 81 | TLS_CERT_ERROR | 150.171.109.118, 150.171.109.72, 150.171.109.76 | 0.0 | 38 |
| `codex-portals.gateway.unified-101.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 20 | TIMEOUT | 4.201.200.182 | 20.0 | 25 |
| `codex-portals.gateway.unified-11.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 22 | TIMEOUT | 172.183.35.77 | 42.1 | 38 |
| `codex-portals.gateway.unified-119.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 22 | TIMEOUT | 51.57.76.34 | 42.1 | 38 |
| `codex-portals.gateway.unified-12.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 20 | TIMEOUT | 172.214.151.156 | 47.4 | 38 |
| `codex-portals.gateway.unified-120.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 20 | TIMEOUT | 4.242.230.113 | 47.4 | 38 |
| `codex-portals.gateway.unified-134.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 20 | TIMEOUT | 74.248.133.45 | 47.4 | 38 |
| `codex-portals.gateway.unified-143.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 20 | TIMEOUT | 74.248.123.18 | 47.4 | 38 |
| `codex-portals.gateway.unified-156.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 23 | TIMEOUT | 20.211.198.50 | 39.5 | 38 |
| `codex-portals.gateway.unified-158.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 23 | TIMEOUT | 85.211.195.189 | 39.5 | 38 |
| `codex-portals.gateway.unified-160.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 22 | TIMEOUT | 20.206.107.238 | 42.1 | 38 |
| `codex-portals.gateway.unified-166.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 20 | TIMEOUT | 52.234.28.116 | 47.4 | 38 |
| `codex-portals.gateway.unified-24.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 22 | TIMEOUT | 74.248.138.237 | 42.1 | 38 |
| `codex-portals.gateway.unified-26.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 20 | TIMEOUT | 72.146.36.89 | 47.4 | 38 |
| `codex-portals.gateway.unified-41.api.openai.com` | dead | `2026-10-23T01:48:02Z` | 46 | TIMEOUT | 52.248.65.112 | 0.0 | 38 |
| `codex-portals.gateway.unified-42.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 26 | TIMEOUT | 13.84.242.214 | 31.6 | 38 |
| `codex-portals.gateway.unified-43.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 25 | TIMEOUT | 13.65.189.203 | 34.2 | 38 |
| `codex-portals.gateway.unified-73.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 25 | TIMEOUT | 172.204.24.16 | 0.0 | 25 |
| `codex-portals.gateway.unified-74.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 26 | TIMEOUT | 4.197.236.184 | 31.6 | 38 |
| `codex-portals.gateway.unified-75.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 25 | TIMEOUT | 48.218.32.133 | 34.2 | 38 |
| `codex-portals.gateway.unified-80.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 23 | TIMEOUT | 20.68.52.70 | 39.5 | 38 |
| `codex-portals.gateway.unified-84.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 22 | TIMEOUT | 4.201.114.119 | 42.1 | 38 |
| `codex-portals.gateway.unified-87.api.openai.com` | dead | `2026-10-30T22:35:24Z` | 20 | TIMEOUT | 4.190.157.198 | 47.4 | 38 |
| `codex-portals.gateway.unified-92.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 26 | TIMEOUT | 4.201.225.205 | 31.6 | 38 |
| `codex-portals.gateway.unified-93.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 25 | TIMEOUT | 4.201.180.103 | 34.2 | 38 |
| `codex-portals.gateway.unified-94.api.openai.com` | dead | `2026-10-29T22:55:07Z` | 23 | TIMEOUT | 4.194.136.111 | 39.5 | 38 |
| `codex-portals.gateway.unified-95.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 25 | TIMEOUT | 4.197.163.90 | 34.2 | 38 |
| `codex-portals.gateway.unified-96.api.openai.com` | dead | `2026-10-30T06:17:53Z` | 22 | TIMEOUT | 4.190.201.17 | 42.1 | 38 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 275 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 38 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 282 | TLS_ERROR | 13.65.2.22 | 0.0 | 38 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 186 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 38 |

## Discovery

Discovery state updated: `2026-11-07T22:12:56Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
