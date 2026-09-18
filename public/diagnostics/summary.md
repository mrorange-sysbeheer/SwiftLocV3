# SwiftIOC IOC Summary

_Generated 2026-09-18T22:23:14Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-18T22:23:14Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 7452 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 931 |
| Score (min / avg / max) | 80 / 80.6 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 931 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-18T22:22:51Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `77[.]239[.]124[.]108` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `94[.]154[.]43[.]69` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `103[.]182[.]132[.]154` | score 96, 4 sources |
| ipv4: `114[.]111[.]53[.]214` | score 96, 4 sources |
| ipv4: `176[.]65[.]139[.]206` | score 96, 4 sources |
| ipv4: `43[.]129[.]53[.]19` | score 96, 4 sources |
| ipv4: `43[.]156[.]71[.]43` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| blocklist_de_ssh | 5663 |
| greensnow_blocklist | 4805 |
| binarydefense_banlist | 4595 |
| ipsum_level5 | 4517 |
| threatfox_export_json | 2754 |
| nist_nvd_recent | 2600 |
| cisa_kev | 1716 |
| spamhaus_drop | 1713 |
| malwarebazaar_recent | 1411 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3765 |
| sha256 | 2458 |
| ipv4_cidr | 1709 |
| domain | 849 |
| url | 621 |
| ipv4 | 300 |
| sha1 | 253 |
| md5 | 45 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| cve | 3765 |
| malware | 3045 |
| nvd | 2302 |
| threatfox | 2132 |
| exploited-in-the-wild | 1716 |
| drop | 1709 |
| spamhaus | 1709 |
| high | 743 |
| Mirai | 502 |
| medium | 423 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 77[.]239[.]124[.]108 | binarydefense_banlist, blocklist_de_ssh, ci_army_list, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]182[.]132[.]154 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 176[.]65[.]139[.]206 | blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]129[.]53[.]19 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]156[.]71[.]43 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
