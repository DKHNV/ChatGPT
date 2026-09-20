# Chatgpt DNS Maintenance Report

Generated: `2026-09-20T19:40:32Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 202 |
| Pending | 0 |
| Suspect | 2 |
| Quarantine | 20 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 199 |
| Unknown | 0 |
| Suspect | 1 |
| Dead | 2 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **202**
Average stability: **98.5%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| NETWORK_ERROR | 2 |
| TIMEOUT | 1 |
| TLS_CERT_ERROR | 1 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `account.supply.openai.com` | alive | `2026-09-20T19:40:32Z` | 1 | NETWORK_ERROR | 23.227.38.74 | 98.2 | 55 |
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 113 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 55 |
| `latest.api.oaistatsig.com` | alive | `2026-09-20T19:40:32Z` | 1 | NETWORK_ERROR | 104.18.42.153, 172.64.145.103 | 98.2 | 55 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 120 | TLS_ERROR | 13.65.2.22 | 0.0 | 55 |
| `tore-argo-mcp.oaistatsig.com` | suspect | `2026-09-15T01:47:48Z` | 24 | TLS_CERT_ERROR | 107.178.243.93 | 0.0 | 24 |

## Discovery

Discovery state updated: `2026-09-20T19:40:32Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
