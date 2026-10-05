# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-05T04:40:38Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 3656 |
| Carried forward | 1353 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 25516 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.9 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-05T04:32:16Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 1677 |
| blocklist_de_ssh | 0 |
| ci_army_list | 15000 |
| cisa_kev | 1734 |
| dshield_block | 20 |
| et_compromised | 621 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 5187 |
| ipsum_level5 | 3531 |
| malwarebazaar_recent | 963 |
| nist_nvd_recent | 739 |
| openphish_feed | 300 |
| spamhaus_drop | 1692 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 3991 |
| tor_exit_nodes | 1382 |
| urlhaus_recent_urls | 880 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3795 |
| cve | 1906 |
| ipv4_cidr | 1691 |
| domain | 1281 |
| url | 1040 |
| ipv4 | 168 |
| sha1 | 70 |
| md5 | 49 |

## Issues

- ⚠️ **blocklist_de_ssh** returned zero indicators
