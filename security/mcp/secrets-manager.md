## Usage Prompts

Securely store and retrieve application secrets
Rotate database passwords and API keys automatically
Manage encryption keys for sensitive data
Audit secret access patterns and usage

## Configuration
```json
{
  "name": "secrets-manager",
  "description": "AWS Secrets Manager secure credential management MCP server",
  "prompt": "You provide secure secrets management capabilities through AWS Secrets Manager for storing and rotating sensitive credentials.",
  "tools": ["secrets_api", "rotation_api", "encryption_api"],
  "allowedTools": ["secrets_api", "rotation_api"]
}
```
