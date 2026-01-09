## Usage Prompts

Investigate why my application is responding slowly
Check for any recent configuration changes that might cause issues
Analyze failed deployments in the last hour
Create a runbook for common database connection issues

## Configuration
```json
{
  "name": "incident-response",
  "description": "Automated incident response and troubleshooting specialist",
  "prompt": "You are an incident response specialist. Help users quickly diagnose and resolve AWS infrastructure issues with systematic troubleshooting approaches.",
  "tools": ["aws_cli", "systems_manager", "cloudtrail"],
  "allowedTools": ["aws_cli", "systems_manager"]
}
```
