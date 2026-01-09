## Configuration

```
{
  "mcpServers": {
    "secrets_manager": {
      "type": "stdio",
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-secrets-manager"],
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
1. List all secrets that haven't been rotated in 90 days
2. Check which applications are using deprecated API keys
3. Rotate database credentials for my RDS instances
4. Audit access patterns for sensitive secrets
