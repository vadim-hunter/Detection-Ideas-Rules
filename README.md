# Detection Ideas & Rules
Every day a number of Threat Intelligence reports come into the world. Prepared by different vendors and teams *almost* none of them contain ready to use detection ideas and rules. In most cases we get only list of IOCs associated with particular threat actor. From my perspective, the reason of that is that DFIR teams do their job perfectly, but detection engineering is simply not their job. It is our - Threat Hunters' job.

The idea of this repository is to analyze public Threat Intelligence reports, interesting TTPs, tools and various offensive tradecraft to generate ready to use detection ideas and rules implementations, which can be used by threat hunters and security monitoring teams.

Note: in brackets (procedures/ideas/rules) or just (ideas/rules).

## Summary
### MITRE ATT&CK TTPs
#### Persistence
- TXXXX - Active Directory Object ACL manipulation
  - TXXXX.001 - AdminSDHolder (3/5/15)
#### Defense Evasion
- T1070 - Indicator Removal on Host
  - T1070.001 - Clear Windows Event Logs (7/12/31) 
- T1218 - Signed Binary Proxy Execution
  - T1218.003 - CSMTP (2/4/7)
- T1564 - Hide Artifacts
  - T1564.001 - Hidden Files and Directories (2/2/4)
- T1197 - BITS Jobs (5/7/20)
#### Credential Access
- T1187 - Forced Authentication (1/3)
#### Command and Control
- T1105 - Ingress Tool Transfer (2/4/7)
- T1071 - Application Layer Protocol
  - T1071.001 - Web Protocols (2/3)

### Threat Intelligence
- Microsoft Threat Intelligence Center (MSTIC)
  - Breaking down NOBELIUM’s latest early-stage toolset (11/19)
- The DFIR Report
  - Sodinokibi (aka REvil) Ransomware (37/78)

### Tools
- Invoke-Phant0m (4/4)
- BloodHound (14/29)
