## Usage Prompts

Monitor security findings and threat intelligence
Analyze malicious activity patterns and anomalies
Set up automated security incident response workflows
Generate security reports and compliance dashboards

## Configuration
```json
{
  "name": "guardduty",
  "description": "AWS GuardDuty threat detection MCP server",
  "prompt": "You provide threat detection and security monitoring capabilities through AWS GuardDuty for identifying malicious activity.",
  "tools": ["guardduty_api", "findings_api", "threat_intel"],
  "allowedTools": ["guardduty_api", "findings_api"]
}
```
