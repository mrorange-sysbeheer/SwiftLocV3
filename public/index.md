# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-09-11T03:39:18Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-11T03:39:18Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 6638 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 562 |
| Score (min / avg / max) | 80 / 80.4 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 562 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-11T03:37:52Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `77[.]239[.]124[.]108` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `164[.]90[.]236[.]107` | score 96, 4 sources |
| ipv4: `176[.]65[.]139[.]206` | score 96, 4 sources |
| ipv4: `43[.]129[.]53[.]19` | score 96, 4 sources |
| ipv4: `43[.]156[.]71[.]43` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |
| ipv4: `68[.]233[.]116[.]124` | score 96, 4 sources |
| sha256: `066f74af1398ed730c07f281018946359d16d6e8eccd6c99d9ec7e606d55005a` | score 88, 2 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| threatfox_export_json | 6039 |
| greensnow_blocklist | 5326 |
| blocklist_de_ssh | 5286 |
| ipsum_level5 | 4011 |
| nist_nvd_recent | 3000 |
| binarydefense_banlist | 2896 |
| spamhaus_drop | 1711 |
| cisa_kev | 1705 |
| tor_exit_nodes | 1336 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 4110 |
| cve | 1815 |
| ipv4_cidr | 1683 |
| domain | 1601 |
| url | 365 |
| sha1 | 225 |
| ipv4 | 184 |
| md5 | 17 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 5549 |
| asyncrat | 3293 |
| rat | 3293 |
| cve | 1815 |
| exploited-in-the-wild | 1705 |
| drop | 1683 |
| spamhaus | 1683 |
| malware | 1254 |
| etherhiding | 1107 |
| Polygon | 631 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 77[.]239[.]124[.]108 | binarydefense_banlist, blocklist_de_ssh, ci_army_list, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 164[.]90[.]236[.]107 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 176[.]65[.]139[.]206 | blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]129[.]53[.]19 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]156[.]71[.]43 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 68[.]233[.]116[.]124 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]69 | blocklist_de_ssh, ipsum_level5, threatfox_export_json |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
