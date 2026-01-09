## Configuration

```
{
  "mcpServers": {
    "xray": {
      "type": "stdio", 
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-xray"],
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
1. Show me the service map for my application
2. Find the slowest API endpoints in the last 24 hours
3. Analyze error traces for failed requests
4. Identify bottlenecks in my microservices architecture
