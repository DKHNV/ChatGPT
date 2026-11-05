# Chatgpt DNS Maintenance Report

Generated: `2026-11-05T20:12:45Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 321 |
| Pending | 0 |
| Suspect | 2 |
| Quarantine | 7 |
| Excluded | 0 |
| Expired | 18 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 291 |
| Unknown | 0 |
| Suspect | 18 |
| Dead | 13 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **322**
Average stability: **94.7%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 28 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 76 | TLS_CERT_ERROR | 150.171.109.145, 150.171.109.147, 150.171.109.151 | 0.0 | 42 |
| `codex-portals.gateway.unified-101.api.openai.com` | suspect | `2026-10-30T22:35:24Z` | 15 | TIMEOUT | 4.201.200.182 | 25.0 | 20 |
| `codex-portals.gateway.unified-11.api.openai.com` | suspect | `2026-10-30T06:17:53Z` | 17 | TIMEOUT | 172.183.35.77 | 59.5 | 42 |
| `codex-portals.gateway.unified-119.api.openai.com` | suspect | `2026-10-30T06:17:53Z` | 17 | TIMEOUT | 51.57.76.34 | 59.5 | 42 |
| `codex-portals.gateway.unified-12.api.openai.com` | suspect | `2026-10-30T22:35:24Z` | 15 | TIMEOUT | 172.214.151.156 | 64.3 | 42 |
| `codex-portals.gateway.unified-120.api.openai.com` | suspect | `2026-10-30T22:35:24Z` | 15 | TIMEOUT | 4.242.230.113 | 64.3 | 42 |
| `codex-portals.gateway.unified-134.api.openai.com` | suspect | `2026-10-30T22:35:24Z` | 15 | TIMEOUT | 74.248.133.45 | 64.3 | 42 |
| `codex-portals.gateway.unified-143.api.openai.com` | suspect | `2026-10-30T22:35:24Z` | 15 | TIMEOUT | 74.248.123.18 | 64.3 | 42 |
| `codex-portals.gateway.unified-156.api.openai.com` | suspect | `2026-10-29T22:55:07Z` | 18 | TIMEOUT | 20.211.198.50 | 57.1 | 42 |
| `codex-portals.gateway.unified-158.api.openai.com` | suspect | `2026-10-29T22:55:07Z` | 18 | TIMEOUT | 85.211.195.189 | 57.1 | 42 |
| `codex-portals.gateway.unified-160.api.openai.com` | suspect | `2026-10-30T06:17:53Z` | 17 | TIMEOUT | 20.206.107.238 | 59.5 | 42 |
| `codex-portals.gateway.unified-166.api.openai.com` | suspect | `2026-10-30T22:35:24Z` | 15 | TIMEOUT | 52.234.28.116 | 64.3 | 42 |
| `codex-portals.gateway.unified-24.api.openai.com` | suspect | `2026-10-30T06:17:53Z` | 17 | TIMEOUT | 74.248.138.237 | 59.5 | 42 |
| `codex-portals.gateway.unified-26.api.openai.com` | suspect | `2026-10-30T22:35:24Z` | 15 | TIMEOUT | 72.146.36.89 | 64.3 | 42 |
| `codex-portals.gateway.unified-41.api.openai.com` | dead | `2026-10-23T01:48:02Z` | 41 | TIMEOUT | 52.248.65.112 | 2.4 | 42 |
| `codex-portals.gateway.unified-42.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 21 | TIMEOUT | 13.84.242.214 | 50.0 | 42 |
| `codex-portals.gateway.unified-43.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 20 | TIMEOUT | 13.65.189.203 | 52.4 | 42 |
| `codex-portals.gateway.unified-73.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 20 | TIMEOUT | 172.204.24.16 | 0.0 | 20 |
| `codex-portals.gateway.unified-74.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 21 | TIMEOUT | 4.197.236.184 | 50.0 | 42 |
| `codex-portals.gateway.unified-75.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 20 | TIMEOUT | 48.218.32.133 | 52.4 | 42 |
| `codex-portals.gateway.unified-80.api.openai.com` | suspect | `2026-10-29T22:55:07Z` | 18 | TIMEOUT | 20.68.52.70 | 57.1 | 42 |
| `codex-portals.gateway.unified-84.api.openai.com` | suspect | `2026-10-30T06:17:53Z` | 17 | TIMEOUT | 4.201.114.119 | 59.5 | 42 |
| `codex-portals.gateway.unified-87.api.openai.com` | suspect | `2026-10-30T22:35:24Z` | 15 | TIMEOUT | 4.190.157.198 | 64.3 | 42 |
| `codex-portals.gateway.unified-92.api.openai.com` | dead | `2026-10-28T22:46:28Z` | 21 | TIMEOUT | 4.201.225.205 | 50.0 | 42 |
| `codex-portals.gateway.unified-93.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 20 | TIMEOUT | 4.201.180.103 | 52.4 | 42 |
| `codex-portals.gateway.unified-94.api.openai.com` | suspect | `2026-10-29T22:55:07Z` | 18 | TIMEOUT | 4.194.136.111 | 57.1 | 42 |
| `codex-portals.gateway.unified-95.api.openai.com` | dead | `2026-10-29T06:17:46Z` | 20 | TIMEOUT | 4.197.163.90 | 52.4 | 42 |
| `codex-portals.gateway.unified-96.api.openai.com` | suspect | `2026-10-30T06:17:53Z` | 17 | TIMEOUT | 4.190.201.17 | 59.5 | 42 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 270 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 42 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 277 | TLS_ERROR | 13.65.2.22 | 0.0 | 42 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 181 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 42 |

## Discovery

Discovery state updated: `2026-11-05T20:12:45Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
