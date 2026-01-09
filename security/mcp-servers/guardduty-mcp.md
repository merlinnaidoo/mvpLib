## Configuration

```
{
  "mcpServers": {
    "guardduty": {
      "type": "stdio",
      "command": "npx", 
      "args": ["-y", "@modelcontextprotocol/server-guardduty"],
      "env": {
        "AWS_REGION": "us-east-1"
      },
      "disabled": false,
      "autoApprove": []
    }
  }
}
```

## Usage Prompts:
1. Show me all high-severity GuardDuty findings
2. Analyze suspicious network activity in the last week
3. Check for compromised instances or malware detections
4. Generate a security incident report from recent findings
