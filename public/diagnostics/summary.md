# SwiftIOC IOC Summary

_Generated 2026-09-26T12:45:41Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-26T12:45:41Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 8593 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 1218 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1218 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-09-26T12:45:18Z |

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
| binarydefense_banlist | 6160 |
| blocklist_de_ssh | 5016 |
| ipsum_level5 | 4856 |
| greensnow_blocklist | 4840 |
| threatfox_export_json | 2480 |
| nist_nvd_recent | 2200 |
| cisa_kev | 1726 |
| spamhaus_drop | 1711 |
| malwarebazaar_recent | 1545 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 2839 |
| sha256 | 2590 |
| domain | 1710 |
| ipv4_cidr | 1710 |
| url | 735 |
| sha1 | 228 |
| ipv4 | 168 |
| md5 | 20 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 3204 |
| malware | 3150 |
| cve | 2839 |
| exploited-in-the-wild | 1726 |
| drop | 1710 |
| spamhaus | 1710 |
| nvd | 1397 |
| Mirai | 1271 |
| ClickFix | 942 |
| etherhiding | 719 |

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
