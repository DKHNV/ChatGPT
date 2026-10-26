# Chatgpt DNS Maintenance Report

Generated: `2026-10-26T13:27:50Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 318 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 6 |
| Excluded | 0 |
| Expired | 19 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 312 |
| Unknown | 0 |
| Suspect | 1 |
| Dead | 5 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **318**
Average stability: **98.3%**

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
| `cdn.staging.openai.com` | dead | `2026-10-14T02:05:56Z` | 49 | TLS_CERT_ERROR | 150.171.109.227, 150.171.109.230, 150.171.110.9 | 5.8 | 52 |
| `codex-portals.api.openai.com` | dead | `2026-09-22T01:45:05Z` | 126 | NETWORK_ERROR | 172.65.163.70 | 0.0 | 52 |
| `codex-portals.gateway.unified-41.api.openai.com` | suspect | `2026-10-23T01:48:02Z` | 14 | TIMEOUT | 52.248.65.112 | 65.9 | 41 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 243 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 52 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 250 | TLS_ERROR | 13.65.2.22 | 0.0 | 52 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 154 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 52 |

## Discovery

Discovery state updated: `2026-10-26T13:27:50Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
