# Contributing

Thank you for contributing to SOC Detection Rulebook!

## How to add a rule

1. Fork this repository
2. Create a new YAML file in the correct tactic folder
   e.g. rules/privilege-escalation/my-rule.yml
3. Follow the schema in docs/rule-schema.md exactly
4. Test your rule in at least one SIEM before submitting
5. Open a Pull Request with a description of what the rule detects

## Rule quality standards

- Must be mapped to at least one MITRE ATT&CK technique
- Must include false positive guidance
- Must include at least one tested SIEM query (Splunk, KQL, or Sigma)
- Should include a real-world scenario where this fires

## Not sure where to start?

Look for issues labelled `rule-request` — these are detections
the community has asked for but no one has written yet.
