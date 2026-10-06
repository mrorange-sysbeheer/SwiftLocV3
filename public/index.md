# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-06T01:11:40Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-06T01:11:40Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 2265 |
| Sources reporting | 15 |
| Indicator types | 8 |
| Multi-source overlaps | 1738 |
| Score (min / avg / max) | 80 / 81.0 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1738 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-06T01:02:12Z |

## Top indicators by score

| Indicator | Score / corroboration |
| --- | ---: |
| ipv4: `94[.]154[.]43[.]69` | score 96, 6 sources |
| ipv4: `94[.]154[.]43[.]60` | score 96, 5 sources |
| ipv4: `114[.]111[.]53[.]214` | score 96, 4 sources |
| ipv4: `165[.]154[.]162[.]74` | score 96, 4 sources |
| ipv4: `165[.]154[.]227[.]8` | score 96, 4 sources |
| ipv4: `45[.]17[.]39[.]120` | score 96, 4 sources |
| ipv4: `45[.]198[.]224[.]184` | score 96, 4 sources |
| ipv4: `45[.]78[.]201[.]248` | score 96, 4 sources |
| ipv4: `103[.]176[.]64[.]36` | score 88, 4 sources |
| sha256: `01b5a60b54ff4a0f670e39a6d567f02bc69338ccfae2d679a17ed09247e284e6` | score 88, 2 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| threatfox_export_json | 4437 |
| ipsum_level5 | 4122 |
| binarydefense_banlist | 1976 |
| cisa_kev | 1734 |
| spamhaus_drop | 1641 |
| nist_nvd_recent | 1544 |
| tor_exit_nodes | 1360 |
| malwarebazaar_recent | 1053 |
| urlhaus_recent_urls | 756 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| sha256 | 4321 |
| cve | 2218 |
| ipv4_cidr | 1499 |
| url | 932 |
| domain | 662 |
| ipv4 | 176 |
| md5 | 108 |
| sha1 | 84 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 4641 |
| malware | 3046 |
| Mirai | 2417 |
| elf | 2411 |
| cve | 2246 |
| exploited-in-the-wild | 1734 |
| drop | 1499 |
| spamhaus | 1499 |
| nvd | 793 |
| malware_download | 759 |

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
| cve: CVE-2008-4128 | cisa_kev, nist_nvd_recent |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
