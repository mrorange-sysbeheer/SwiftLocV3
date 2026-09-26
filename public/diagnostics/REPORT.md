# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-26T22:29:06Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 8418 |
| Carried forward | 2786 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 30259 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.6 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-09-26T22:19:14Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 6160 |
| blocklist_de_ssh | 5068 |
| ci_army_list | 15000 |
| cisa_kev | 1726 |
| dshield_block | 20 |
| et_compromised | 669 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 4838 |
| ipsum_level5 | 4856 |
| malwarebazaar_recent | 1328 |
| nist_nvd_recent | 2200 |
| openphish_feed | 300 |
| spamhaus_drop | 1711 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 0 |
| tor_exit_nodes | 1376 |
| urlhaus_recent_urls | 537 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 4661 |
| sha256 | 2819 |
| ipv4_cidr | 1710 |
| url | 539 |
| sha1 | 228 |
| ipv4 | 23 |
| md5 | 20 |

## Issues

- ⚠️ **threatfox_export_json**: Expecting value: line 1 column 1 (char 0)
- ⚠️ **threatfox_export_json** returned zero indicators
