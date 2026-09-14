# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-14T17:54:40Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 6020 |
| Carried forward | 5406 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 29481 |
| Stored | 10000 |
| Score (min / avg / max) | 79 / 80.5 / 96 |
| High-confidence indicators | 9624 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-14T17:53:17Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 3643 |
| blocklist_de_ssh | 5176 |
| ci_army_list | 15000 |
| cisa_kev | 1709 |
| dshield_block | 20 |
| et_compromised | 610 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 4265 |
| ipsum_level5 | 4238 |
| malwarebazaar_recent | 481 |
| nist_nvd_recent | 1156 |
| openphish_feed | 300 |
| spamhaus_drop | 1725 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 0 |
| tor_exit_nodes | 1224 |
| urlhaus_recent_urls | 446 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3555 |
| cve | 3311 |
| ipv4_cidr | 1724 |
| url | 450 |
| domain | 376 |
| sha1 | 336 |
| md5 | 128 |
| ja3 | 97 |
| ipv4 | 23 |

## Issues

- ⚠️ **threatfox_export_json**: HTTPSConnectionPool(host='threatfox.abuse.ch', port=443): Max retries exceeded with url: /export/json/recent/ (Caused by ReadTimeoutError("HTTPSConnectionPool(host='threatfox.abuse.ch', port=443): Read timed out. (read timeout=20)"))
- ⚠️ **threatfox_export_json** returned zero indicators
