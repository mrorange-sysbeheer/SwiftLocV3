# SwiftIOC IOC Summary

_Generated 2026-09-24T23:05:21Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-24T23:05:21Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 8710 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 1168 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1168 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-09-24T23:04:54Z |

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
| blocklist_de_ssh | 11626 |
| binarydefense_banlist | 5786 |
| greensnow_blocklist | 5476 |
| ipsum_level5 | 4859 |
| threatfox_export_json | 4503 |
| nist_nvd_recent | 2600 |
| malwarebazaar_recent | 2488 |
| cisa_kev | 1723 |
| spamhaus_drop | 1710 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 2944 |
| domain | 2281 |
| cve | 2253 |
| ipv4_cidr | 1412 |
| url | 680 |
| sha1 | 230 |
| ipv4 | 178 |
| md5 | 22 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 3691 |
| malware | 3504 |
| cve | 2253 |
| exploited-in-the-wild | 1723 |
| drop | 1412 |
| spamhaus | 1412 |
| Mirai | 1378 |
| ClickFix | 1225 |
| etherhiding | 1100 |
| victim | 1041 |

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
