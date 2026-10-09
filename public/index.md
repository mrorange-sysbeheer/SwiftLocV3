# SwiftIOC Threat Intelligence Snapshot

This site is generated automatically from the latest SwiftIOC collection run.

_Generated 2026-10-09T05:18:51Z_

## Highlights

| Metric | Value |
| --- | ---: |
| Generated | 2026-10-09T05:18:51Z |
| Window (hours) | 48 |
| Total indicators | 10000 |
| Duplicates removed | 7526 |
| Sources reporting | 17 |
| Indicator types | 8 |
| Multi-source overlaps | 2085 |
| Score (min / avg / max) | 80 / 81.2 / 96 |
| High-score indicators (≥80) | 10000 |
| Corroborated (2+ sources) | 2085 |
| Earliest first_seen | 2008-09-18T20:00:00Z |
| Newest first_seen | 2026-10-09T05:09:14Z |

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
| ipv4: `36[.]50[.]134[.]86` | score 96, 3 sources |
| sha256: `0034a00a2a4f32f5329a5ada096a1e5eac1e38a8849ec1891536792071f26738` | score 88, 2 sources |

## Per-source totals

| Source | Indicators |
| --- | ---: |
| ci_army_list | 15000 |
| nist_nvd_recent | 7479 |
| greensnow_blocklist | 5433 |
| ipsum_level5 | 4686 |
| blocklist_de_ssh | 4632 |
| binarydefense_banlist | 2809 |
| threatfox_export_json | 2006 |
| urlhaus_recent_urls | 1992 |
| cisa_kev | 1739 |
| spamhaus_drop | 1672 |

## Indicator types

| Type | Indicators |
| --- | ---: |
| cve | 3003 |
| sha256 | 2643 |
| url | 2252 |
| domain | 773 |
| ipv4_cidr | 694 |
| ipv4 | 255 |
| md5 | 190 |
| sha1 | 190 |

## Top tags

| Tag | Indicators |
| --- | ---: |
| malware | 4525 |
| threatfox | 3499 |
| cve | 3003 |
| malware_download | 1996 |
| exploited-in-the-wild | 1739 |
| nvd | 1604 |
| CheatSheet | 1331 |
| exe | 1271 |
| Mirai | 782 |
| elf | 712 |

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
| ipv4: 36[.]50[.]134[.]86 | blocklist_de_ssh, ipsum_level5, threatfox_export_json |
| cve: CVE-2008-4128 | cisa_kev, nist_nvd_recent |

For more detail see [diagnostics/REPORT.md](diagnostics/REPORT.md) and the machine-readable feeds in [iocs/](iocs/).
