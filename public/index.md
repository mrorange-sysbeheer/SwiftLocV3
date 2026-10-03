# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-03T13:08:24Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-03T13:08:24Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 2115 |
| Sources reporting | 15 |
| Indicator types | 8 |
| Multi-source overlaps | 1480 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1480 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-03T13:08:12Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]69` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |
| ipv4: `45[.]198[.]224[.]184` | score 96, 4 sources |
| ipv4: `103[.]176[.]64[.]36` | score 93, 4 sources |
| ipv4: `114[.]111[.]53[.]214` | score 93, 4 sources |
| ipv4: `165[.]154[.]162[.]74` | score 93, 4 sources |
| ipv4: `165[.]154[.]227[.]8` | score 93, 4 sources |
| ipv4: `45[.]78[.]201[.]248` | score 93, 4 sources |
| ipv4: `209[.]126[.]103[.]97` | score 93, 3 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| threatfox_export_json | 4810 |
| ipsum_level5 | 3528 |
| nist_nvd_recent | 2188 |
| cisa_kev | 1733 |
| spamhaus_drop | 1693 |
| tor_exit_nodes | 1388 |
| binarydefense_banlist | 1073 |
| malwarebazaar_recent | 984 |
| urlhaus_recent_urls | 673 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3259 |
| cve | 2593 |
| domain | 1998 |
| url | 973 |
| ipv4_cidr | 778 |
| ipv4 | 193 |
| sha1 | 149 |
| md5 | 57 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 4828 |
| malware | 2945 |
| cve | 2593 |
| exploited-in-the-wild | 1733 |
| etherhiding | 1429 |
| Mirai | 1411 |
| elf | 1275 |
| nvd | 1168 |
| ClickFix | 1063 |
| drop | 778 |

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
