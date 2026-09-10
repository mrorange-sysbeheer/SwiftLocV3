# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-09-10T16:02:51Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-09-10T16:02:51Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 3963 |
| Sources reporting | 16 |
| Indicator types | 8 |
| Multi-source overlaps | 560 |
| Score (min / avg / max) | 80 / 80.4 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 560 |
| Earliest first_seen | 2016-05-11T01:59:46Z |
| Newest first_seen | 2026-09-10T16:01:20Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `77[.]239[.]124[.]108` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `103[.]176[.]64[.]36` | score 96, 4 sources |
| ipv4: `164[.]90[.]236[.]107` | score 96, 4 sources |
| ipv4: `43[.]129[.]53[.]19` | score 96, 4 sources |
| ipv4: `43[.]156[.]71[.]43` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |
| ipv4: `68[.]233[.]116[.]124` | score 96, 4 sources |
| ipv4: `94[.]154[.]43[.]69` | score 89, 3 sources |
| sha256: `066f74af1398ed730c07f281018946359d16d6e8eccd6c99d9ec7e606d55005a` | score 88, 2 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| blocklist_de_ssh | 5349 |
| threatfox_export_json | 5014 |
| ipsum_level5 | 3889 |
| nist_nvd_recent | 3600 |
| binarydefense_banlist | 2650 |
| spamhaus_drop | 1711 |
| cisa_kev | 1703 |
| tor_exit_nodes | 1335 |
| malwarebazaar_recent | 1006 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 4309 |
| cve | 2444 |
| ipv4_cidr | 1222 |
| domain | 883 |
| url | 617 |
| ipv4 | 247 |
| sha1 | 243 |
| md5 | 35 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 5015 |
| rat | 3311 |
| asyncrat | 3293 |
| cve | 2444 |
| exploited-in-the-wild | 1703 |
| malware | 1620 |
| drop | 1222 |
| spamhaus | 1222 |
| nvd | 979 |
| malware_download | 446 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 77[.]239[.]124[.]108 | binarydefense_banlist, blocklist_de_ssh, ci_army_list, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 103[.]176[.]64[.]36 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 164[.]90[.]236[.]107 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]129[.]53[.]19 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 43[.]156[.]71[.]43 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 68[.]233[.]116[.]124 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]69 | blocklist_de_ssh, ipsum_level5, threatfox_export_json |
| cve: CVE-2009-3960 | cisa_kev, nist_nvd_recent |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
