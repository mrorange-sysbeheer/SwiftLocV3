# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-08T05:09:16Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-08T05:09:16Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 6153 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 1916 |
| Score (min / avg / max) | 80 / 81.1 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1916 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-08T04:55:47Z |

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
| sha256: `0034a00a2a4f32f5329a5ada096a1e5eac1e38a8849ec1891536792071f26738` | score 88, 2 sources |
| sha256: `006e08f1b8cad821f7849c282dc11d317e76ce66a5bcd84053dd5e7752e0606f` | score 88, 2 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| urlhaus_recent_urls | 14387 |
| greensnow_blocklist | 5499 |
| nist_nvd_recent | 5444 |
| blocklist_de_ssh | 4832 |
| ipsum_level5 | 3385 |
| threatfox_export_json | 2689 |
| binarydefense_banlist | 2520 |
| cisa_kev | 1734 |
| spamhaus_drop | 1671 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3055 |
| sha256 | 2256 |
| ipv4_cidr | 1670 |
| domain | 1361 |
| url | 1161 |
| ipv4 | 193 |
| md5 | 152 |
| sha1 | 152 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| threatfox | 3596 |
| malware | 3243 |
| cve | 3055 |
| exploited-in-the-wild | 1734 |
| drop | 1670 |
| spamhaus | 1670 |
| nvd | 1649 |
| malware_download | 1027 |
| etherhiding | 975 |
| Mirai | 673 |

## Multi-source overlaps

| Indicator | Sources |
| --- | --- |
| ipv4: 94[.]154[.]43[.]69 | binarydefense_banlist, blocklist_de_ssh, et_compromised, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 94[.]154[.]43[.]60 | binarydefense_banlist, blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 114[.]111[.]53[.]214 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]162[.]74 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 165[.]154[.]227[.]8 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]17[.]39[.]120 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]198[.]224[.]184 | blocklist_de_ssh, et_compromised, ipsum_level5, threatfox_export_json |
| ipv4: 45[.]78[.]201[.]248 | blocklist_de_ssh, greensnow_blocklist, ipsum_level5, threatfox_export_json |
| cve: CVE-2008-4128 | cisa_kev, nist_nvd_recent |
| cve: CVE-2009-3960 | cisa_kev, nist_nvd_recent |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
