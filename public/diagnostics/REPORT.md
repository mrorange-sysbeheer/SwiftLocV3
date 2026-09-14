# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-14T03:57:23Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 4785 |
| Carried forward | 3935 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 25534 |
| Stored | 10000 |
| Score (min / avg / max) | 79 / 80.6 / 96 |
| High-confidence indicators | 9939 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-14T03:47:32Z |

## Per-source counts

| Source | Indicators |
| --- | ---: |
| binarydefense_banlist | 3643 |
| blocklist_de_ssh | 0 |
| ci_army_list | 15000 |
| cisa_kev | 1709 |
| dshield_block | 20 |
| et_compromised | 610 |
| feodo_ipblocklist | 5 |
| greensnow_blocklist | 4769 |
| ipsum_level5 | 4238 |
| malwarebazaar_recent | 406 |
| nist_nvd_recent | 595 |
| openphish_feed | 300 |
| spamhaus_drop | 1725 |
| sslbl_ja3 | 97 |
| threatfox_export_json | 1581 |
| tor_exit_nodes | 1323 |
| urlhaus_recent_urls | 363 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3437 |
| cve | 2801 |
| ipv4_cidr | 1724 |
| url | 523 |
| domain | 488 |
| sha1 | 418 |
| ipv4 | 302 |
| md5 | 210 |
| ja3 | 97 |

## Issues

- ⚠️ **blocklist_de_ssh** returned zero indicators
