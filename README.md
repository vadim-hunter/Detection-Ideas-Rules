# Detection Ideas & Rules
Every day a number of Threat Intelligence reports come into the world. Prepared by different vendors and teams *almost* none of them contain ready to use detection ideas and rules. In most cases we get only list of IOCs associated with particular threat actor. From my perspective, the reason of that is that DFIR teams do their job perfectly, but detection engineering is simply not their job. It is our - Threat Hunters' job.

The idea of this repository is to analyze public Threat Intelligence reports, interesting TTPs, tools and various offensive tradecraft to generate ready to use detection ideas and rules implementations, which can be used by threat hunters and security monitoring teams.

## Summary
### MITRE ATT&CK TTPs
#### Defense Evasion
- T1218 - Signed Binary Proxy Execution
  - T1218.003 - CSMTP (4/7)
- T1564 - Hide Artifacts
  - T1564.001 - Hidden Files and Directories (2/4)
#### Credential Access
- T1187 - Forced Authentication (1/3)
#### Command and Control
- T1105 - Ingress Tool Transfer (4/7)
- T1071 - Application Layer Protocol
  - T1071.001 - Web Protocols (2/3)

### Threat Intelligence
- Microsoft Threat Intelligence Center (MSTIC)
  - Breaking down NOBELIUM’s latest early-stage toolset (9/17)
