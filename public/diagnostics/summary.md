# SwiftIOC IOC Summary

_Generated 2026-09-30T14:43:53Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-30T14:43:53Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 5806 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 1331 |
| Score (min / avg / max) | 80 / 80.7 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1331 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-09-30T14:43:31Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]69` | score 96, 6 sources |
| ipv4: `176[.]65[.]139[.]206` | score 96, 5 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
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
| blocklist_de_ssh | 5382 |
| greensnow_blocklist | 4905 |
| ipsum_level5 | 4277 |
| nist_nvd_recent | 2754 |
| threatfox_export_json | 1857 |
| cisa_kev | 1729 |
| spamhaus_drop | 1693 |
| tor_exit_nodes | 1409 |
| malwarebazaar_recent | 1300 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3493 |
| cve | 3242 |
| ipv4_cidr | 1142 |
| url | 825 |
| domain | 700 |
| ipv4 | 366 |
| sha1 | 182 |
| md5 | 50 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| malware | 3814 |
| cve | 3242 |
| threatfox | 2816 |
| nvd | 1801 |
| exploited-in-the-wild | 1729 |
| Mirai | 1522 |
| drop | 1142 |
| spamhaus | 1142 |
| malware_download | 618 |
| high | 611 |

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
