# SOC Investigation Portfolio

Hands-on SOC investigations completed in simulated security environments.

This portfolio documents my practical approach to alert triage, incident investigation, evidence correlation, and endpoint analysis while developing toward a Security Operations Centre role.

The focus of these reports is not only the final answer, but the investigation process: identifying relevant entities, validating assumptions, correlating telemetry, determining scope, and documenting findings clearly.

---

## Skills Demonstrated

- Alert triage
- SIEM investigation
- EDR analysis
- Windows Event Log analysis
- Authentication analysis
- Firewall and network telemetry
- Process and command-line analysis
- Incident timeline reconstruction
- Incident scoping
- MITRE ATT&CK mapping
- True-positive / false-positive assessment
- Endpoint containment
- Technical incident documentation

---

## Investigations

### 01 — RDP Compromise and Host Discovery

Investigation of unauthorized RDP access to a Windows endpoint followed by interactive system and network discovery.

The investigation involved correlation of firewall telemetry, Windows authentication events, endpoint process activity, and terminal history to identify the source of the compromise and reconstruct the post-authentication activity.

**Key areas:** RDP, Event ID 4624, Logon Type 10, Windows discovery commands, EDR analysis, incident containment.

[View Investigation](./RDP Compromise and Host Discovery/README.md)
