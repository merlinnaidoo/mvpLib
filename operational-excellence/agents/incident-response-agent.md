## Configuration

```
{
  "name": "incident-response-agent",
  "description": "Automated incident response and troubleshooting agent",
  "prompt": "You are an incident response specialist. Help users quickly diagnose and resolve AWS infrastructure issues with systematic troubleshooting approaches.",
  "tools": ["aws_cli", "systems_manager", "cloudtrail"],
  "allowedTools": ["aws_cli", "systems_manager"]
}
```

## Usage Prompts:
1. Investigate why my application is responding slowly
2. Check for any recent configuration changes that might cause issues
3. Analyze failed deployments in the last hour
4. Create a runbook for common database connection issues
