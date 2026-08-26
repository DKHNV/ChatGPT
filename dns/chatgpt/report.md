# Chatgpt DNS Maintenance Report

Generated: `2026-08-26T19:24:46Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 191 |
| Pending | 0 |
| Suspect | 21 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 189 |
| Unknown | 0 |
| Suspect | 2 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **191**
Average stability: **99.0%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 1 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `foundry.openai.com` | suspect | `2026-08-23T11:48:51Z` | 14 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 14 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | suspect | `2026-08-21T17:58:03Z` | 21 | TLS_ERROR | 13.65.2.22 | 0.0 | 21 |

## Discovery

Discovery state updated: `2026-08-26T19:24:46Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
