# Chatgpt DNS Maintenance Report

Generated: `2026-09-04T09:52:32Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 192 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 21 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 190 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 2 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **192**
Average stability: **99.0%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 1 |
| TLS_ERROR | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `foundry.openai.com` | dead | `2026-08-23T11:48:51Z` | 48 | TIMEOUT | 15.205.11.130, 40.38.121.218, 40.38.48.92 | 0.0 | 48 |
| `responsesapi-cert-publisher.gateway-passthrough.unified-0.api.openai.com` | dead | `2026-08-21T17:58:03Z` | 55 | TLS_ERROR | 13.65.2.22 | 0.0 | 55 |

## Discovery

Discovery state updated: `2026-09-04T09:52:32Z`

## Notes

- Public active DNS file: `ChatGPT_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
