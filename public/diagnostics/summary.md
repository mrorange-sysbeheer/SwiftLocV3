# SwiftIOC IOC Summary

_Generated 2026-10-03T19:04:58Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-03T19:04:58Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 2903 |
| Sources reporting | 16 |
| Indicator types | 8 |
| Multi-source overlaps | 1469 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1469 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-03T19:04:49Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]69` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `114[.]111[.]53[.]214` | score 96, 4 sources |
| ipv4: `165[.]154[.]162[.]74` | score 96, 4 sources |
| ipv4: `165[.]154[.]227[.]8` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |
| ipv4: `45[.]198[.]224[.]184` | score 96, 4 sources |
| ipv4: `45[.]78[.]201[.]248` | score 96, 4 sources |
| ipv4: `209[.]126[.]103[.]97` | score 90, 3 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| threatfox_export_json | 4877 |
| greensnow_blocklist | 4611 |
| ipsum_level5 | 3528 |
| cisa_kev | 1733 |
| spamhaus_drop | 1693 |
| nist_nvd_recent | 1667 |
| tor_exit_nodes | 1396 |
| binarydefense_banlist | 1073 |
| malwarebazaar_recent | 945 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3058 |
| cve | 2294 |
| domain | 1908 |
| ipv4_cidr | 1362 |
| url | 1038 |
| ipv4 | 171 |
| sha1 | 131 |
| md5 | 38 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 4724 |
| malware | 2755 |
| cve | 2294 |
| exploited-in-the-wild | 1733 |
| elf | 1439 |
| Mirai | 1436 |
| etherhiding | 1415 |
| drop | 1362 |
| spamhaus | 1362 |
| ClickFix | 1030 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]198[.]224[.]184 | blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]78[.]201[.]248 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 176[.]65[.]148[.]49 | blocklist_de_ssh, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
