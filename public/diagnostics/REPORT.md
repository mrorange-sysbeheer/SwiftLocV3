# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-16T09:12:46Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 4640 |
| Carried forward | 833 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 29134 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.6 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-16T09:05:05Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 4148 |
| blocklist_de_ssh | 4717 |
| ci_army_list | 15000 |
| cisa_kev | 1710 |
| dshield_block | 20 |
| et_compromised | 588 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 0 |
| ipsum_level5 | 4117 |
| malwarebazaar_recent | 1356 |
| nist_nvd_recent | 3634 |
| openphish_feed | 300 |
| spamhaus_drop | 1725 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 3667 |
| tor_exit_nodes | 1345 |
| urlhaus_recent_urls | 512 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3573 |
| sha256 | 2442 |
| ipv4_cidr | 1613 |
| domain | 1446 |
| url | 528 |
| sha1 | 220 |
| ipv4 | 166 |
| md5 | 12 |

## Issues

- ⚠️ **greensnow_blocklist**: 503 Server Error: Service Unavailable for url: https://blocklist.greensnow.co/greensnow.txt
- ⚠️ **greensnow_blocklist** returned zero indicators
