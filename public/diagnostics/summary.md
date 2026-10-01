# SwiftIOC IOC Summary

_Generated 2026-10-01T04:52:23Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-01T04:52:23Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 4354 |
| Sources reporting | 16 |
| Indicator types | 8 |
| Multi-source overlaps | 1363 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1363 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-01T04:47:53Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]69` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `103[.]182[.]132[.]154` | score 96, 4 sources |
| ipv4: `114[.]111[.]53[.]214` | score 96, 4 sources |
| ipv4: `165[.]154[.]162[.]74` | score 96, 4 sources |
| ipv4: `165[.]154[.]227[.]8` | score 96, 4 sources |
| ipv4: `43[.]156[.]71[.]43` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |
| ipv4: `45[.]198[.]224[.]184` | score 96, 4 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| blocklist_de_ssh | 4914 |
| nist_nvd_recent | 4583 |
| ipsum_level5 | 4072 |
| threatfox_export_json | 1943 |
| cisa_kev | 1730 |
| spamhaus_drop | 1693 |
| binarydefense_banlist | 1514 |
| tor_exit_nodes | 1407 |
| malwarebazaar_recent | 1258 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3337 |
| sha256 | 3170 |
| ipv4_cidr | 1362 |
| url | 889 |
| domain | 639 |
| ipv4 | 371 |
| sha1 | 182 |
| md5 | 50 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| malware | 3572 |
| cve | 3337 |
| threatfox | 2766 |
| nvd | 1905 |
| exploited-in-the-wild | 1730 |
| drop | 1362 |
| spamhaus | 1362 |
| Mirai | 1252 |
| high | 696 |
| malware_download | 664 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 176[.]65[.]139[.]206 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]182[.]132[.]154 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]156[.]71[.]43 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
