# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-02T20:27:05Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-02T20:27:05Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 3746 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 1473 |
| Score (min / avg / max) | 80 / 80.8 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1473 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-02T20:19:19Z |

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
| ipv4: `176[.]65[.]148[.]49` | score 96, 3 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| greensnow_blocklist | 4841 |
| ipsum_level5 | 4372 |
| threatfox_export_json | 2562 |
| nist_nvd_recent | 2400 |
| cisa_kev | 1733 |
| spamhaus_drop | 1693 |
| tor_exit_nodes | 1386 |
| malwarebazaar_recent | 1095 |
| blocklist_de_ssh | 759 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 2959 |
| cve | 2725 |
| ipv4_cidr | 1692 |
| domain | 1126 |
| url | 1078 |
| ipv4 | 209 |
| sha1 | 159 |
| md5 | 52 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 3461 |
| malware | 3259 |
| cve | 2725 |
| exploited-in-the-wild | 1733 |
| drop | 1692 |
| spamhaus | 1692 |
| nvd | 1300 |
| Mirai | 970 |
| ClickFix | 964 |
| malware_download | 754 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]182[.]132[.]154 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]156[.]71[.]43 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]198[.]224[.]184 | blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
