# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-01T04:52:23Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 4354 |
| Carried forward | 2477 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 27945 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-01T04:47:53Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 1514 |
| blocklist_de_ssh | 4914 |
| ci_army_list | 15000 |
| cisa_kev | 1730 |
| dshield_block | 20 |
| et_compromised | 633 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 0 |
| ipsum_level5 | 4072 |
| malwarebazaar_recent | 1258 |
| nist_nvd_recent | 4583 |
| openphish_feed | 300 |
| spamhaus_drop | 1693 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 1943 |
| tor_exit_nodes | 1407 |
| urlhaus_recent_urls | 653 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3337 |
| sha256 | 3170 |
| ipv4_cidr | 1362 |
| url | 889 |
| domain | 639 |
| ipv4 | 371 |
| sha1 | 182 |
| md5 | 50 |

## Issues

- ⚠️ **greensnow_blocklist**: 503 Server Error: Service Unavailable for url: https://blocklist.greensnow.co/greensnow.txt
- ⚠️ **greensnow_blocklist** returned zero indicators
