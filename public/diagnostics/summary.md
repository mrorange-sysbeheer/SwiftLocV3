# SwiftIOC IOC Summary

_Generated 2026-10-06T18:04:34Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-06T18:04:34Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 6119 |
| Sources reporting | 17 |
| Indicator types | 6 |
| Multi-source overlaps | 1765 |
| Score (min / avg / max) | 80 / 81.0 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 1765 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-06T18:04:04Z |

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
| sha256: `01325b5d6ae777813bf88b5804468c1a53c3a1e5ad3448ae274f60cb8ea0dcd0` | score 88, 2 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| urlhaus_recent_urls | 14596 |
| greensnow_blocklist | 4970 |
| blocklist_de_ssh | 4223 |
| threatfox_export_json | 4170 |
| ipsum_level5 | 4122 |
| nist_nvd_recent | 2200 |
| binarydefense_banlist | 1976 |
| cisa_kev | 1734 |
| spamhaus_drop | 1641 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| url | 3431 |
| cve | 2071 |
| sha256 | 1759 |
| ipv4_cidr | 1640 |
| domain | 1050 |
| ipv4 | 49 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| malware | 5103 |
| malware_download | 3403 |
| zip | 3217 |
| github | 3203 |
| LuaJIT-loader | 3188 |
| SmartLoader | 3188 |
| threatfox | 2617 |
| cve | 2071 |
| exploited-in-the-wild | 1734 |
| drop | 1640 |

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
