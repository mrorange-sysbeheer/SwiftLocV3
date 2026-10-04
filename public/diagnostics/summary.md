# SwiftIOC IOC Summary

_Generated 2026-10-04T19:18:03Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-04T19:18:03Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 2791 |
| Sources reporting | 16 |
| Indicator types | 8 |
| Multi-source overlaps | 1405 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1405 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-04T19:17:55Z |

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
| sha256: `0345370e70311cfab06adb18c67785c3f8377f35a66b54d0619d620434165373` | score 88, 2 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| threatfox_export_json | 4894 |
| greensnow_blocklist | 4305 |
| ipsum_level5 | 3731 |
| cisa_kev | 1733 |
| spamhaus_drop | 1692 |
| tor_exit_nodes | 1398 |
| binarydefense_banlist | 1397 |
| malwarebazaar_recent | 1036 |
| urlhaus_recent_urls | 864 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3934 |
| cve | 1925 |
| ipv4_cidr | 1691 |
| domain | 1250 |
| url | 996 |
| ipv4 | 173 |
| sha1 | 26 |
| md5 | 5 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 4653 |
| malware | 2803 |
| Mirai | 2217 |
| elf | 2152 |
| cve | 1925 |
| exploited-in-the-wild | 1733 |
| drop | 1691 |
| spamhaus | 1691 |
| etherhiding | 960 |
| malware_download | 818 |

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
| ipv4: 209[.]126[.]103[.]97 | ci_army_list, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
