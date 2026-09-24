# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-09-24T09:06:46Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-24T09:06:46Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 9066 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 1141 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1141 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-09-24T09:05:43Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `77[.]239[.]124[.]108` | score 96, 6 sources |
| ipv4: `176[.]65[.]139[.]206` | score 96, 5 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `94[.]154[.]43[.]69` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `103[.]182[.]132[.]154` | score 96, 4 sources |
| ipv4: `114[.]111[.]53[.]214` | score 96, 4 sources |
| ipv4: `165[.]154[.]162[.]74` | score 96, 4 sources |
| ipv4: `165[.]154[.]227[.]8` | score 96, 4 sources |
| ipv4: `43[.]156[.]71[.]43` | score 96, 4 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| blocklist_de_ssh | 11752 |
| binarydefense_banlist | 5786 |
| greensnow_blocklist | 5605 |
| threatfox_export_json | 4923 |
| ipsum_level5 | 4859 |
| nist_nvd_recent | 2882 |
| malwarebazaar_recent | 2153 |
| cisa_kev | 1721 |
| spamhaus_drop | 1712 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 2605 |
| domain | 2458 |
| cve | 2256 |
| ipv4_cidr | 1666 |
| url | 645 |
| sha1 | 216 |
| ipv4 | 146 |
| md5 | 8 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 3942 |
| malware | 2983 |
| cve | 2256 |
| exploited-in-the-wild | 1721 |
| drop | 1666 |
| spamhaus | 1666 |
| ClickFix | 1191 |
| etherhiding | 1100 |
| victim | 1041 |
| Mirai | 1036 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 77[.]239[.]124[.]108 | binarydefense_banlist, blocklist_de_ssh, ci_army_list, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 176[.]65[.]139[.]206 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]182[.]132[.]154 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]156[.]71[.]43 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
