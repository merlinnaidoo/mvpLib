Usage Prompts:
Get cost optimization recommendations from Trusted Advisor
Identify underutilized resources and idle instances
Review security and performance recommendations
Generate comprehensive optimization reports

Configuration
```json
{
  "name": "trusted-advisor",
  "description": "AWS Trusted Advisor optimization recommendations MCP server",
  "prompt": "You provide AWS Trusted Advisor recommendations for cost optimization, security, performance, and fault tolerance improvements.",
  "tools": ["trusted_advisor_api", "support_api", "recommendations"],
  "allowedTools": ["trusted_advisor_api", "support_api"]
}
```
