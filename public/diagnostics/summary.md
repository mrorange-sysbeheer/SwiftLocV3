# SwiftIOC IOC Summary

_Generated 2026-09-28T16:34:03Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-28T16:34:03Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 5982 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 1326 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1326 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-09-28T16:33:30Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `176[.]65[.]139[.]206` | score 96, 5 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `94[.]154[.]43[.]69` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `103[.]182[.]132[.]154` | score 96, 4 sources |
| ipv4: `114[.]111[.]53[.]214` | score 96, 4 sources |
| ipv4: `165[.]154[.]162[.]74` | score 96, 4 sources |
| ipv4: `165[.]154[.]227[.]8` | score 96, 4 sources |
| ipv4: `43[.]156[.]71[.]43` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| blocklist_de_ssh | 11837 |
| threatfox_export_json | 6122 |
| greensnow_blocklist | 4849 |
| ipsum_level5 | 4467 |
| cisa_kev | 1728 |
| spamhaus_drop | 1693 |
| tor_exit_nodes | 1366 |
| malwarebazaar_recent | 1310 |
| nist_nvd_recent | 1008 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3002 |
| cve | 2650 |
| ipv4_cidr | 1624 |
| domain | 1322 |
| url | 984 |
| sha1 | 234 |
| ipv4 | 158 |
| md5 | 26 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| malware | 3687 |
| threatfox | 3048 |
| cve | 2650 |
| exploited-in-the-wild | 1728 |
| drop | 1624 |
| spamhaus | 1624 |
| Mirai | 1381 |
| nvd | 1208 |
| etherhiding | 956 |
| malware_download | 744 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 176[.]65[.]139[.]206 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]182[.]132[.]154 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]156[.]71[.]43 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
