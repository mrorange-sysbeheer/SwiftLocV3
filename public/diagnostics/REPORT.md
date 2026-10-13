# SwiftIOC Run Report

## Overview

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-13T01:53:20Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 8500 |
| Carried forward | 2202 |
| Expired (score < 20) | 0 |
| Aged out (> 30d) | 0 |
| Pruned over cap (10000) | 29617 |
| Stored | 10000 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-confidence indicators | 10000 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-13T01:49:21Z |

## Per-source coverage

Collected means records returned in the configured window, not a guarantee of complete upstream coverage.

| Source | Indicators | State |
| --- | ---: | --- |
| binarydefense_banlist | 3918 | collected |
| blocklist_de_ssh | 4306 | collected |
| ci_army_list | 15000 | collected |
| cisa_kev | 1739 | collected |
| dshield_block | 20 | collected |
| et_compromised | 529 | collected |
| feodo_ipblocklist | 5 | collected |
| greensnow_blocklist | 5472 | collected |
| ipsum_level5 | 5079 | collected |
| malwarebazaar_recent | 1016 | collected |
| nist_nvd_recent | 2400 | collected |
| openphish_feed | 300 | collected |
| spamhaus_drop | 1677 | collected |
| sslbl_ja3 | 97 | collected |
| threatfox_export_json | 2038 | collected |
| tor_exit_nodes | 1208 | collected |
| urlhaus_recent_urls | 1111 | collected |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3585 |
| sha256 | 2008 |
| url | 1706 |
| ipv4_cidr | 1676 |
| ipv4 | 321 |
| domain | 271 |
| md5 | 217 |
| sha1 | 216 |
