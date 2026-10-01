# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-01T20:52:57Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 3794 |
| Carried forward | 3715 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 26629 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-01T20:52:17Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 1514 |
| blocklist_de_ssh | 3928 |
| ci_army_list | 15000 |
| cisa_kev | 1731 |
| dshield_block | 20 |
| et_compromised | 633 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 0 |
| ipsum_level5 | 4072 |
| malwarebazaar_recent | 1394 |
| nist_nvd_recent | 2200 |
| openphish_feed | 300 |
| spamhaus_drop | 1693 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 2000 |
| tor_exit_nodes | 1376 |
| urlhaus_recent_urls | 745 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3154 |
| sha256 | 3127 |
| ipv4_cidr | 1612 |
| url | 1052 |
| domain | 472 |
| ipv4 | 380 |
| sha1 | 167 |
| md5 | 36 |

## Issues

- ⚠️ **greensnow_blocklist**: 503 Server Error: Service Unavailable for url: https://blocklist.greensnow.co/greensnow.txt
- ⚠️ **greensnow_blocklist** returned zero indicators
