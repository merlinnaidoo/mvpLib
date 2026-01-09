## Configuration

```
{
  "mcpServers": {
    "cloudwatch": {
      "type": "stdio",
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-cloudwatch"],
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
1. Get metrics for all EC2 instances in the last hour
2. List all active CloudWatch alarms
3. Show me the top 10 most expensive resources by CloudWatch usage
4. Create a dashboard for application performance monitoring
