# SwiftIOC IOC Summary

_Generated 2026-10-13T11:31:07Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-13T11:31:07Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 7434 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-group overlaps | 373 |
| Score (min / avg / max) | 80 / 80.3 / 96 |
| High-score indicators (≥80) | 10000 |
| 2+ reporting groups | 373 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-13T11:30:27Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 reporting groups |
| ipv4: `94[.]154[.]43[.]69` | score 96, 5 reporting groups |
| ipv4: `114[.]111[.]53[.]214` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]162[.]74` | score 96, 3 reporting groups |
| ipv4: `165[.]154[.]227[.]8` | score 96, 3 reporting groups |
| ipv4: `165[.]245[.]160[.]178` | score 96, 3 reporting groups |
| ipv4: `165[.]245[.]171[.]220` | score 96, 3 reporting groups |
| ipv4: `31[.]59[.]220[.]26` | score 96, 3 reporting groups |
| ipv4: `36[.]50[.]134[.]86` | score 96, 3 reporting groups |
| ipv4: `45[.]198[.]224[.]184` | score 96, 3 reporting groups |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| ipsum_level5 | 5079 |
| greensnow_blocklist | 4786 |
| blocklist_de_ssh | 4308 |
| binarydefense_banlist | 3918 |
| nist_nvd_recent | 2800 |
| threatfox_export_json | 2357 |
| cisa_kev | 1739 |
| spamhaus_drop | 1678 |
| tor_exit_nodes | 1207 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3482 |
| url | 2112 |
| sha256 | 1836 |
| ipv4_cidr | 1677 |
| ipv4 | 323 |
| domain | 268 |
| md5 | 151 |
| sha1 | 151 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| cve | 3482 |
| malware | 2861 |
| threatfox | 2555 |
| nvd | 2085 |
| exploited-in-the-wild | 1739 |
| drop | 1677 |
| spamhaus | 1677 |
| malware_download | 1140 |
| medium | 837 |
| Mirai | 820 |

## Multi-group reporting overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]245[.]160[.]178 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]245[.]171[.]220 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 31[.]59[.]220[.]26 | binarydefense_banlist, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 36[.]50[.]134[.]86 | blocklist_de_ssh, ci_army_list, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
