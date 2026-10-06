# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-06T01:11:40Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 2265 |
| Carried forward | 2553 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 24932 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 81.0 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-06T01:02:12Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 1976 |
| blocklist_de_ssh | 0 |
| ci_army_list | 15000 |
| cisa_kev | 1734 |
| dshield_block | 20 |
| et_compromised | 599 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 0 |
| ipsum_level5 | 4122 |
| malwarebazaar_recent | 1053 |
| nist_nvd_recent | 1544 |
| openphish_feed | 300 |
| spamhaus_drop | 1641 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 4437 |
| tor_exit_nodes | 1360 |
| urlhaus_recent_urls | 756 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 4321 |
| cve | 2218 |
| ipv4_cidr | 1499 |
| url | 932 |
| domain | 662 |
| ipv4 | 176 |
| md5 | 108 |
| sha1 | 84 |

## Issues

- ⚠️ **greensnow_blocklist**: 503 Server Error: Service Unavailable for url: https://blocklist.greensnow.co/greensnow.txt
- ⚠️ **blocklist_de_ssh** returned zero indicators
- ⚠️ **greensnow_blocklist** returned zero indicators
