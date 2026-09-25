# SwiftIOC IOC Summary

_Generated 2026-09-25T04:01:36Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-25T04:01:36Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 9268 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 1168 |
| Score (min / avg / max) | 80 / 80.6 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1168 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-09-25T03:59:30Z |

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
| blocklist_de_ssh | 11591 |
| binarydefense_banlist | 5974 |
| greensnow_blocklist | 5426 |
| ipsum_level5 | 5065 |
| threatfox_export_json | 4389 |
| malwarebazaar_recent | 2642 |
| cisa_kev | 1723 |
| spamhaus_drop | 1710 |
| nist_nvd_recent | 1600 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3208 |
| cve | 2253 |
| ipv4_cidr | 1709 |
| domain | 1651 |
| url | 738 |
| sha1 | 230 |
| ipv4 | 189 |
| md5 | 22 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| malware | 3803 |
| threatfox | 3095 |
| cve | 2253 |
| exploited-in-the-wild | 1723 |
| drop | 1709 |
| spamhaus | 1709 |
| Mirai | 1607 |
| etherhiding | 1100 |
| victim | 1041 |
| nvd | 807 |

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
