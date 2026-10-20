# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-20T03:58:06Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 8184 |
| Carried forward | 3106 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 29910 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-20T03:47:07Z |

## Per-source coverage

Collected means records returned in the configured window, not a guarantee of complete upstream coverage.

| Source | Indicators | State |
| --- | ---: | --- |
| binarydefense_banlist | 1465 | collected |
| blocklist_de_ssh | 5282 | collected |
| ci_army_list | 15000 | collected |
| cisa_kev | 1748 | collected |
| dshield_block | 20 | collected |
| et_compromised | 474 | collected |
| feodo_ipblocklist | 5 | collected |
| greensnow_blocklist | 5283 | collected |
| ipsum_level5 | 5407 | collected |
| malwarebazaar_recent | 1256 | collected |
| nist_nvd_recent | 2600 | collected |
| openphish_feed | 300 | collected |
| spamhaus_drop | 1693 | collected |
| sslbl_ja3 | 97 | collected |
| threatfox_export_json | 2652 | collected |
| tor_exit_nodes | 1209 | collected |
| urlhaus_recent_urls | 497 | collected |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3116 |
| sha256 | 2872 |
| ipv4_cidr | 1692 |
| url | 1269 |
| domain | 558 |
| ipv4 | 241 |
| md5 | 127 |
| sha1 | 125 |
