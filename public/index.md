# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-15T03:44:01Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-15T03:44:01Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 6054 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-group overlaps | 378 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-score indicators (≥80) | 10000 |
| 2+ reporting groups | 378 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-15T03:34:28Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 reporting groups |
| ipv4: `94[.]154[.]43[.]69` | score 96, 5 reporting groups |
| ipv4: `103[.]170[.]217[.]170` | score 96, 3 reporting groups |
| ipv4: `114[.]111[.]53[.]214` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]162[.]74` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]227[.]8` | score 96, 3 reporting groups |
| ipv4: `165[.]245[.]160[.]178` | score 96, 3 reporting groups |
| ipv4: `165[.]245[.]171[.]220` | score 96, 3 reporting groups |
| ipv4: `31[.]59[.]220[.]26` | score 96, 3 reporting groups |
| ipv4: `36[.]50[.]134[.]86` | score 96, 3 reporting groups |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| greensnow_blocklist | 5588 |
| ipsum_level5 | 4416 |
| blocklist_de_ssh | 4116 |
| threatfox_export_json | 3925 |
| nist_nvd_recent | 3200 |
| cisa_kev | 1745 |
| spamhaus_drop | 1682 |
| malwarebazaar_recent | 1252 |
| tor_exit_nodes | 1210 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 4058 |
| url | 2088 |
| ipv4_cidr | 1680 |
| sha256 | 1112 |
| domain | 620 |
| ipv4 | 192 |
| md5 | 125 |
| sha1 | 125 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| cve | 4058 |
| threatfox | 3091 |
| nvd | 2662 |
| exploited-in-the-wild | 1745 |
| drop | 1680 |
| spamhaus | 1680 |
| high | 1451 |
| malware | 1399 |
| c2 | 1207 |
| stealer | 1174 |

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
