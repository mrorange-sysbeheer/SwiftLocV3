# SwiftIOC IOC Summary

_Generated 2026-09-14T03:57:23Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-14T03:57:23Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 4785 |
| Sources reporting | 16 |
| Indicator types | 9 |
| Multi-source overlaps | 792 |
| Score (min / avg / max) | 79 / 80.6 / 96 |
| High-score indicators (≥80) | 9939 |
| Corroborated (2+ sources) | 792 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-14T03:47:32Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `77[.]239[.]124[.]108` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `103[.]182[.]132[.]154` | score 96, 4 sources |
| ipv4: `114[.]111[.]53[.]214` | score 96, 4 sources |
| ipv4: `176[.]65[.]139[.]206` | score 96, 4 sources |
| ipv4: `43[.]129[.]53[.]19` | score 96, 4 sources |
| ipv4: `43[.]156[.]71[.]43` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |
| ipv4: `45[.]78[.]201[.]248` | score 96, 4 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| greensnow_blocklist | 4769 |
| ipsum_level5 | 4238 |
| binarydefense_banlist | 3643 |
| spamhaus_drop | 1725 |
| cisa_kev | 1709 |
| threatfox_export_json | 1581 |
| tor_exit_nodes | 1323 |
| et_compromised | 610 |
| nist_nvd_recent | 595 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3437 |
| cve | 2801 |
| ipv4_cidr | 1724 |
| url | 523 |
| domain | 488 |
| sha1 | 418 |
| ipv4 | 302 |
| md5 | 210 |
| ja3 | 97 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 4478 |
| cve | 2801 |
| rat | 2375 |
| asyncrat | 2373 |
| drop | 1724 |
| spamhaus | 1724 |
| exploited-in-the-wild | 1709 |
| malware | 1414 |
| nvd | 1336 |
| high | 538 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 77[.]239[.]124[.]108 | binarydefense_banlist, blocklist_de_ssh, ci_army_list, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]182[.]132[.]154 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 164[.]90[.]236[.]107 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 176[.]65[.]139[.]206 | blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]129[.]53[.]19 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]156[.]71[.]43 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
