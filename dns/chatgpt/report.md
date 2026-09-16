# Chatgpt DNS Maintenance Report

Generated: `2026-09-16T20:22:02Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 196 |
| Pending | 2 |
| Suspect | 0 |
| Quarantine | 20 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 193 |
| Unknown | 1 |
| Suspect | 0 |
| Dead | 2 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **196**
Average stability: **98.5%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 1 |
| TLS_CERT_ERROR | 1 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 97 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 55 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 104 | TLS_ERROR | 13.65.2.22 | 0.0 | 55 |
| `tore-argo-mcp.oaistatsig.com` | unknown | `2026-09-15T01:47:48Z` | 8 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 8 |

## Discovery

Discovery state updated: `2026-09-16T20:22:02Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
