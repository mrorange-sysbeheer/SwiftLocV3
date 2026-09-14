# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-09-14T17:54:40Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-14T17:54:40Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 6020 |
| Sources reporting | 16 |
| Indicator types | 9 |
| Multi-source overlaps | 823 |
| Score (min / avg / max) | 79 / 80.5 / 96 |
| High-score indicators (≥80) | 9624 |
| Corroborated (2+ sources) | 823 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-14T17:53:17Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `77[.]239[.]124[.]108` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `103[.]182[.]132[.]154` | score 96, 4 sources |
| ipv4: `114[.]111[.]53[.]214` | score 96, 4 sources |
| ipv4: `164[.]90[.]236[.]107` | score 96, 4 sources |
| ipv4: `176[.]65[.]139[.]206` | score 96, 4 sources |
| ipv4: `43[.]129[.]53[.]19` | score 96, 4 sources |
| ipv4: `43[.]156[.]71[.]43` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| blocklist_de_ssh | 5176 |
| greensnow_blocklist | 4265 |
| ipsum_level5 | 4238 |
| binarydefense_banlist | 3643 |
| spamhaus_drop | 1725 |
| cisa_kev | 1709 |
| tor_exit_nodes | 1224 |
| nist_nvd_recent | 1156 |
| et_compromised | 610 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 3555 |
| cve | 3311 |
| ipv4_cidr | 1724 |
| url | 450 |
| domain | 376 |
| sha1 | 336 |
| md5 | 128 |
| ja3 | 97 |
| ipv4 | 23 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 3765 |
| cve | 3311 |
| rat | 2396 |
| asyncrat | 2373 |
| nvd | 1846 |
| drop | 1724 |
| spamhaus | 1724 |
| exploited-in-the-wild | 1709 |
| malware | 1647 |
| high | 686 |

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
