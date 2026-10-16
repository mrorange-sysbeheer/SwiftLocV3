# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-16T22:39:40Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-16T22:39:40Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 5570 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-group overlaps | 385 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-score indicators (≥80) | 10000 |
| 2+ reporting groups | 385 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-16T22:39:19Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]69` | score 96, 5 reporting groups |
| ipv4: `103[.]170[.]217[.]170` | score 96, 3 reporting groups |
| ipv4: `114[.]111[.]53[.]214` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]162[.]74` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]227[.]8` | score 96, 3 reporting groups |
| ipv4: `165[.]245[.]160[.]178` | score 96, 3 reporting groups |
| ipv4: `31[.]59[.]220[.]26` | score 96, 3 reporting groups |
| ipv4: `45[.]198[.]224[.]184` | score 96, 3 reporting groups |
| ipv4: `45[.]78[.]201[.]248` | score 96, 3 reporting groups |
| ipv4: `91[.]92[.]43[.]221` | score 96, 3 reporting groups |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| ipsum_level5 | 4457 |
| blocklist_de_ssh | 4377 |
| threatfox_export_json | 4367 |
| greensnow_blocklist | 4284 |
| nist_nvd_recent | 2600 |
| cisa_kev | 1748 |
| spamhaus_drop | 1691 |
| tor_exit_nodes | 1207 |
| binarydefense_banlist | 734 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3160 |
| url | 2203 |
| sha256 | 2131 |
| ipv4_cidr | 1439 |
| domain | 427 |
| ipv4 | 314 |
| md5 | 163 |
| sha1 | 163 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 4105 |
| cve | 3160 |
| nvd | 1767 |
| exploited-in-the-wild | 1748 |
| malware | 1590 |
| drop | 1439 |
| spamhaus | 1439 |
| c2 | 1295 |
| Vidar | 1218 |
| stealer | 1214 |

## Multi-group reporting overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]170[.]217[.]170 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]245[.]160[.]178 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]245[.]171[.]220 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 31[.]59[.]220[.]26 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 36[.]50[.]134[.]86 | blocklist_de_ssh, ci_army_list, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
