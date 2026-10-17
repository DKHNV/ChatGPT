# Chatgpt DNS Maintenance Report

Generated: `2026-10-17T01:27:28Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 314 |
| Pending | 1 |
| Suspect | 1 |
| Quarantine | 7 |
| Excluded | 0 |
| Expired | 16 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 310 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 4 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **314**
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
| `cdn.staging.openai.com` | alive | `2026-10-14T02:05:56Z` | 13 | TLS_CERT_ERROR | 150.171.109.148, 150.171.109.152, 150.171.109.153 | 72.9 | 48 |
| `codex-portals.api.openai.com` | dead | `2026-09-22T01:45:05Z` | 90 | NETWORK_ERROR | 172.65.163.70 | 0.0 | 48 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 207 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 48 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 214 | TLS_ERROR | 13.65.2.22 | 0.0 | 48 |
| `tore-argo-mcp.oaistatsig.com` | dead | `2026-09-15T01:47:48Z` | 118 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 48 |

## Discovery

Discovery state updated: `2026-10-17T01:27:28Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
