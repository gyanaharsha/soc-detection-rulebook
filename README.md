# SOC Detection Rulebook

> Battle-tested SIEM detection rules by a working SOC analyst.
> Mapped to MITRE ATT&CK. Ready for Splunk, Microsoft Sentinel, and Elastic.

![Rules](https://img.shields.io/badge/rules-12-blue)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-mapped-orange)
![License](https://img.shields.io/badge/license-MIT-green)

## What this is

A curated library of detection rules written from real SOC experience.
Each rule includes the detection logic, MITRE mapping, severity rating,
false positive guidance, and analyst triage notes.

## Who it's for

- SOC analysts who want ready-to-use rules for their SIEM
- Detection engineers building or improving detection coverage
- Security teams benchmarking their ATT&CK coverage

## Rules by tactic

| Tactic | Rules | MITRE IDs |
|---|---|---|
| Initial Access | 3 | T1078, T1190, T1566 |
| Privilege Escalation | 2 | T1068, T1548 |
| ... | ... | ... |

## Rule format

All rules are written in YAML with optional SIEM-specific translations.
See [docs/rule-schema.md](docs/rule-schema.md) for the full spec.

## About the author

Gyana Harsha Neeli — SOC Analyst with 16 months experience in SIEM.
[LinkedIn URL] | [Any certs e.g. CEH, SC-200]

