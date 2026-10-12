# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-12T17:30:39Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 7140 |
| Carried forward | 3708 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 30960 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-12T17:17:38Z |

## Per-source coverage

Collected means records returned in the configured window, not a guarantee of complete upstream coverage.

| Source | Indicators | State |
| --- | ---: | --- |
| binarydefense_banlist | 3698 | collected |
| blocklist_de_ssh | 4718 | collected |
| ci_army_list | 15000 | collected |
| cisa_kev | 1739 | collected |
| dshield_block | 20 | collected |
| et_compromised | 600 | collected |
| feodo_ipblocklist | 5 | collected |
| greensnow_blocklist | 4757 | collected |
| ipsum_level5 | 4723 | collected |
| malwarebazaar_recent | 952 | collected |
| nist_nvd_recent | 2077 | collected |
| openphish_feed | 300 | collected |
| spamhaus_drop | 1677 | collected |
| sslbl_ja3 | 97 | collected |
| threatfox_export_json | 1737 | collected |
| tor_exit_nodes | 1204 | collected |
| urlhaus_recent_urls | 1088 | collected |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 4084 |
| sha256 | 1892 |
| ipv4_cidr | 1676 |
| url | 1466 |
| ipv4 | 305 |
| domain | 288 |
| md5 | 145 |
| sha1 | 144 |
