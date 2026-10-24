# Chatgpt DNS Maintenance Report

Generated: `2026-10-24T19:41:41Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 318 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 7 |
| Excluded | 0 |
| Expired | 18 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 313 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 5 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **318**
Average stability: **98.4%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| NETWORK_ERROR | 1 |
| TIMEOUT | 2 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 43 | TLS_CERT_ERROR | 150.171.109.183, 150.171.110.194, 150.171.110.210 | 17.3 | 52 |
| `codex-portals.api.openai.com` | dead | `2026-09-22T01:45:05Z` | 120 | NETWORK_ERROR | 172.65.163.70 | 0.0 | 52 |
| `codex-portals.gateway.unified-41.api.openai.com` | alive | `2026-10-23T01:48:02Z` | 8 | TIMEOUT | 52.248.65.112 | 77.1 | 35 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 237 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 52 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 244 | TLS_ERROR | 13.65.2.22 | 0.0 | 52 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 148 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 52 |

## Discovery

Discovery state updated: `2026-10-24T19:41:41Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
