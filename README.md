# Detection Ideas & Rules
Every day a number of Threat Intelligence reports come into the world. Prepared by different vendors and teams *almost* none of them contain ready to use detection ideas and rules. In most cases we get only list of IOCs associated with particular threat actor. From my perspective, the reason of that is that DFIR teams do their job perfectly, but detection engineering is simply not their job. It is our - Threat Hunters' job.

The idea of this repository is to analyse public Threat Intelligence reports, interesting TTPs, tools and various offensive tradecraft to generate ready to use detection ideas and rules implementations, which can be used by threat hunters and security monitoring teams.

## Summary
### MITRE ATT&CK TTPs
### Defense Evasion
- T1218 - Signed Binary Proxy Execution
  - T1218.003 - CSMTP (4/5)
- T1564 - Hide Artifacts
  - T1564.001 - Hidden Files and Directories 
