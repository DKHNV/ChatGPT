# Chatgpt DNS Maintenance Report

Generated: `2026-08-21T23:50:48Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 160 |
| Pending | 15 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 159 |
| Unknown | 1 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **160**
Average stability: **99.4%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | unknown | `2026-08-21T17:58:03Z` | 2 | TLS_ERROR | 13.65.2.22 | 0.0 | 2 |

## Discovery

Discovery state updated: `2026-08-21T23:50:48Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
