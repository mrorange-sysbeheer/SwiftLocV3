# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-10T16:02:51Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 3963 |
| Carried forward | 2775 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 31516 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.4 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-10T16:01:20Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 2650 |
| blocklist_de_ssh | 5349 |
| ci_army_list | 15000 |
| cisa_kev | 1703 |
| dshield_block | 20 |
| et_compromised | 570 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 0 |
| ipsum_level5 | 3889 |
| malwarebazaar_recent | 1006 |
| nist_nvd_recent | 3600 |
| openphish_feed | 300 |
| spamhaus_drop | 1711 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 5014 |
| tor_exit_nodes | 1335 |
| urlhaus_recent_urls | 455 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 4309 |
| cve | 2444 |
| ipv4_cidr | 1222 |
| domain | 883 |
| url | 617 |
| ipv4 | 247 |
| sha1 | 243 |
| md5 | 35 |

## Issues

- ⚠️ **greensnow_blocklist**: 503 Server Error: Service Unavailable for url: https://blocklist.greensnow.co/greensnow.txt
- ⚠️ **greensnow_blocklist** returned zero indicators
