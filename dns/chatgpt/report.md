# Chatgpt DNS Maintenance Report

Generated: `2026-10-20T20:47:26Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 314 |
| Pending | 0 |
| Suspect | 2 |
| Quarantine | 8 |
| Excluded | 0 |
| Expired | 16 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 310 |
| Unknown | 0 |
| Suspect | 1 |
| Dead | 4 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **315**
Average stability: **98.6%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| NETWORK_ERROR | 1 |
| TIMEOUT | 1 |
| TLS_CERT_ERROR | 2 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `cdn.staging.openai.com` | suspect | `2026-10-14T02:05:56Z` | 27 | TLS_CERT_ERROR | 150.171.109.116, 150.171.109.74 | 44.9 | 49 |
| `codex-portals.api.openai.com` | dead | `2026-09-22T01:45:05Z` | 104 | NETWORK_ERROR | 172.65.163.70 | 0.0 | 49 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 221 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 49 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 228 | TLS_ERROR | 13.65.2.22 | 0.0 | 49 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 132 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 49 |

## Discovery

Discovery state updated: `2026-10-20T20:47:26Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
