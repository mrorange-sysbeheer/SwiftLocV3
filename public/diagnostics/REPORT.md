# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-03T13:08:24Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 2115 |
| Carried forward | 2584 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 24582 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-03T13:08:12Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 1073 |
| blocklist_de_ssh | 0 |
| ci_army_list | 15000 |
| cisa_kev | 1733 |
| dshield_block | 20 |
| et_compromised | 621 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 0 |
| ipsum_level5 | 3528 |
| malwarebazaar_recent | 984 |
| nist_nvd_recent | 2188 |
| openphish_feed | 300 |
| spamhaus_drop | 1693 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 4810 |
| tor_exit_nodes | 1388 |
| urlhaus_recent_urls | 673 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3259 |
| cve | 2593 |
| domain | 1998 |
| url | 973 |
| ipv4_cidr | 778 |
| ipv4 | 193 |
| sha1 | 149 |
| md5 | 57 |

## Issues

- ⚠️ **greensnow_blocklist**: 503 Server Error: Service Unavailable for url: https://blocklist.greensnow.co/greensnow.txt
- ⚠️ **blocklist_de_ssh** returned zero indicators
- ⚠️ **greensnow_blocklist** returned zero indicators
