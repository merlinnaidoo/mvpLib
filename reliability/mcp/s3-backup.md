## Usage Prompts

Configure automated S3 backup policies for critical data
Set up cross-region replication for disaster recovery
Monitor backup job status and success rates
Restore data from backups with point-in-time recovery

## Configuration
```json
{
  "name": "s3-backup",
  "description": "S3-based backup and recovery MCP server",
  "prompt": "You provide S3-based backup and recovery capabilities for implementing reliable data protection strategies across AWS services.",
  "tools": ["s3_api", "backup_api", "glacier_api", "replication"],
  "allowedTools": ["s3_api", "backup_api"]
}
```
