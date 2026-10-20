# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-20T09:20:45Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 7888 |
| Carried forward | 2331 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 29732 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-20T09:13:08Z |

## Per-source coverage

Collected means records returned in the configured window, not a guarantee of complete upstream coverage.

| Source | Indicators | State |
| --- | ---: | --- |
| binarydefense_banlist | 1465 | collected |
| blocklist_de_ssh | 5287 | collected |
| ci_army_list | 15000 | collected |
| cisa_kev | 1748 | collected |
| dshield_block | 20 | collected |
| et_compromised | 474 | collected |
| feodo_ipblocklist | 5 | collected |
| greensnow_blocklist | 5412 | collected |
| ipsum_level5 | 5407 | collected |
| malwarebazaar_recent | 1249 | collected |
| nist_nvd_recent | 2200 | collected |
| openphish_feed | 300 | collected |
| spamhaus_drop | 1693 | collected |
| sslbl_ja3 | 97 | collected |
| threatfox_export_json | 2880 | collected |
| tor_exit_nodes | 1209 | collected |
| urlhaus_recent_urls | 843 | collected |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 2936 |
| cve | 2553 |
| ipv4_cidr | 1692 |
| url | 1628 |
| domain | 582 |
| ipv4 | 245 |
| md5 | 183 |
| sha1 | 181 |
