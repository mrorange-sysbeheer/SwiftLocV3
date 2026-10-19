# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-19T23:25:47Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-19T23:25:47Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 6913 |
| Sources reporting | 17 |
| Indicator types | 9 |
| Multi-group overlaps | 382 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-score indicators (≥80) | 10000 |
| 2+ reporting groups | 382 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-19T23:15:48Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]69` | score 96, 5 reporting groups |
| ipv4: `130[.]12[.]180[.]32` | score 96, 4 reporting groups |
| ipv4: `114[.]111[.]53[.]214` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]162[.]74` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]227[.]8` | score 96, 3 reporting groups |
| ipv4: `194[.]238[.]29[.]124` | score 96, 3 reporting groups |
| ipv4: `31[.]59[.]220[.]26` | score 96, 3 reporting groups |
| ipv4: `45[.]198[.]224[.]184` | score 96, 3 reporting groups |
| ipv4: `45[.]78[.]201[.]248` | score 96, 3 reporting groups |
| ipv4: `85[.]215[.]45[.]36` | score 96, 3 reporting groups |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| ipsum_level5 | 5306 |
| blocklist_de_ssh | 5288 |
| greensnow_blocklist | 5131 |
| nist_nvd_recent | 2600 |
| threatfox_export_json | 2576 |
| cisa_kev | 1748 |
| spamhaus_drop | 1693 |
| tor_exit_nodes | 1208 |
| malwarebazaar_recent | 1172 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3042 |
| cve | 2980 |
| ipv4_cidr | 1692 |
| url | 1242 |
| domain | 556 |
| ipv4 | 231 |
| md5 | 127 |
| sha1 | 125 |
| ja3 | 5 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 3446 |
| cve | 2980 |
| malware | 2360 |
| exploited-in-the-wild | 1748 |
| drop | 1692 |
| spamhaus | 1692 |
| nvd | 1587 |
| Mirai | 1157 |
| elf | 1046 |
| ClickFix | 656 |

## Multi-group reporting overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 130[.]12[.]180[.]32 | blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 31[.]59[.]220[.]26 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]198[.]224[.]184 | blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]78[.]201[.]248 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 91[.]92[.]43[.]221 | blocklist_de_ssh, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 194[.]238[.]29[.]124 | blocklist_de_ssh, ci_army_list, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
