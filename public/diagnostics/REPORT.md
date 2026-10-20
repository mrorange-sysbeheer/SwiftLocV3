# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-20T16:33:36Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 7364 |
| Carried forward | 2405 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 33664 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-20T16:23:09Z |

## Per-source coverage

Collected means records returned in the configured window, not a guarantee of complete upstream coverage.

| Source | Indicators | State |
| --- | ---: | --- |
| binarydefense_banlist | 1465 | collected |
| blocklist_de_ssh | 5200 | collected |
| ci_army_list | 15000 | collected |
| cisa_kev | 1748 | collected |
| dshield_block | 20 | collected |
| et_compromised | 474 | collected |
| feodo_ipblocklist | 5 | collected |
| greensnow_blocklist | 4814 | collected |
| ipsum_level5 | 5407 | collected |
| malwarebazaar_recent | 1379 | collected |
| nist_nvd_recent | 6400 | collected |
| openphish_feed | 300 | collected |
| spamhaus_drop | 1687 | collected |
| sslbl_ja3 | 97 | collected |
| threatfox_export_json | 2658 | collected |
| tor_exit_nodes | 1208 | collected |
| urlhaus_recent_urls | 761 | collected |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 2982 |
| sha256 | 2838 |
| ipv4_cidr | 1686 |
| url | 1680 |
| domain | 225 |
| ipv4 | 225 |
| md5 | 183 |
| sha1 | 181 |
