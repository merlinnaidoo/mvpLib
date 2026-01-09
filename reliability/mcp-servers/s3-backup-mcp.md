# S3 Backup MCP Server

Model Context Protocol server for S3 backup strategies, cross-region replication, and data lifecycle management.

## Configuration

```json
{
  "mcpServers": {
    "s3-backup-mcp": {
      "command": "npx",
      "args": ["@aws/s3-backup-mcp-server"],
      "env": {
        "AWS_REGION": "us-east-1",
        "BACKUP_REGION": "us-west-2",
        "VERSIONING_ENABLED": "true",
        "MFA_DELETE": "true"
      }
    }
  }
}
```

## Usage Prompts

### S3 Backup Strategy Assessment
```
Using S3 backup MCP tools, evaluate current backup strategy:
- Cross-region replication status
- Versioning configuration
- Lifecycle policies
- Backup encryption
- Access logging
- MFA delete protection

Recommend improvements for data durability and availability.
```

### Cross-Region Replication Setup
```
Configure cross-region replication for critical S3 buckets:
- Identify source and destination regions
- Set up replication rules with filters
- Configure storage class transitions
- Enable replication metrics
- Test replication functionality

Ensure compliance with data residency requirements.
```

### Data Lifecycle Management
```
Optimize S3 storage costs with lifecycle policies:
- Analyze access patterns
- Configure intelligent tiering
- Set up glacier transitions
- Implement deletion policies
- Monitor storage class distribution

Balance cost optimization with recovery requirements.
```

### S3 Disaster Recovery Testing
```
Create S3 disaster recovery testing procedures:
- Simulate region failures
- Test cross-region failover
- Validate data integrity
- Measure recovery times
- Document restoration procedures

Generate DR test reports with lessons learned.
```

### Backup Validation and Integrity
```
Implement automated backup validation:
- Verify object checksums
- Test restoration procedures
- Monitor replication lag
- Check encryption status
- Validate access permissions

Create alerts for backup failures or inconsistencies.
```

### S3 Security and Compliance
```
Ensure S3 backup security and compliance:
- Audit bucket policies and ACLs
- Verify encryption at rest and in transit
- Check access logging configuration
- Review IAM permissions
- Validate compliance controls

Generate security assessment reports for backup infrastructure.
```