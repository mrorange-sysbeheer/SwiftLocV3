# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-18T08:41:06Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-18T08:41:06Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 6442 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-group overlaps | 385 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-score indicators (≥80) | 10000 |
| 2+ reporting groups | 385 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-18T08:31:16Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]69` | score 96, 5 reporting groups |
| ipv4: `130[.]12[.]180[.]32` | score 96, 4 reporting groups |
| ipv4: `114[.]111[.]53[.]214` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]162[.]74` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]227[.]8` | score 96, 3 reporting groups |
| ipv4: `31[.]59[.]220[.]26` | score 96, 3 reporting groups |
| ipv4: `45[.]198[.]224[.]184` | score 96, 3 reporting groups |
| ipv4: `45[.]78[.]201[.]248` | score 96, 3 reporting groups |
| ipv4: `85[.]215[.]45[.]36` | score 96, 3 reporting groups |
| ipv4: `91[.]92[.]43[.]221` | score 96, 3 reporting groups |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| ipsum_level5 | 4946 |
| greensnow_blocklist | 4833 |
| blocklist_de_ssh | 4427 |
| threatfox_export_json | 3144 |
| nist_nvd_recent | 2800 |
| cisa_kev | 1748 |
| spamhaus_drop | 1692 |
| tor_exit_nodes | 1211 |
| malwarebazaar_recent | 896 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3017 |
| sha256 | 2734 |
| ipv4_cidr | 1691 |
| url | 1368 |
| domain | 496 |
| md5 | 234 |
| sha1 | 234 |
| ipv4 | 226 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 3891 |
| cve | 3017 |
| malware | 1912 |
| exploited-in-the-wild | 1748 |
| drop | 1691 |
| spamhaus | 1691 |
| nvd | 1624 |
| elf | 1236 |
| Mirai | 1052 |
| ClickFix | 787 |

## Multi-group reporting overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 130[.]12[.]180[.]32 | blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]170[.]217[.]170 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]245[.]160[.]178 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]245[.]171[.]220 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 31[.]59[.]220[.]26 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]198[.]224[.]184 | blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
