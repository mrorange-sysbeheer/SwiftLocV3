# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-14T04:05:48Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 7949 |
| Carried forward | 2226 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 30328 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-14T04:01:15Z |

## Per-source coverage

Collected means records returned in the configured window, not a guarantee of complete upstream coverage.

| Source | Indicators | State |
| --- | ---: | --- |
| binarydefense_banlist | 4182 | collected |
| blocklist_de_ssh | 4194 | collected |
| ci_army_list | 15000 | collected |
| cisa_kev | 1741 | collected |
| dshield_block | 20 | collected |
| et_compromised | 530 | collected |
| feodo_ipblocklist | 5 | collected |
| greensnow_blocklist | 5694 | collected |
| ipsum_level5 | 4558 | collected |
| malwarebazaar_recent | 1130 | collected |
| nist_nvd_recent | 1200 | collected |
| openphish_feed | 300 | collected |
| spamhaus_drop | 1682 | collected |
| sslbl_ja3 | 97 | collected |
| threatfox_export_json | 3383 | collected |
| tor_exit_nodes | 1214 | collected |
| urlhaus_recent_urls | 1121 | collected |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 2923 |
| url | 2670 |
| sha256 | 1779 |
| ipv4_cidr | 1340 |
| domain | 553 |
| ipv4 | 309 |
| md5 | 213 |
| sha1 | 213 |
